# sargo_nethunter (Tested on LineageOS 19.1)
Ready-compiled kernel with Kali Nethunter additions for Google Pixel 3A/3A XL (Bonito/Sargo)
--------------

* Flash .zip in lineageos-recovery as ADB Sideload Update
* Flash the magisk module with firmwares

# What works?
- WireGuard
- Packet injection
- Internal monitoring mode (qcacld-3.0)
- Wifi/BT adapters (exc. 88xxAU)
- HID (exc. RNDIS)
- SDR/DVB
- USB Serial Converter (for pn532 attacks)
- Android Binder IPC
- Ethernet adapters
- Low Memory Killer
- Ultra-wideband dongles

# Screenshots
* Working Prolific PL-2303 with PN532 for Mifare attacks
  - ![nfc-list](https://github.com/Nougat-User/sargo_nethunter/blob/main/nfc-list.jpg?raw=true)
* Working USB2Ethernet for sniffing wired connections
  - ![ifconfig](https://github.com/Nougat-User/sargo_nethunter/blob/main/ifconfig.jpg?raw=true)
* Working many WLAN adapters for more fun
  - ![airmon-ng](https://github.com/Nougat-User/sargo_nethunter/blob/main/airmon-ng.jpg?raw=true)
