This is a clone of [the official Prometheus images](https://hub.docker.com/u/prom/) for the raspberry pi.

The changes from the original images are :
- added QEmu in the image to allow it to be build on x86 systems (Travis CI)
- built from armhf/alpine instead of busybox (QEmu does not work with Busybox)

The following images are available as tags of napnap75/rpi-prometheus :
- prometheus : the main program

The source code is available [here](https://github.com/napnap75/rpi-prometheus) and the images [here](https://hub.docker.com/r/napnap75/rpi-prometheus/).

These images are build every week thanks to Travis CI.