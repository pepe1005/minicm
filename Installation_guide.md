# Requirements #
You need to fulfill the following requirements in order to install MiniCM
  * [Root](http://forum.xda-developers.com/showthread.php?t=833722) and [CWM Recovery](http://forum.xda-developers.com/showthread.php?t=1105745) already installed
  * Latest 2.1.1.A.0.6 SE firmware due to kernel dependencies.

In order to check your firmware version go to Settings -> About phone
Your firware version should be reported as: 2.1.1.A.0.6. If it's not, you need to get there. Try updating via SEUS or PC-Companion. If it still does not push the needed firware to your device, use the following approach.

## Force-update to 2.1.1.A.0.6 ##
  * Grab [this](http://code.google.com/p/minicm/downloads/detail?name=build.prop#makechanges) build.prop file and copy it to your sdcard
  * Using Root explorer, backup your /system/build.prop file and copy the grabbed build.prop file to /system/build.prop
  * Reboot twice and try to re-update your firware. You might need to force-update if SEUS or PC-Companion says you already have the latest firware.
  * Once the update completes, check again your firmware version.

# Installing MiniCM10 #

## Installing the nAa-jb kernel ##
  * Download the latest flashtool from here: http://androxyde.github.com/
  * Install flashtool
  * Unlock your bootloader as described here: http://forum.xda-developers.com/showpost.php?p=17384177&postcount=3 or here: http://forum.xda-developers.com/showthread.php?t=1254225
  * Download the latest nAa-jb kernel ftf file for your device from the downloads page and move it to Flashtool\firmwares so that Flashtool can pick it up
  * Flash the kernel via Flashtool
  * Reboot and press the back button repeatedly to enter recovery
  * The bootlogo should report the new kernel version

## Installing the MiniCM10 ROM ##
  * Download the latest MiniCM10 ROM for your device from the 'Downloads' page
  * Backup your /data contents: contacts, apps, sms, etc.
  * Download the latest gapps-jb-xxxxxxxx-signed.zip from the downloads page
  * Copy the MiniCM10-4.x.x-'device'.zip, as well as the gapps-jb-xxxxxxxx-signed.zip that you previously downloaded to your sdcard (top level)
  * Reboot to CWM recovery
  * Keep a backup of your current status using CWM's Backup & Restore in case you want to restore
  * Select 'mounts and storage' then 'format /cache', 'format /data' and 'format /system' if you were not already using MiniCM10
  * Click the back button and select 'install zip from sdcard' then 'choose zip from sdcard' and select the MiniCM10-4.x.x-'device'.zip and select yes
  * Select 'choose zip from sdcard' and select the gapps-jb-xxxxxxxx-signed.zip and select yes
  * Reboot (first boot will take ~2 mins)
  * Once your device has booted, you can navigate to Settings -> System -> Update notifications and select 'Register'. This way you can get update notifications on new versions of MiniCM10 and nAa-jb kernel!

Note that if you don't stick to the above instructions you might get various problems (WiFi, Data traffic, Bluetooth etc). In that case, and before reporting an issue, select 'wipe data/factory reset' from the top menu of CWM Recovery and Reboot

# Installing MiniCM9 #

## Installing the nAa-ics kernel ##
  * Download the latest flashtool from here: http://androxyde.github.com/
  * Install flashtool
  * Unlock your bootloader as described here: http://forum.xda-developers.com/showpost.php?p=17384177&postcount=3 or here: http://forum.xda-developers.com/showthread.php?t=1254225
  * Download the latest nAa-ics kernel ftf file for your device from the downloads page and move it to Flashtool\firmwares so that Flashtool can pick it up
  * Flash the kernel via Flashtool
  * Reboot and press the back button repeatedly to enter recovery
  * The bootlogo should report the new kernel version

## Installing the MiniCM9 ROM ##
  * Download the latest MiniCM9 ROM for your device from the 'Downloads' page
  * Backup your /data contents: contacts, apps, sms, etc.
  * Download the latest gapps-ics-xxxxxxxx-signed.zip from here: http://goo.im/gapps/
  * Copy the MiniCM9-3.x.x-'device'.zip, as well as the gapps-ics-xxxxxxxx-signed.zip that you previously downloaded to your sdcard (top level)
  * Reboot to CWM recovery
  * Keep a backup of your current status using CWM's Backup & Restore in case you want to restore
  * Select 'mounts and storage' then 'format /cache' and 'format /data' if you were not already using MiniCM9
  * Click the back button and select 'install zip from sdcard' then 'choose zip from sdcard' and select the MiniCM9-3.x.x-'device'.zip and select yes
  * Select 'choose zip from sdcard' and select the gapps-ics-xxxxxxxx-signed.zip and select yes
  * Reboot (first boot will take ~2 mins)
  * Once your device has booted, you can navigate to Settings -> System -> Update notifications and select 'Register'. This way you can get update notifications on new versions of MiniCM9 and nAa-ics kernel!

Note that if you don't stick to the above instructions you might get various problems (WiFi, Data traffic, Bluetooth etc). In that case, and before reporting an issue, select 'wipe data/factory reset' from the top menu of CWM Recovery and Reboot

# Installing MiniCM7 #

## Installing the nAa kernel ##
  * Download the latest flashtool from here: http://androxyde.github.com/
  * Install flashtool
  * Unlock your bootloader as described here: http://forum.xda-developers.com/showpost.php?p=17384177&postcount=3 or here: http://forum.xda-developers.com/showthread.php?t=1254225
  * Download the latest nAa kernel ftf file for your device from the downloads page and move it to Flashtool\firmwares so that Flashtool can pick it up
  * Flash the kernel via Flashtool
  * Reboot and press the back button repeatedly to enter recovery
  * The bootlogo should report the new kernel version

## Installing the MiniCM7 ROM ##
  * Download the latest MiniCM7 ROM for your device from the 'Downloads' page
  * Backup your /data contents: contacts, apps, sms, etc.
  * Download the latest gapps-gb-xxxxxxxx-signed.zip from here: http://goo.im/gapps/
  * Copy the MiniCM7-2.x.x-'device'.zip, as well as the gapps-gb-xxxxxxxx-signed.zip that you previously downloaded to your sdcard (top level)
  * Reboot to CWM recovery
  * Keep a backup of your current status using CWM's Backup & Restore in case you want to restore
  * Select 'mounts and storage' then 'format /cache' and 'format /data' if you were not already using MiniCM7
  * Click the back button and select 'install zip from sdcard' then 'choose zip from sdcard' and select the MiniCM7-2.x.x-'device'.zip and select yes
  * Select 'choose zip from sdcard' and select the gapps-gb-xxxxxxxx-signed.zip and select yes
  * Reboot (first boot will take ~2 mins)
  * Once your device has booted, you can navigate to Settings -> System -> Update notifications and select 'Register'. This way you can get update notifications on new versions of MiniCM7 and nAa kernel!

Note that if you don't stick to the above instructions you might get various problems (WiFi, Data traffic, Bluetooth etc). In that case, and before reporting an issue, select 'wipe data/factory reset' from the top menu of CWM Recovery and Reboot

# Installing MiniCM6 #
  * Download the latest MiniCM6 ROM for your device from the 'Downloads' page
  * Rename the 'release'.zip file to update.zip
  * Copy the update.zip to your sdcard (top level). E.g via your PC or via 'adb push update.zip /sdcard/'
  * Reboot to CWM recovery
  * Keep a backup of your current status using CWM's Backup & Restore in case you want to restore.
  * Select 'wipe data/factory reset' if you were not already using MiniCM6
  * Select 'apply update from sdcard' from the top menu of CWM recovery
  * Reboot (first boot will take ~2 mins)

Note that if you don't stick to the above instructions you might get various problems (WiFi, Data traffic, Bluetooth etc). In that case, and before reporting an issue, select 'wipe data/factory reset' from the top menu of CWM Recovery and Reboot

# Installing themes or additional stuff posted #
Installing additional themes or other stuff posted at the downloads page, require a similar procedure like the one described before:
  * Download
  * Rename to update.zip
  * Push update.zip to your sdcard. E.g: adb push update.zip /sdcard/
  * Reboot to CWM recovery
  * Select 'apply update from sdcard' from the top menu of CWM recovery
  * Reboot