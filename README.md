## platform-udoo

***

This repo contains all platform-specific files, used by the Volumio Builder to create a **udoo-neo** and **udoo-qdl** images.

###U-Boot Sources

udoo-neo: [https://github.com/UDOOboard/uboot-imx](https://github.com/UDOOboard/uboot-imx) 
Branch: 2015.04

udoo-qdl: [https://github.com/UDOOboard/uboot-imx](https://github.com/UDOOboard/uboot-imx)
Branch: 2015.10.fslc-qdl


**Note:** This repo contains u-boot patches for the corresponding boards. 
Use the patch before compiling your own u-boot, it enables the use of initramfs.

###Kernel Sources: 

udoo-neo: [git clone https://github.com/UDOOboard/linux_kernel](git clone https://github.com/UDOOboard/linux_kernel) 
Branch: default
Config: udoo_neo_defconfig

udoo-neo: [git clone https://github.com/UDOOboard/linux_kernel](git clone https://github.com/UDOOboard/linux_kernel) 
Branch: default
Config: udoo_quad_dual_defconfig

**Note:** Before compiling the kernel, use the overlayfs patch in this repo. 

**Platform files for udoo-neo**
- 20170207: Initial version


**Platform files for udoo-qdl**
- 20170207: Initial version

