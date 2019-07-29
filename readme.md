
# &emsp;&emsp;&emsp;&emsp;BPI-BIT Webduino 固件 & 软件 发布主页

[![Open Source Love](https://badges.frapsoft.com/os/v3/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badge/)
![](https://img.shields.io/github/release/BPI-STEAM/BPI-BIT-Webduino.svg)
![](https://img.shields.io/github/license/BPI-STEAM/BPI-BIT-Webduino.svg)
![](https://img.shields.io/badge/base-JavaScript-BBAA00.svg)
![](https://img.shields.io/badge/support-blockly-red.svg)
![](https://img.shields.io/badge/expand-blocks-BB00EE.svg)
![](https://img.shields.io/badge/languages-Many-00CCCC.svg)

## 烧写教程 

[刷入 Webduino 固件](https://bpi-steam-docs.readthedocs.io/zh_CN/latest/bpi-web/tutorials/flash_web.html)

## 使用文档

[Webduino 标准版文档](https://bpi-steam-docs.readthedocs.io/zh_CN/latest/bpi-web/advanced/index.html)

- [教育版學習手冊（繁体版）](https://tutorials.webduino.io/zh-tw/docs/webbit/index.html)

- [标准版教学文件（简体版）](https://bit.webduino.com.cn/site/zh_cn/tutorials.html)

## 软件支持

- [软件正式发布中心](release.md)

- [Webbit 软件下载](https://github.com/BPI-STEAM/BPI-BIT-WebDuino/releases/tag/DevTools)

- [教育版积木编程网站](https://webbit.webduino.io/blockly)

- [标准版积木编程网站](https://bit.webduino.com.cn/blockly)

## 固件支持

- [Webbit 固件下载](https://github.com/BPI-STEAM/BPI-BIT-WebDuino/releases/tag/FlashTool)

## CHANGELOG

### （固件）20190729 firmware-webbit-20190604.bin

- 同步软件的固件更新，保持一致，在 [releases](https://github.com/BPI-STEAM/BPI-BIT-Webduino/releases) 提供 `FlashWebduino-20190719.zip` 
 一键烧写包。

### （固件）20190708 firmware-webbit-20190604.bin

- 重新发布固件，烧写方式与 MicroPython 一致。
- 跳过生产检测流程，解决大多数红叉问题。
- 默认配置 MQTT 服务器为中国服务器，配合软件运行。

### （软件）20190623 多语言版本

- 添加多语言接口（内测中），暂定快捷键为按下Ctrl+Shift+F1就可以切換到英文語系，Ctrl+Shift+F2是繁中，Ctrl+Shift+F3是簡中。 
- 添加了 MQTT 服务器
- 修复 WIFI 链接硬件

### （固件）20190604 webbit-0.1.10_0604_01.bin

- 修复网页设置 SSID 返回的错误信息
- 修复 MQTT 服务器的配置文件

### （软件）20190529 第一个版本

- 支持物联网开发、支持定制积木插件、支持云端托管、支持简体和繁体等多语言。
- 提供了大量基础教育场景范例、支持分享和转发、载入与保存等基本功能。
- 支持 Windows 离线应用、也支持二次 HTML5（Webcomponents） 、 JavaScript 、 NodeJS 云端开发代码。
