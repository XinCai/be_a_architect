# Linux 学习笔记

#### 性能的指标 （了解这个概念）：

应用程序的角度：
吞吐，iops, input output operations per second 电脑存储设备性能测试的量测方式, 是每秒的读写次数。

延迟，lantency, 响应快

系统资源的角度：
资源使用率， 饱和度 等等
主要资源是：  CPU , 内存，网络， 磁盘IO 

性能问题的本质，就是系统资源达到瓶颈，请求处理不够快，无法支撑更多的请求

Application
    |
Libraries
    |
System Call
    |
Linux Kernel 
    | 
Device

从上倒下， 应用负载的角度； 从下往上， 资源视角
