# Clean flash:
- Reboot to bootloader
- Run flash.bat in cmd
- Reboot to recovery
- Sideload ROM zip (adb sideload <zip-name>.zip)
- Format data (ignore errors if any)
- Reboot and voila!

# Updating to a newer build (dirty flash):
- Reboot to recovery
- Sideload ROM zip (adb sideload <zip-name>.zip)
- Reboot and voila!

# If sideloading rom gives error 7:
- Reboot to recovery
- Enter fastbootd
- fastboot wipe-super super_empty.img
- Enter recovery
- Sideload the rom zip
- Format data
- Reboot
