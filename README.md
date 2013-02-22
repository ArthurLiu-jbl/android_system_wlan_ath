android_system_wlan_ath
=======================

     AR6kSDK.build_3.1_RC.563 (psyke83 / AR6kSDK.3.1)


More HOW-TO here ("How to support new WiFi card in Android"):
https://community.freescale.com/docs/DOC-93603

More source code here:
http://service.i-onik.de/a10_source_1.5/lichee/linux-3.0/modules/wifi/ar6003/


AR6kSDK driver for Atheros AR6003, from the i.MX53 Android 10.3 tarball here: http://www.freescale.com/webapp/sps/site/prod_summary.jsp?code=IMX53_SW.
To compile, cd AR6kSDK/host/; fix paths in localmake.linux.inc; make.

Find info on ath6kl here:

http://wireless.kernel.org/en/users/Drivers/ath6kl

Product is AR6003 SDIO:
https://www.qca.qualcomm.com/technology/technology.php?nav1=47&product=67
