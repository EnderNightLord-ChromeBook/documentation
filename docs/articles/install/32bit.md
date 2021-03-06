# dahliaOS on 32-UEFI

# Installation 

- dahliaOS supports a wide range of devices. This guide will tell you how to flash it on a USB and what hardware you need.

## Flash the ISO

There are two ISOs to choose from, **linux-builds** and **linux-grub-builds**

- Some devices have a 32 bit UEFI that can boot 64 bit OSes but in order to boot, small changes need to be made on the grub bootloader.

The grub builds have these changes so you just need to download and flash.

- Be aware **linux-grub-builds** are made by [HexaOneOfficial](https://github.com/HexaOneOfficial) and they may break your PC.

They are only made for developers or people who know what they're doing!

### Linux-builds-grub

1. Download the latest ISO [here](https://github.com/dahliaos/releases/releases/latest).

2. Download and install Etcher: [Download Etcher](https://www.balena.io/etcher/).

3. Run Etcher, select your dahlia ISO, then your USB device, then select flash.

4. After the process is finished, reboot and select you USB from you boot menu. 

- **!** (You may need to change your boot order in your UEFI first) and also disable secure boot.

## Requirements

### Minimum requirements

- You need at least **512 MB of RAM** and a **64 bit** dual core processor with **Intel HD graphics**

### Recommended requirements

**2 GB of RAM** and **a 64 bit** quad core processor with **Intel HD graphics**

**Note: Nvidia graphics won't work well, use onboard graphics for the best result.**
