Some Notes about this project...
It took some work to get the NavX's firmware updated...
Here is the fix which was posted by JamesT to CD Here. 
https://www.chiefdelphi.com/t/cant-update-navx-mxp-firmware/422156/2

```
If you open Device Manager, is there a “STM32 BOOTLOADER” under Universal Serial Bus devices?

If so:

Right-Click on the STM32 BOOTLOADER and select Update driver
Choose, Browse my computer for drivers
Let me pick from a list of available drivers on my computer
In the list of compatible hardware, select: “STM Device in DFU Mode” and hit Next
The device should now be using the STM Device in DFU Mode driver, and you will be able to update the firmware.
```