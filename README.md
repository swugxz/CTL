## 张佳，昊天要调研的事情：

1. 蓝牙ibeacon定位的具体实现方法

   （1）具体实现流程

   （2）确认定位过程中，锚点和待定位节点，哪个发ibeacon包，哪个收

   （3）ibeacon数据包里的rssi值（距离发送节点一米处的信号强度），是测出来的，还是理论上算得

2.  ble 的芯片能不能拿到bit流的信息，能做哪些修改

   （1）参考xbee文章，它里面应该是拿到了bit流的数据，看看是怎么做的



## 郭秀珍要做的事情

1. 跨协议定位ibeacon数据包的识别，什么时候触发定位
2. 物理层的模拟：技术选型，到底应该怎么做
3. 定位精度：考虑wifi的反射折射，精度如何 >＝蓝牙ibeacon