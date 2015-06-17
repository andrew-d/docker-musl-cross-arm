# docker-musl-cross-arm

This repository contains a `Dockerfile` that builds an image with the
[musl-cross][1] toolchain installed, cross-compiling to ARM (specifically,
ARMv6 with hardware floating point and the VFPv2 FPU).  I will attempt to
keep the version of musl up-to-date.

This image is also an automated build on the Docker hub - you can fetch it
by running: `docker pull andrewd/musl-cross-arm`

[1]: https://github.com/GregorR/musl-cross
