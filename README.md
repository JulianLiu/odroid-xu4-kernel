# odroid-xu4-kernel
The kernel snap for odroid-xu4 board


## Building

To cross build this kernel, use gcc-linaro-arm-linux-gnueabihf-4.9-2014.09 [here](https://dn.odroid.com/toolchains/)
Set environment variable before running `snapcraft`

```shell
$ export ARCH=arm
$ export CROSS_COMPILE=/opt/toolchains/gcc-linaro-arm-linux-gnueabihf-4.9-2014.09_linux/bin/arm-linux-gnueabihf- 
$ snapcraft --target-arch=armhf
```
