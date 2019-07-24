# asuswrt_rt-ac85u
#### How to build in ubuntu 18.04 LTS:
``` bash
sudo apt-get install libncurses5 libncurses5-dev m4 bison gawk flex libstdc++-4.8-dev g++-multilib g++ gengetopt git gitk zlib1g-dev autoconf autopoint libtool shtool autogen mtd-utils intltool sharutils docbook-xsl-* libstdc++5 texinfo dos2unix xsltproc binutils u-boot-tools device-tree-compiler python qemu gperf liblzo2-dev uuid-dev build-essential lzma-dev liblzma-dev lzma patch cmake intltool libglib2.0-dev gtk-doc-tools libc6-i386 lib32stdc++6 lib32z1 libelf1:i386 lib32ncurses5 libc6-dev-i386
```

``` bash
cd /opt
git clone https://github.com/ferhung-mtk/asuswrt_rt-ac85u.git
```

``` bash
sudo mv /opt/asuswrt_rt-ac85u/* /opt/
cd /opt/release/src-ra-5010
```

``` bash
export PATH=/opt/brcm/hndtools-mipsel-linux/bin:$PATH
export PATH=/opt/brcm/hndtools-mipsel-uclibc/bin:$PATH
export PATH=/opt/buildroot-gcc463/bin:$PATH
```

``` bash
make rt-ac85u

```

