# micropython_esp32_firmware

## Flash Firmware to ESP32

- windows command

```shell
esptool -p COM7 -b 921600 --before default_reset --after hard_reset --chip esp32  write_flash 0x1000 firmware.bin --erase-all
```
