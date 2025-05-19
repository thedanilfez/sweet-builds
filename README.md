# PostmarketOS builds for xiaomi-sweet

This repository contains workflows and configurations to automatically build PostmarketOS edge images for Xiaomi Redmi Note 10 Pro (xiaomi-sweet), device supported by [sm7150-mainline](https://github.com/sm7150-mainline).

# Image Information

The CI builds images with phosh every week. When completed, it uploads artifacts that was built. Theese artifacts contain `boot-xiaomi-sweet.img` and `rootfs-xiaomi-sweet.img`. You need to install sm7150-mainline fork of [U-Boot](https://github.com/sm7150-mainline/u-boot) to boot postmarketOS.

## Downloading

Head to the [Actions](https://github.com/thedanilfez/sweet-builds/actions) tab, select the latest successful build with your desired UI and download artifacts. Flash u-boot to boot partition, `boot-xiaomi-sweet.img` to cache and `rootfs-xiaomi-sweet.img` to userdata.
