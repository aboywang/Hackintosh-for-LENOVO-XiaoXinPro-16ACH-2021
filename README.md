## Hackintosh for LENOVO XiaoXinPro 16ACH 2021

##### **attention:**

- This 'EFI' file is only available for **macOS Ventura 13.5**,if you need the higher version compared  to Monterey,you must replace the crucial files of the 'EFI',like bluetooth,to ensure your PC could work well.
- IF the temperature of  your laptop's CPU is too high, you probably need to limit it with the 'AMD Power Gadget' application in the Tools folder.
- GPUs cannot be hard-coded, only soft-coded. I used the deprecated "BFixup.kext", which may have slowed down OpenGL or caused hardware acceleration to fail completely. But the good thing is that if you add this kext, the daily use of the software will be much better.

##### support situation:

|   Hardware   |             Detail              |           Run           |
| :----------: | :-----------------------------: | :---------------------: |
|     CPU      |        AMD Ryzen 7 5800H        |          well           |
|     GPU      | Radeon Graphics(max support 2G) |          well           |
|    Memory    |               16G               |          well           |
|    Sound     |  ALC0257(ALC257, layout-id=11)  |          well           |
|     HDMI     | Radeon Graphics(max support 2G) | unknown(needed to test) |
| Network Card |        Intel AX210 WiFi6        |          well           |
|  Bluetooth   |        Intel AX210 WiFi6        |          well           |
|    iCloud    |           System App            |          well           |
|    Camera    |            FaceTime             |          well           |
|   Battery    |             Lenovo              |          well           |

##### screenshot of the effect:

![image](/effect/effect1.png)

![image](/effect/effect2.png)

![image](/effect/effect3.png)

##### Learning and communication:

![image](QR.png)

##### thanks:

Thanking [nootedred](https://github.com/ChefKissInc/NootedRed) for supporting macOS on AMD platform.
