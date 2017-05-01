# docker-gentoo-xdistccd-s3
gentoo docker image, cross compiler of stage3


crossdev stage options:

* -s0, --stage0  Build just binutils
* -s1, --stage1  Also build a bare C compiler (no C library/C++/shared GCC libs/C++ exceptions/etc...)
* -s2, --stage2  Also build kernel headers
* -s3, --stage3  Also build the C library
* -s4, --stage4  Also build a full compiler [default]


# base image stack

*    [samuelololol/docker-gentoo-crossdev-distccd](https://hub.docker.com/r/samuelololol/docker-gentoo-crossdev-distccd/)
*    [samuelololol/docker-gentoo-websync](https://hub.docker.com/r/samuelololol/docker-gentoo-websync/)
*    [gentoo/stage3-amd64](https://hub.docker.com/r/gentoo/stage3-amd64/)
