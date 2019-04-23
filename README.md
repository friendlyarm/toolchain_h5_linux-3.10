# Get H5_Linux-3.10 BSP toolchain:
```bash
$ cat gcc-linaro-aarch64.tar.xz* >gcc-linaro-aarch64.tar.xz
$ ls gcc-linaro-aarch64.tar.xz gcc-linaro-arm-4.6.3.tar.xz
```
# Add new toolchain to repo:
```
$ split -b 40M toolchain.tar.xz -d -a 1 toolchain.tar.xz

