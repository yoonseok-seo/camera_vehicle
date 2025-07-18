A VEHICL with a CAMERA


Purpose: Collect and analyze camera information

chipset: nxp  IMX8mp

version:
          kernel 5.10.72.2.2.0

          u-boot 2021.04

 u-boot


1) Unlock a compressed file (u-boot_01.egg)
   -->  u-boot-imx_20420829.tar.gz

2) Unlock the compressed file(u-boot-imx_20420829.tar.gz)

    $mkdir u-boot-imx
  
    $cd   cd u-boot-imx
  
    $tar cvfz u-boot-imx_20420829.tar.gz

3) u-boot build
 
   $ ./uboot_make.sh imx8mp_mv_defconfig

   $ ./uboot_make.sh 

======================================================================

Kernel

1) Unlock a compressed file

   linux-imx_01.ovl.egg, linux-imx_01.ov2.egg, linux-imx_01.ov3.egg, linux-imx_01.ov4.egg

   linux-imx_01.ov5.egg, linux-imx_01.ov6.egg, linux-imx_01.ov7.egg, linux-imx_01.ov8.egg

   linux-imx_01.ov9.egg, linux-imx_01.ovl10.egg

   --> linux-imx_20240829.tar.gz

3) Unlock the compressed file(linux-imx_20240829.tar.gz)
  
   $mkdir linux-imx 

   $tar cvfz linux-imx_20240829.tar.gz
  
3) kernel build

   $./kernel_make.sh mv_v8_defconfig
 
   $./kernel_make.sh







