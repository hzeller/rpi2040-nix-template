# Barebone rpi2040 project template

The build uses `cmake` as required by the pico-sdk,
but around we wrap a little Makefile that works
around the complicated bootloader interaction via
filesytem (in the pico-sdk they just suggest to
'drag-and-drop', but that is of course a productivity
killer).

