# Discussion about how to distribute a standard toolchain

* Historically we have an issue with building a standard toolchain and releasing it for Arm cross compiling
  * For instance we are planning to build a Rust xcc toolchain
* New users are challenged to get past the toolchain hurdle
* Distribute the openocd configs and version as well or equivalent device programming software

## Use Docker

* Build a toolchain and create a container, distribute the container
* Docker does diffs
* Maybe could be used for regressions/testing
* PSAS has a machine running on campus we could use
* Docker has a service to host containers

## Docker alternatives

* Use a QEMU image?
  * This sounds interesting...maybe



