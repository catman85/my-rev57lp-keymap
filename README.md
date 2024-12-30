# README

## Manually flash a hex file to the arduino pro micro containing the vial binary 
```bash
# double tap the reset button and then quickly
avrdude -p m32u4 -c avr109 -P /dev/ttyACM0 -b 57600 -D -U flash:w:rev57lp.hex:i
```

## After flashing the file specified above, you can configure your keyboard layout with Vial
