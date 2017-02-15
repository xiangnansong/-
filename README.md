# README

这是一个简易的物联网系统。代码和平台分为三个部分：远程服务器端的转发程序，移动控制端的App，主控stm32+esp8266+传感器作为传感节点。移动端的代码在android文件夹中，stm32代码在mdk文件夹中，服务器端代码在web文件夹中。有两种情景:移动端上发送控制命令 -> 远程服务器 -> 节点，实现远程控制功能，例如对一个led灯的开关控制。节点发送传感信息 -> 远程服务器 ->移动端，实现远程信息监控，例如监控室内的温度。