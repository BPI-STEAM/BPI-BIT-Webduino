# ESPtool烧录方法介绍
> 首先根据[esptool github](https://github.com/espressif/esptool#usage)有详细介绍esptool的用法，下面以实际烧录语句来介绍用法。

## 烧录指令：
```
esptool.py --chip esp32 --port /dev/ttyUSB0 --baud 460800 write_flash -z --flash_mode dio --flash_freq 40m 0x1000 bit_BL_DIO_40M.bin 0x8000 bit_partitions.bin 0xe000 bit_boot_app0.bin 0x10000 bit_default.bin
```
> 包含在`esptool.py -h`

`--chip` 指定烧录芯片，可选项有[`auto`,`esp8266`,`esp32`],这里使用`esp32`。
`--port` 指定烧录端口，在linux下面bit的端口为`/dev/ttyUSB*`，在windows下面bit的端口为`COM*`
`--baud` 指定烧录端口速率，可以选用一些常用端口速率，115200、460800、921600或1152000等等，不仅限于这里提到的速率。

> 包含在`esptool.py wirte_flash -h`

`wirte_flash` 指定写入flash模式，通常会配合`-z`或者`--compress`使用，目的是压缩传输数据。
`--flash_mode` 指定SPI flash的模式，可选[`keep`,`qio`,`qout`,`dio`,`dout`]，也可以简写为`-fm`
`--flash_freq` 指定SPI flash的频率，可选[`keep`,`40m`,`26m`,`20m`,`80m`]，也可以简写为`-ff`
`--flash_size` 指定SPI flash的大小（MegaBytes为单位），可选啊[`1MB`, `2MB`, `4MB`, `8MB`, `16M`]，也可以简写为`-fs`
`<address> <filename>` 地址后跟二进制文件名，用空格分隔
