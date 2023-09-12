# sargo_nethunter
Ready-compiled kernel with Kali Nethunter additions for Google Pixel 3A/3A XL (Bonito/Sargo)
Tested on LineageOS 19.1
-------------------

Flash .zip in lineageos-recovery as ADB Sideload Update;
After move all *.ko file in /vendor/lib/modules. Or make magisk script like this:

* /data/adb/service.d/load.sh (chmod 755):
    insmod /data/adb/wlan.ko
    insmod /data/adb/lcd.ko

