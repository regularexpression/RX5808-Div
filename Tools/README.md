# RX5808-Div-Tool

RX5808 Download Firmware Guide

## 1. STM32 version

The STM32 firmware is STM32_Firmware.zip. STM32 can be downloaded via USB, UART, or SWD, so I won’t go into details.

## 2. ESP32 version

1. Unzip the ESP32_FirmWare.zip folder in this directory and get three xxx.bin files, as shown below:

![image](https://user-images.githubusercontent.com/66466560/183941319-5b98264a-7aaf-42ed-a1c0-3359cdcafc04.png)

2. Unzip the flash_download_tool_3.9.2_0.zip folder in this directory and obtain the following files:

![image](https://user-images.githubusercontent.com/66466560/183941369-ae1474e4-ccc6-4826-a105-4ce33f092943.png)
 
3. Double-click flash_download_tool_3.9.2_0.exe to open the download program:

![image](https://user-images.githubusercontent.com/66466560/183941402-a557a9e5-d548-456c-b53c-5481e826d153.png)

Select ESP32 and click OK.

4. Open the decompressed bin file in the following order:

         bootloader.bin     0x1000
         
         partition-table.bin  0x8000
         
         RX5808.bin        0x10000 
         
 ![image](https://user-images.githubusercontent.com/66466560/183941506-98f46ba4-1fad-475d-91d7-f391da223f43.png)

5. SPIFLASH settings as shown below:

![image](https://user-images.githubusercontent.com/66466560/183941552-d3622ece-0861-4cdc-a700-2601824ec92c.png)
 
6. Select the COM port and download: (The picture below shows the download completion)
 
![image](https://user-images.githubusercontent.com/66466560/183941582-fadea089-f43e-490e-819a-48b0e2b0c2e5.png)

7. Questions
If you encounter screen distortion problems, use the ESP32_FirmWare_Slow firmware.

2022.08.10 The new module version firmware ESP32_Model_FirmWare。
 
