
本系列用于介绍组合仪表相关的知识，及其他ECU在组合仪表上的实现方式，一共分为以下几个部分：

* [组合仪表 - 标志（Symbols）的应用][Symbols]
* 组合仪表 - LCD中标志的显示方案
  * 实时性
  * 资源控制
  * 满足法规
* 组合仪表 - 如何描述标志相关的功能
  * 不同级别的功能如何描述：产品/系统级的功能规范，软件级的功能规范
  * 常用灯功能描述举例
    * 安全带，法规的定义
    * 转向灯，法规要求，闪烁的控制
  * 不同输入信号的灯
    * 数字量输入的灯
    * CAN报文输入的灯
    * 模拟量输入的灯，如何消抖（延时，回滞区）
  * 特殊状态的灯
    * IGN OFF需要工作的灯
    * 和车速相关的灯
* [组合仪表 - 车速表（Speedometer）的应用][Speedometer]
* 组合仪表 - 发动机转速表的应用
* 组合仪表 - 发动机水温表的应用
* 组合仪表 - 发动机油压表的应用
* 组合仪表 - 燃油液位表的应用
  * 传感器类型
  * 车速对速度的影响
  * 报警灯的逻辑
* 组合仪表 - 胎压监测系统的应用
* 组合仪表 - 自适应巡航系统的应用
* 组合仪表 - 自动紧急制动系统的应用
* 组合仪表 - 安全带报警



[Symbols]:https://github.com/JacobLeung0313/Automotive-Electronics/blob/master/Instrument-Cluster/Symbols.md

[Speedometer]:https://github.com/JacobLeung0313/Automotive-Electronics/blob/master/Instrument-Cluster/Speedometer.md