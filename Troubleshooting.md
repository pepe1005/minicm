# Battery recalibration #
If you're experiencing higher than normal battery drain, try the following:

  1. Charge the device to full battery; let it keep charging until the battery says it is fully charged. Do not just wait until the light is green, it isn't always fully charged, causing a lot of inaccuracies. (You can check by going to: Settings ->; About device ->; Status ->; Battery Level = Full.)
  1. Boot to CWM-recovery
  1. From "advanced" select "wipe battery stats"

**NOTE**: To have the most accurate of battery stats, reboot the device immediately after wiping the battery stats and wait for CyanogenMod to boot completely to the desktop. Once your entire boot is done and you have full access to the device, go ahead and pull the charger and continue with this troubleshooter.

  1. Do not charge the device until after draining the battery completely, resulting in it automatically shutting off.
  1. Recharge the device completely and then use as you normally would.

# Problems Flashing #
If you have flashed (attempted a rom installation) using the Rom Manager and your device is stuck on an opening screen (Boot Animation) we call that a bootloop. If you're stuck in this situation following these instructions will end the loop and get you running again. Root of your SD refers to files that are on your SD but are not inside of a folder. Be patient. Do not get discouraged.

## Bootloop Problem ##
  1. Boot into CWM-recovery
  1. Reflash the latest build from CWM-recovery
  1. Choose "wipe data/factory reset" and confirm your selection.
  1. Once the wipe is complete, reboot your device.

## Some services don't work ##
If after flashing the latest MiniCM build some services such as WiFi, Bluetooth, Telephony, Data traffic, etc. stopped working or cause the device to reboot:
  1. Boot into CWM-recovery
  1. Reflash the latest build from CWM-recovery
  1. Choose "wipe data/factory reset" and confirm your selection.
  1. Once the wipe is complete, reboot your device.

# Market issues #
## Some large apps fail to install ##
The device has a small /cache partition which causes a download not to even start from Market if the app is large in size. To workaround this:
  1. Boot into CWM-recovery
  1. Go into partition tools and choose "wipe cache partition"
  1. Once the wipe is complete, reboot your device and re-download the app. It should work now.

Source:
http://wiki.cyanogenmod.com/index.php?title=Troubleshooting