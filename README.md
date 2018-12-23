MECHREVO X1 hackintosh EFI folder
=================================

Done on a MECHREVO X1 modified with a BCM94352Z Wi-Fi card

Hardware:
* i7-7700HQ
* Intel HD 630
* GTX 1060 (disabled)
* ALC269VC audio
* ELAN touchpad
* BCM94352Z WiFi card
* RTL8111 Gigabit ethernet

What works:
* Wifi
* Ethernet
* Sleep
* Mouse
* Keyboard
* Trackpad
* Brightness adjustment
* USB 2/3
* AirDrop
* Sound


What doesn't work:
* NTFS write
* NVMe support
* Retain backlight level (need to implement NVRAM support)

To do:
* ~~create custom SSDT for USB ports~~ Done!
* ~~Test different layouts for ALC269 from https://github.com/acidanthera/AppleALC/wiki/Supported-codecs~~

