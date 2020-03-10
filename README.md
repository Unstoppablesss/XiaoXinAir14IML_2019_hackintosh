# 联想小新 Air-14 2019 (Intel平台：IML版)

|   规格   |                   详细信息                    |
| :------: | :-------------------------------------------: |
| 电脑型号 |             联想 81Q2 笔记本电脑              |
| 操作系统 |  Windows 10 Enterprise 64位 ( 4.09.00.0904 )  |
|  处理器  |     英特尔 Core i5-10210U @ 1.60GHz 四核      |
|   主板   |               联想 LNVNB161216                |
|   显卡   |         Nvidia GeForce MX250 ( 2 GB )         |
|   内存   |                12 GB ( 三星 )                 |
|  主硬盘  | 三星 MZVLB512HBJQ-000L2 ( 512 GB / 固态硬盘 ) |
|  显示器  |           友达 AUO353D ( 14 英寸  )           |
|   声卡   |                Conexant CX8070                |
|   网卡   |            英特尔 Wireless-AC 9462            |

#### 更新小记
可以在 [wiki](./wiki/) 看我都折腾日记


* 2020-03-10 14:00 修复了FN+F11 FN+F12调亮度的功能,更新了kext
* 2020-02-21 21:00 小更新，如果进不去系统，进备用efi引导，进去后打开命令行输入 `sudo nvram -c` 清除了nvram后这个efi能进去
* 2020-02-21 00:00 更新所有kext到最新
* 2020-02-24 14:00 大部分都正常了,加了openCore版

## 目前状态：
* 系统：10.15.3正式版
* 硬盘：三星PM981a有问题，已经换了一个sm960（加装硬盘也行的，只要不是pm981a）
* 独立显卡：屏蔽了（反正驱动不了）
* 集成显卡：成功驱动
* 触摸板：成功驱动（支持手势，最多识别5点）
* 声卡：仿冒layout-id 15成功，无爆音
* wifi：无解（准备换网卡）
* 蓝牙：不正常（反正换网卡一起换了）
* HDMI外接：正常
* 摄像头:正常
* 读卡器:正常
* 睡眠:正常

## 不正常的：
* ~~电脑休眠（反正我的不正常）~~
* ~~摄像头没有驱动~~
* ~~SD卡槽没有驱动~~ 已成功，见 [这里](https://github.com/lietxia/XiaoXinAir14IML_2019_hackintosh/wiki/%E8%AF%BB%E5%8D%A1%E5%99%A8)
* ~~HDMI外接：可选分辨率很有限，音量固定最大，而且不能调整~~(本来就不能调)




