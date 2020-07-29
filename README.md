# 联想小新 Air-14 2019 (Intel平台：IML版)

|   规格   |                  详细信息                  |
| :------: | :----------------------------------------: |
| 电脑型号 |            联想 81Q2 笔记本电脑            |
|  处理器  |    英特尔 Core i5-10210U @ 1.60GHz 四核    |
|   主板   |              联想 LNVNB161216              |
|   显卡   |       Nvidia GeForce MX250 ( 2 GB )        |
|   内存   |               12 GB ( 三星 )               |
|   硬盘   | 512GB 2242 SATA固态 + 原装三星PM981A 512GB |
|  显示器  |         友达 AUO353D ( 14 英寸  )          |
|   声卡   |              Conexant CX8070               |
|   网卡   |          英特尔 Wireless-AC 9462           |
|  读卡器  | O2 Micro SD card reader(有概率读卡器不同)  |

## 目前状态：
* 系统：10.15.4正式版(强烈推荐，10.15.X之前触摸板跑不起来，10.15.4之前开机会卡顿)
* 硬盘：三星PM981A目前苹果下有问题,但是还有个短的SSD位(规格是2242的)固态,顺便一提:这个机型2个SSD卡槽都可以装双面颗粒的SSD, 同时支持PCIE协议和SATA协议
* 独立显卡：屏蔽了（反正驱动不了）
* 集成显卡：成功驱动
* 触摸板：成功驱动（支持手势，最多识别5点）
* 声卡：仿冒layout-id 15成功，无爆音
* wifi：自带网卡无解,已换DW1820A(只要对黑苹果有了解,内置无线网卡99%要换) WIFI做更名已经可以和iPad随航
* 蓝牙：自带蓝牙可驱动,但已换为DW1820A(DW1820A是唯一价位低于100元,还是单面颗粒,同时带蓝牙的网卡,不过并不是免驱,但很好驱动起来)能用apple Watch解锁账户登陆。
* HDMI外接：正常(可输出4k30帧,和win表现一致)
* 摄像头:正常(USB摄像头还是很好驱动的)
* 读卡器:正常(联想居然弄了个走PCI通道的读卡器..有小概率型号不一样)
* 睡眠:支持原生休眠

## 不正常的：
* `指纹`无法驱动
* 耳麦一体的耳机🎧，麦克风🎤有问题
* ~~无法禁音,但是可以把音量调最小就没声音了~~(已经解决)
* ~~开机会卡顿几秒~~(10.15.4解决)  
* ~~触摸板使用轮询方式,最多识别5指,但轮询并不是彻底完美,会有小瞬间丢状态~~ (新触摸板驱动大幅改善)

# 触摸板
如果触摸板(重建缓存触摸板仍不行，使用此方法)  
https://github.com/lietxia/XiaoXinAir14IML_2019_hackintosh/releases/tag/2020.04.05

## TIPS  
> 小新AIR14-2019 i5-10210u QQ群号1032311345  
> 推荐系统为 macOS 10.15.3 因为10.14以及他之前的系统,触摸板无解  
> 姑且做了OC的版本,但不推荐(使用OC要关掉超线程,不然进不去)  
> 现阶段推荐使用CLOVER版,虽然吹OC的很多- -|||

#### 更新小记
* 2020-06-13 16:38 更新opencore成0.5.9官方正式版。更新clover到v5.0 r5119。更新kexts。
* 2020-05-06 21:36 SSDT-OCPublic-Merge.aml 合并 SSDT-EC.aml、SSDT-RTC0.aml、SSDT-USBX.aml、SSDT-ALS0.aml、SSDT-MCHC.aml 更新 kexts 更新opencore和clover，机型改为MacBook Air2020 ，删掉 CPUFriend.kext、CPUFriendDataProvider.kext
* 2020-04-11 08:39 修正了无法静音的bug，更新kext
* 更新clover到5019 更新了lilu等等kext……没看到什么可观的变化，可以无视这个更新
* 2020-03-26 11:05 更新触摸板驱动，多指更加灵敏，更新kext到最新版，OC换成魔改版，开机节目更加美观，clover升级到最最新版
* 2020-03-10 14:00 修复了FN+F11 FN+F12调亮度的功能,更新了kext
* 2020-02-21 21:00 小更新，如果进不去系统，进备用efi引导，进去后打开命令行输入 `sudo nvram -c` 清除了nvram后这个efi能进去
* 2020-02-21 00:00 更新所有kext到最新
* 2020-02-24 14:00 大部分都正常了,加了openCore版


## 安装方法
1. 完全按照 联想小新Pro13 的方法安装一次 https://blog.daliansky.net/Lenovo-Xiaoxin-PRO-13-2019-and-macOS-Catalina-Installation-Tutorial.html
2. 安装成功后,把EFI换成这个 

## 建议
* 因目前休眠无法正常唤醒 , 为避免影响到睡眠 , 终端使用命令关闭休眠 `sudo pmset -a hibernatemode 0`
* 强烈建议解锁 `CFG Lock` 开启电源管理更好
* 强烈建议解锁 `DVMT` 让显存大小变成64M

### 改DVMT和 CFG Lock
#### 推荐方法: 进隐藏BIOS  
参考 https://github.com/daliansky/Lenovo-Air13-IWL-Hackintosh/blob/master/Advanced/ReadMe.md  
文章让从F1开始，经过测试，从F4开始即可，正确顺序：
F4->4->R->F->V
F5->5->T->G->B
F6->6->Y->H->N
然后按F2进隐藏bios
评价:非常安全,群里好多人进去了,但我从来没进去过

#### 备用方法: windows直接改
参考 https://github.com/lietxia/XiaoXinAir14IML_2019_hackintosh/wiki/DVMT  
`DVMT`：  
* 区域（area） : `SaSetup`
* 偏移（offset） : `0x107`
* `01` to `02`

`CFG LOCK`：  
* 区域（area） : `CpuSetup`
* 偏移（offset） : `0x3E`
* `01` to `00`

## TIPS
### 1. 触摸板挂了
升级系统之类或其他触摸板挂掉的情况,  
需要重建缓存 , 使触摸板正常工作 , 终端执行以下命令之后重启

```
sudo mount -uw /
killall Finder
sudo kextcache -i /
```

### 2. 声卡挂了
从win直接重启切换到mac,会导致声卡挂掉,这时候需要关机,再开机,声卡就恢复了  
咨询得到到回答:win的重启是热启动,会跳过硬件检测,直接win重启进黑苹果会出问题
* 建议: 从win切换到mac,不要用重启,先关机,再开机
* mac重启mac,不会掉声卡


## 如何更爽一点?
* 截图键(PrintScreen PrtSC)在mac下是不能用的,我把他映射到F13,自己把截图快捷键改到F13即可(系统偏好设置  键盘  快捷键  截屏)
* 开启hidpi 项目地址[这里](https://github.com/xzhih/one-key-hidpi) 使用方法:终端打命令 `bash -c "$(curl -fsSL https://raw.githubusercontent.com/xzhih/one-key-hidpi/master/hidpi.sh)"`


### 热补丁
| 补丁          | 说明                           | 必备 | 建议 | 可选 |
| ------------- | ------------------------------ | ---- | ---- | ---- |
| AIR14-TPAD    | I2C 触摸板补丁                 | √    |      |      |
| SSDT-DMAC     | 仿冒 DMA 控制器                |      |      | √    |
| SSDT-EC       | 仿冒 EC 设备                   | √    |      |      |
| SSDT-GPRW     | 防秒醒:0D / 6D 睡了即醒补丁    | √    |      |      |
| SSDT-HPTE     | 屏蔽 HPET 补丁                 |      |      | √    |
| SSDT-MCHC     | 仿冒 MCHC 设备                 |      | √    |      |
| SSDT-PNLF-CFL | Coffee Lake 亮度控制补丁       | √    |      |      |
| SSDT-PR00     | (X86)CPU电源管理补丁(开启XCPM) | √    |      |      |
| SSDT-RMCF     | PS2 按键映射补丁               | √    |      |      |
| SSDT-SBUS     | 仿冒 BUS0 , DVL0 设备          |      | √    |      |
| SSDT-UIAC     | 定制USB                        |      | √    |      |
| SSDT-USBX     | USB 电源补丁                   | √    |      |      |
| SSDT-XSPI     | 仿冒 XSPI 设备                 |      |      | √    |

### KEXT
| KEXT                            | 说明               | 必备 | 可选 |
| ------------------------------- | ------------------ | ---- | ---- |
| AirportBrcmFixup.kext           | dw1820相关 wifi    |      | √    |
| AppleALC.kext                   | HDMI以及声卡       | √    |      |
| BrcmBluetoothInjector.kext      | dw1820相关 蓝牙    |      | √    |
| BrcmFirmwareData.kext           | dw1820相关         |      | √    |
| BrcmPatchRAM2.kext              | dw1820相关         |      | √    |
| CPUFriend.kext                  | cpu变频            | √    |      |
| CPUFriendDataProvider.kext      | cpu变频数据        | √    |      |
| FakePCIID_Intel_HDMI_Audio.kext | HDMI以及声卡       | √    |      |
| FakePCIID.kext                  | HDMI以及声卡       | √    |      |
| Lilu.kext                       | 驱动扩展库(超重要) | √    |      |
| NoTouchID.kext                  | 取消指纹           |      | √    |
| SMCBatteryManager.kext          | SMC(超重要)        | √    |      |
| SMCLightSensor.kext             | SMC(超重要)        | √    |      |
| SMCProcessor.kext               | SMC-处理器         | √    |      |
| SMCSuperIO.kext                 | SMC-超级读写       | √    |      |
| USBPorts.kext                   | 定制USB            | √    |      |
| VirtualSMC.kext                 | SMC(超重要)        | √    |      |
| VoodooI2C.kext                  | 触摸板-核心        | √    |      |
| VoodooI2CHID.kext               | HID类型触摸板      | √    |      |
| VoodooPS2Controller.kext        | 键盘驱动           | √    |      |
| WhateverGreen.kext              | 核显驱动           | √    |      |




