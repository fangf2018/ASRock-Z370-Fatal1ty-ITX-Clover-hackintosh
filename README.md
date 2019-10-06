
# ASRock-Z370-Gaming-ITX-ac-hackintosh
###  2019-10-05
这个仓库以后就不再更新了 

转移到 

[z370核显OpenCore(macmini8,1)](https://github.com/fangf2018/ASRock-Z370-Fatal1ty-ITX-OpenCore-hackintosh) 

[z390独显OpenCore(imac19,1)](https://github.com/fangf2018/ASRock-Z390-Phantom-ITX-OpenCore-Hackintosh)

很乱很乱，期间有很多不懂的地方，
也给大家造成了很多的误导,在这里和大家说一声抱歉，也欢迎大家一起来交流 
OpenCore群538643249 z370/z390群838739020
这台机器因为折腾期间矿卡挂掉了，然后折腾的时候cpu也挂了，索性就升级了 9700k+z390，说实话z390真的很难折腾，黑苹果老老实实用z370主板真的非常省心


<img style="width:500px;" src="http://pylzvsh3j.bkt.clouddn.com/2019-09-30-QQ20190930-040354.png"/>

<img style="width:600px;" src="http://pylzvsh3j.bkt.clouddn.com/2019-09-30-z370.png" />


<img style="width:500px;" src="http://pylzvsh3j.bkt.clouddn.com/2019-09-30-QQ20190930-192427@2x.png"/>






###2019-10-3

* 增加一个4.10版本的bios 已更改为苹果启动logo 可直接刷入 参考[修改教程](https://www.bilibili.com/read/cv2788822/)

* 主logo

    ![2](http://github.fangf.cc/2019-10-03-2.jpg)
    
* 右下角文字

    ![IMG_8883](http://github.fangf.cc/2019-10-03-IMG_8883.JPG)

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
