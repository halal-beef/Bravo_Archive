<img align="right" src="https://github.com/halal-beef/res/blob/main/htc_desire_450x450x32_fill.png" width="350" alt="HTC Desire">

# Bravo Archive

## Files

- revolutionary-0.4pre4-patched ```Revolutionary S-OFF that was patched to have the key check removed``` 
- 4EXT_PB99IMG.zip ```4EXT Touch Recovery as an RUU zip```
- PB99IMG.zip ```Android Gingerbread RUU zip```
- PB99IMG_downgrade.zip ```RUU Zip to help revert HBOOT versions / Help restoring the stock partition table```

## Guides

### Flashing an RUU without a Micro SD Card

- Boot your HTC Desire into fastboot mode
- Open cmd on your computer
- Run the command ```fastboot oem rebootRUU```
- Run the command ```fastboot flash zip <RUUZip>``` where ```<RUUZip>``` is the RUU Zip you want to flash
- Reboot the phone via the command ```fastboot reboot```

### Reverting H-Boot versions or restoring the partition table

> **Warning** You need to make sure you have your device S-OFF'ed already!

- Boot into RUU Mode
- Open cmd on your computer
- Run the command ```fastboot oem rebootRUU```
- Run the command ```fastboot flash zip PB99IMG_downgrade.zip```
- Run the command ```fastboot oem rebootRUU```
- Flash a stock RUU, by using the guide above

## Troubleshooting

### Radio doesn't flash or seems bricked

- When this happens there is a 40% chance that your radio is bricked and as of right now I don't think there is a way to unbrick the radio
- 60% of the time tho, the phone is just simply too hot and radio will refuse to flash, make sure you take out the battery and put the phone on a cool surface to cool down (preferrably metal), Please note you probably shouldn't put your phone into a fridge or a freezer
