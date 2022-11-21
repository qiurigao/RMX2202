# RMX2202 TWRP Installer Realme GT Convert  ROM Region and ROOT All Vrsion
1.boot to TWRP

> fastboot boot twrp.img

2. push ROM file to /data/ota.zip

> adb push RMX2202_ROLLBACK.zip /data/ota.zip

3.TWRP install /data/ota.zip

> adb shell "twrp install /data/ota.zip"

4.Go stock Recovery Format data

> adb reboot recovery

## ROOT - Any version available

> fastboot boot twrp.img

> adb push Magisk_alpha.apk /data/magisk.zip

> adb shell "twrp install /data/magisk.zip"

# Download

1.TWRP (Update)

Android 11 or Android 12 https://www.mediafire.com/file/s5tm666gqgl6ylu/twrp-3.6.0-V2.img/file

2.ROLLBACK file

##UI 2.0

CN A.24 https://drive.google.com/file/d/1TFODtSjRdY2EIVKbgcLgY6AiPOXhqu6I/view?usp=sharing

CN A.08 http://www.mediafire.com/file/j3v0moqzb153nrs/GT_A08_OTA_RMX2202.zip

IN https://download.c.realme.com/flash/Early_Access/IN/RMX2202_ROLLBACK_Android11_IN.zip

EU https://download.c.realme.com/flash/DP1_Android_12/EUEX/RMX2202_ROLL%20BACK_Android11_EUEX_0609.zip

##UI 3.0 

CN C.25 https://rbp01.realme.net/GT/UI3.0/RMX2202_11_C_OTA_1250_all_d1bf42_10010111.zip

IN C.25 https://download.c.realme.com/flash/Rollbackpack/realme_GT/RMX2202_11_C_OTA_1250_all_de11f7_00011011.zip

3.Magisk 
https://github.com/topjohnwu/Magisk/releases

# China Region all ver. Dont Flash to TWRP!!!

all CN https://github.com/qiurigao/RMX2202/blob/main/cn.md
