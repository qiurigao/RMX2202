# RMX2202 TWRP Installer Realme GT Convert  ROM Region and ROOT All Vrsion
1.boot to TWRP

> fastboot boot twrp.img

2. push ROM file to /data/ota.zip

> adb push RMX2202_ROLLBACK.zip /data/ota.zip

3.TWRP install /data/ota.zip

> adb shell "twrp install /data/ota.zip"

4.Go stock Recovery Format data

> adb reboot recovery

5.ROOT - Any version available

> fastboot boot twrp.img

> adb push Magisk_alpha.zip /tmp/magisk.zip

> adb shell "twrp install /tmp/magisk.zip"

# Download

1.TWRP

Android 11 or Android 11 https://www.mediafire.com/folder/hepc8ivdr1wro/TWRP

2.ROLLBACK file

CN ​https://drive.google.com/file/d/1TFODtSjRdY2EIVKbgcLgY6AiPOXhqu6I/view?usp=sharing​​​

IN ​https://download.c.realme.com/flash/Early_Access/IN/RMX2202_ROLLBACK_Android11_IN.zip​​​

EU ​https://download.c.realme.com/flash/DP1_Android_12/EUEX/RMX2202_ROLL%20BACK_Android11_EUEX_0609.zip​​​

3.Magisk 
https://github.com/vvb2060/magisk_files/raw/alpha/app-release.apk

# China Region all ver. Dont Flash to TWRP!!!

all CN https://github.com/qiurigao/RMX2202/blob/main/cn.md
