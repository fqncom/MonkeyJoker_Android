# MonkeyJoker_Android
MonkeyJoker for android

***
## 版本更新概况
* 2016.02.22 项目初步结构确定


---
## 项目工具及开发环境
* 该项目使用统一的keystore
* jdk版本为1.8及以上
* 使用AndroidStudio作为IDE
* compileSdkVersion 22
* buildToolsVersion "22.0.1"
* minSdkVersion 14
* targetSdkVersion 22

## 项目目录结构
##### 初步结构

### app ---module
 * libs   --- jar包
 * src
  - assets
  - com
    - bean --- bean类
    - base --- 基类
    - application
    - ui   --- activity / fragment
    - adapter
    - interface
    - listeners --- 事件监听
    - view --- 自定义view
    - tools --- 可独立于项目的各种工具类
    - utils  --- 依赖于项目的工具类
    - data  ----constants
    - api --- 存放api连接


  - res
    - anim
    - layout
    - drawable-xxx ---存放自定义样式， .9文件，第三方资源文件
    - mipmap-xxx
    - values
      - strings
      - styles
      - colors
    - menu
