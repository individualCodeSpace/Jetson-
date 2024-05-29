# Jetson-
在Jetson TX2和Jetson orin nano  的开发过程中，遇到的不少网上都找不到的问题，记录一下
1.通过sdkmanager安装jetson cuda 组件，需要指定nvidia.com的DNS网址,并且通过网络安装，并且在主机使用ssh命令连接到jetson才能成功安装。命令为：ssh <jetsonname>@<同一子网下的ip>.
2.jetson 刷机后需要使用默认源更新apt依赖项。
3.jetson 先刷系统再安装组件。
4.换源更新apt需要去官网找ARM架构的链接。
