This is a clone of [the official Prometheus images](https://hub.docker.com/u/prom/) for the raspberry pi.

The changes from the original images are :
- added QEmu in the image to allow it to be build on x86 systems (Travis CI)
- built from arm32v6/alpine instead of busybox (QEmu does not work with Busybox)

The following images are available as tags of napnap75/rpi-prometheus :
- prometheus : The Prometheus monitoring system and time series database
- node_exporter : Prometheus exporter for hardware and OS metrics
- alertmanager : The Alertmanager handles alerts sent by client applications such as the Prometheus server.
- blackbox_exporter : The blackbox exporter allows blackbox probing of endpoints over HTTP, HTTPS, DNS, TCP and ICMP.
- snmp_exporter : The SNMP Exporter exposes information gathered from SNMP

The source code is available [here](https://github.com/napnap75/rpi-prometheus) and the images [here](https://hub.docker.com/r/napnap75/rpi-prometheus/).

These images are build every week thanks to Travis CI.
