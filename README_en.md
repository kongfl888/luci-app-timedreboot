# Timed Reboot for OpenWrt

<br>English | [简体中文](README.md)

## A lightweight, completely rewritten OpenWrt timed restart.

<img alt="Preview" src="https://raw.githubusercontent.com/animegasan/mikwrt/main/preview/luci-app-timedreboot.png"/>

## Compile method
* Copy to `package` directory
* Run make menuconfig
* Select plugin
* Then
  ```
  make package/luci-app-timedreboot/compile V=99
  ```
* Files are found in bin

You can also find the ipk file in Releases to download and install it into your openwrt.

[LICENSE](LICENSE)
