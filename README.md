# mqttsimpleclient
Mqtt Client Test Demo Based on QtMqtt of Qt5.12.8

----------


> 系统 ubuntu 20.04
> 
> Qt5.12.8

## 测试demo配置 ##

> 添加模块
> 
> QT += mqtt

## qtmqtt源码下载及编译动态库 ##

> 源码下载GitHub地址

    https://github.com/qt/qtmqtt.git

> 将下载编译后得qmqtt以模块的形式部署到Qt的安装目录


## mqttsimpleclient 使用说明 ##

> 运行后，点击 Connect 连接服务器，日志输出窗口 State 为 2 表示已连接；
> 
> 点击 Subscribe 订阅按钮，再点击 Publish 发布按钮，即可收到信息