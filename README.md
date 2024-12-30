## Readme

# to manually flash a hex file to an arduino pro micro
# double tap the reset button and then quickly
```bash
avrdude -p m32u4 -c avr109 -P /dev/ttyACM0 -b 57600 -D -U flash:w:rev57lp.hex:i
```

# After flashing the file specified above, you can configure your keyboard layout with Vial
