# linkit-smart-uboot
This feeds holds the UBoot bootloader source code for the LinkIt Smart 7688 (Duo)

# ubuntu

```
sudo apt update
sudo apt -y install make gcc libc6-i386 zlib1g-dev libncurses5-dev git realpath
```

# Compile

Start by cloning the tree

`git clone https://github.com/MediaTek-Labs/linkit-smart-uboot.git`

We need to install the cross toolchain required to build the source

`sudo tar xjf buildroot-gcc342.tar.bz2 -C /opt/`

Finally we can start building the source

`make`

Notes: Uboot firmware is uboot.bin NOT uboot.img
