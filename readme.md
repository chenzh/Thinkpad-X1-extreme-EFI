## The part that can work
* Sound card (AppleALC)
* intel cable Gigabit LAN (mini RJ45)
* intel integrated graphics
* nvidia graphics card (screened off, power saving, although the dual graphics card is no problem, but mojave no nvidia graphics driver)
* Battery level display (DSDT patch, you can use RehabMan/thinkpad x230i patch directly)
* Machine sleep
* usb port configuration
* Touchpad and touch screen (multi-finger touch is not yet completed)
* Keyboard function keys, volume and screen brightness (DSDT EC _Q14, _Q15 patch)

## Installation Precautions
* Installation must be started using config-install.plist, the installation uses fake-id 0x12345678

## Waiting for the perfect part
* Touchpad multi-touch driver
* Touch screen multi-touch driver
* The first time the machine opens, there is a problem that cannot be started.