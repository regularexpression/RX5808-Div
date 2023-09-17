# RX5808-Div
## 1. The interface design is based on [LVGL](https://github.com/lvgl/lvgl)

See the [demonstration video](https://www.bilibili.com/video/BV1yr4y1371b).

![ui](https://user-images.githubusercontent.com/66466560/218503938-571cd1fa-2c89-4279-a6aa-281c7fcf8234.jpeg)

## 2. Control
- Long press the OK button on the main interface to lock/unlock the manual channel, short press to enter the menu; when unlocked, press up, down, left, and right to adjust the frequency.
- The menu interface is divided into three parts:
  - Scan;
  - Settings;
  - About.

  Press up and down to switch menu options, confirm to enter the submenu, and left click to return to the main interface.
  
- The scan menu has three sub-contents:
  - The graph scan shows the signal strength of frequency 5300-5900MHz;
  - The table scan display displays the image transmission channel signal strength in different colors. After the scan is completed, the frequency is switched to the channel with the best current signal strength and is displayed in the upper right corner.
  - RSSI calibration is used to calibrate RSSI. If image transmission is not turned on, the calibration will fail. If it succeeds, the result will be saved.

- In the setting interface, you can set the display backlight intensity, fan speed, boot animation, buzzer, etc. to be turned on. The OSD format needs to be saved and re-opened on the main page to take effect.

- Display relevant information on the interface.

 

## 3. OSD

The OSD function was added by Lin Baobao (Bilibili ID). It is in non-overlay mode and can be turned on by unlocking it on the main interface.

See the [demonstration video](https://www.bilibili.com/video/BV1ya411g78U).
Fully synchronized with receiver UI.

![osd](https://user-images.githubusercontent.com/66466560/218504602-102e7fe0-b935-48ca-be9e-f459200034c8.jpg)


## 4. Hardware opensource design
https://oshwhub.com/ftps/rx5808-div
