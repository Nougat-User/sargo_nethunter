# sargo_nethunter (Tested on LineageOS 19.1)
Ready-compiled kernel with Kali Nethunter additions for Google Pixel 3A/3A XL (Sargo/Bonito)
--------------

* Flash .zip in lineageos-recovery as ADB Sideload Update
* Flash the magisk module with firmwares

# What works?
- Wireguard support
- Frames injection support
- Internal monitoring mode support (qcacld-3.0)
- Wifi/BT adapters support
- HID support
- SDR/DVB support
- USB Serial Converter support (for pn532 attacks)
- Android Binder IPC support
- Ethernet adapters
- BBR TCP by default
- Loadable Module Support
- Ext2/Ext3 support

# Screenshots
* Working Prolific PL-2303 with PN532 for Mifare attacks
  - ![nfc-list](https://github.com/Nougat-User/sargo_nethunter/blob/main/nfc-list.jpg?raw=true)
* Working USB2Ethernet for sniffing wired connections
  - ![ifconfig](https://github.com/Nougat-User/sargo_nethunter/blob/main/ifconfig.jpg?raw=true)
* Working many WLAN adapters for more fun
  - ![airmon-ng](https://github.com/Nougat-User/sargo_nethunter/blob/main/airmon-ng.jpg?raw=true)

# Sources
https://github.com/Nougat-User/nethunter_kernel_google_msm-4.9
