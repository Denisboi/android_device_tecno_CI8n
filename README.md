# ALPHA TWRP for Tecno Camon 19 Pro

### Checks

- [X] Correct screen/recovery size
- [ ] Working Touch, screen(so it works, but it’s impossible to use)
- [X] Backup to internal/microSD
- [X] Restore from internal/microSD
- [ ] reboot to system(not tested)
- [X] ADB
- [ ] update.zip sideload(not tested)
- [ ] Screen goes off and on
- [X] F2FS/EXT4 Support, exFAT/NTFS where supported
- [X] all important partitions listed in mount/backup lists
- [ ] backup/restore to/from external (USB-OTG) storage (not tested)
- [ ] decrypt /data(not tested)
- [ ] Correct date
- [X] MTP export
- [X] reboot to bootloader
- [X] reboot to recovery
- [X] poweroff
- [X] battery level
- [X] temperature
- [X] input devices via USB (USB-OTG) - keyboard, mouse and disks
- [ ] USB mass storage export (not tested)
- [X] set brightness
- [ ] vibrate
- [X] screenshot
- [X] partition SD card
- [X] 120 HZ

## Building

```bash
source build/envsetup.sh; export ALLOW_MISSING_DEPENDENCIES=true; lunch twrp_CI8n-eng && mka bootimage;
```
