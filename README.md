# upy-bin
Highly experimental micropython binaries

In this repository I share builds of some of my micropython pull requests.

The binaries here *might* work (**or not**), get only sporadic updates 
and are copies of the firmware.bin files created during compilation.

To flash, use e.g.
```
esptool.py --chip esp32 --port /dev/ttyUSB0 write_flash -z 0x1000 esp32-GENERIC-ext1_reason-8a5d88555.bin
```
