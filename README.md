# xiaoXinPro-i5-PM981
**PM981硬盘不能直接安装MAC需要选择克隆的方式**

这里只是小新PRO13硬盘为PM981的折中方案，为了更好的使用黑果，强烈建议更换其他型号硬盘。


使用方法
---
1. 安装mac系统到U盘/移动硬盘/其他型号的硬盘
2. 克隆安装好的MAC分区到PM981硬盘
3. 使用此处的clover建立引导，引导PM981里的MAC系统

注意事项
---
* 注意：第一次启动可能不成功，长按电源键重启多试几次（只有更改clover后才会出现此情况，正常使用不会）
* 这不是安装教程，只是PM981硬盘安装黑苹果的折中办法，详细安装教程请移步[小兵博客](https://blog.daliansky.net/Lenovo-Xiaoxin-PRO-13-2019-and-macOS-Catalina-Installation-Tutorial.html)
* `clover`不支持PM981升级MAC系统，想升级系统请在win下完整备份MAC系统后再尝试。
* 升级方法
  * 备份MAC系统
  * 切换到OC引导
  * OC引导下升级系统
  * 尝试升级
  * 升级不成功就直接切换到clover引导，不要重置`VRAM`


硬件型号
---

|硬件|型号|
| --- | --- |
|CPU|10210U|
|核显|uhd620|
|网卡|已经更换BCM94360CS2|
|声卡|alc257|
|显示器|华星|
|硬盘|PM981A|

功能情况
---
* CPU变频正常
* 核显驱动正常
* 触摸板驱动正常，支持手势
* 声卡内置MIC无法驱动，其余正常
* FN+F1-F9快捷键正常
* 无法完全睡眠，PM981硬盘正常盒盖不关wifi和蓝牙耗电大概`6%~7%/h`,关闭wifi和蓝牙`3%~4%`
* 打开QQ+Chrome看小时大概使用8小时左右

# 请详细阅读小兵大佬提供的[安装教程](https://blog.daliansky.net/Lenovo-Xiaoxin-PRO-13-2019-and-macOS-Catalina-Installation-Tutorial.html)，按照教程操作，不要错漏任何一步。

# 本人只是搬运工，感谢小兵大佬和宪武大佬以及众多群友的无私奉献，感谢群友`HellO`提供的PM981补丁，有什么疑难问题请到黑果群提问，此处不做解答。
