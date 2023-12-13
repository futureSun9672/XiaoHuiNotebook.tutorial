## Modbus RTU要点
Modbus大致分为以下几种:
Modbus-RTU
Modbus-ASCII
Modbus-TCP
一般来说大部分的设备都是Modbus-RTU协议的，Modbus是主从方式通信，也就是说，不能同步进行通信，总线上每次只有一个数据进行传输，即主机发送，从机应答。

## 1、帧结构
帧结构 = 地址 + 功能码+ 数据 + 校验
Modbus-RTU协议一般我们用的最多功能码就是03和06 
例：
![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/50e0393237f84f15abc4a29d7235d4dd.png#pic_center)
![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/4bbe5f9bc2bb4a16958ceae5d9381f92.png#pic_center)
[其他功能码的使用：](https://blog.csdn.net/qq_21805743/article/details/120560226)
