---
sort: 8
---

# Q&A

### 1、如何获取配套Android app

  [下载apk文件并安装](https://github.com/addison-CQ/webPages/tree/develop/doc/ESP32SensorKit)
  
### 2、程序依赖的库无法在线安装

  在本仓库[Board/ESP32SensorKit/ArduinoDependence](https://github.com/addison-CQ/webPages/tree/develop/Board/ESP32SensorKit/ArduinoDependence)目录下选择所需的软件包，下载后解压至本地C:\Users\用户名\Documents\Arduino\libraries目录下

### 3、开发板正常工作，但ArduinoIDE无法检测到开发板或无法下载程序
  1. 持续按下开发板BOOT按键
  2. 按下开发板RST按键持续1秒后松开
  3. 松开开发板BOOT按键

### 4、Card Mount Failed
开发板上电后，屏幕显示图中信息，请检查SD卡是否正确安装在开发板背部的SD卡卡槽内

<img decoding="async" src="https://addison-cq.github.io/webPages/images/IMG_20221208_154101_edit_494093426512107.jpg" width="70%">

### 5、MAX3010x Start Failed
开发板上电后，屏幕显示图中信息，请检查MAX3010x模块是否正常连接至开发板右侧8P排母

<img decoding="async" src="https://addison-cq.github.io/webPages/images/IMG_20221208_154012_edit_494062645760549.jpg" width="70%">

### 6、如何判断电池充放电状态

开发板可以使用USB接口供电，或者锂电池供电。同时也可以通过USB给锂电池充电。可以根据板上绿色LED充电指示灯进行判断。

* 绿灯闪烁时表示开发板使用USB供电
* 绿灯常亮时表示开发板使用锂电池供电
* 绿灯灭表示锂电池充电满

![](https://addison-cq.github.io/webPages/images/ESP32_charge.jpg)
