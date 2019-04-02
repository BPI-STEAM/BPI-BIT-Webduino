# BPI-BIT Webduino  [![MIT](https://img.shields.io/github/license/mashape/apistatus.svg?style=for-the-badge)](./LICENSE)

## BPI-BIT Webduino相关网站：

[中国大陆地区官方网站](https://webduino.com.cn)

[中国港澳台以及其他地区官方网站](https://webduino.io/)

[BPI-BIT官方英文论坛](http://forum.banana-pi.org/c/bpi-webduino/BPI-Webduino)

[BPI-BIT官方中文论坛](https://forum.banana-pi.org.cn/c/bpi-webduino/webduino)

## 固件烧录：

> 固件存放位置在[Bin](/Bin)目录下面

- #### Bin目录介绍(仅适用于Windows)：
    + bit_default.bin : BPI-BIT板的标准Webduino固件
    + bit_stable.bin : BPI-BIT板的stable版本Webduino固件
    + boot_app0.bin : Espressif-WROOM-32主核心驱动
    + partitions.bin : BPI-BIT的Webduino固件分区表文件
    + bootloader_dio_40m.bin : Espressif-WROOM-32的bootloader(适用于速度为40MHz的DIO烧录模式)

- #### AutoFlash目录介绍(仅适用于Windows)：
    + AutoErase.exe : 自动清除bit板内存脚本工具
    + AutoFlashWebduinoBin.exe : 自动烧录bit板webduino固件脚本工具
    + webduino.bin : BPI-BIT板的Webduino固件
    + boot_app0.bin : Espressif-WROOM-32主核心驱动
    + partitions.bin : BPI-BIT的Webduino固件分区表文件
    + bootloader_dio_40m.bin : Espressif-WROOM-32的bootloader(适用于速度为40MHz的DIO烧录模式)

### 各个操作系统下的烧录方式：

> #### 工具：[ESP FLASH DOWNLOAD TOOL](/Windows/FLASH_DOWNLOAD_TOOLS_V3.6.4.rar)(Windows)

[ESP FLASH DOWNLOAD TOOL烧录方法(Wiki)](https://github.com/BPI-STEAM/BPI-BIT-WebDuino/wiki#esp-flash-download-tool)

> #### Auto Flash工具：[AutoFlashWebduinoBin](/AutoFlash)(Windows)

[Auto Flash工具烧录方法(Wiki)](https://github.com/BPI-STEAM/BPI-BIT-WebDuino/wiki#auto-flash%E5%B7%A5%E5%85%B7)

> #### ESPtool工具：[ESPtool安装(github)](https://github.com/espressif/esptool#installation--dependencies)(Windows&linux&macOS)

[ESPtool介绍(github)](https://github.com/espressif/esptool)
