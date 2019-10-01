
# ASRock-Z370-Gaming-ITX-ac-hackintosh

<img style="width:500px;" src="http://pylzvsh3j.bkt.clouddn.com/2019-09-30-QQ20190930-040354.png"/>

<img style="width:600px;" src="http://pylzvsh3j.bkt.clouddn.com/2019-09-30-z370.png" />


<img style="width:500px;" src="http://pylzvsh3j.bkt.clouddn.com/2019-09-30-QQ20190930-192427@2x.png"/>





## 更新记录

###  2019-09-30
* 不再更新clover，全面转移到OpenCore，仅核显配置19,2

###  2019-09-21
* 系统升级10.15B8 19A558d
* clover升级5070，其他驱动升级
* fakesmc更换为VirtualSMC
* 删减主题文件
* 删减drivers64UEFI文件
* 加入GPRW防止usb设备唤醒，仅电源键唤醒（家里养猫）

###  2019-09-04
* 配置同步到当日最新

###  2019-05-30
* 增加一套无独显配置，机型imac18，1

###  2019-05-21
* 机型更换到更新imac pro1,1 bios需关闭核显

> Advanced \ Chipset Configuration → Share Memory : Auto
> 
> Advanced \ Chipset Configuration → IGPU Multi-Monitor : Disabled
> 

* fakesmc更换成VirtualSMC
* 常规升级 10.14.6 Beta 18G29g
* cpu变频优化 
> 6个档位 800 2400 2800 3700 3800 4200

#### 关于机型最近折腾了很多，为什么选择了imac pro1,1 并屏蔽核显，基于一下几点

> 1、uhd630这个显卡比较尴尬的是fcpx在渲染输出的时候参与加速并不明显、4k视频转场特效卡顿
> 
> 2、10.14.5版本系统后独显也可以单独硬解4k视频了，核显的意义不大了
> 
> 3、uhd630存在的意义不像是4代核心的显卡（hd4600等）可以完美fcpx
> 
> 4、与其增加功耗，不如关闭核显，有效控制cpu温度
> 

###  2019-05-07
* 系统升级到 10.14.5（18F127a）
* Clover 升级到 Clover_v2.4k_r4928

###  2019-04-12
* 系统升级到 10.14.5（18F108f）beta2
* 驱动更新到最新版本
* 机型更换到 19，1

### 2019-04-08
* 升级clover版本 4919
* 更换机型19，2

### 2019-03-29 
* 增加两个ssdt解决雷电热插拔 去除已失效驱动IOElectrify.kext
* 系统升级10.14.5 Beta1 (18F96h)无异常
* CLOVER 升级到 r4910
* 增加一个主题，系统等待时间改为1秒

### 2019-03-26 
* 首次上传 系统版本 10.14.4正式版 CLOVER r4903

## 配置

主板：华擎z370 Gaming-ITX-ac

cpu：8700k es qn8g

显卡：amd 蓝宝石 rx570

网卡：BCM943602CS

其他配置信息 [点我查看](https://github.com/fangf2018/ASRock-Z370-Gaming-ITX-ac-hackintosh/issues/1#issuecomment-489914538)

## BIOS设置

Advanced \ Chipset Configuration → Vt-d : Disabled

Advanced \ Super IO Configuration → Serial Port: Disabled

Advanced \ USB Configuration → XHCI Hand-off : Enabled

Advanced \ Chipset Configuration → Share Memory : 128MB

Advanced \ Chipset Configuration → IGPU Multi-Monitor : Enabled


# 参考
[精解OpenCore](https://blog.daliansky.net/OpenCore-BootLoader.html)

[macOS Catalina 10.15安装中常见的问题及解决方法](https://blog.daliansky.net/Common-problems-and-solutions-in-macOS-Catalina-10.15-installation.html)

[使用HIDPI解决睡眠唤醒黑屏、花屏及连接外部显示器的正确姿势](https://blog.daliansky.net/Use-HIDPI-to-solve-sleep-wake-up-black-screen,-Huaping-and-connect-the-external-monitor-the-correct-posture.html)

[OpenCore部件补丁](https://github.com/daliansky/OC-little)


# 感谢
**[daliansky](https://github.com/daliansky)（黑果小兵）**

**[RehabMan](https://bitbucket.org/RehabMan/)**

**[ZeRo° Xu](https://github.com/xzhih)(冰水加劲Q)**

**[acidanthera](https://github.com/acidanthera/OpenCorePkg)**

**[Bat.bat](https://github.com/williambj1)**
