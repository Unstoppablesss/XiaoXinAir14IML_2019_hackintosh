# 联想小新 Air-14 2019IML
![air14iml-sur](img/air14iml-sur.png)
以上截图软件：https://github.com/lihaoyun6/capXDR-plugins/  
安装包在：app/capXDR.dmg  
模板：Lenovo-Air14IML (我做的)  
QQ群号：1032311345

中文  
[ENGLISH](./README-en.md)

|   规格    |                      详细信息                      |
| :-------: | :------------------------------------------------: |
| 电脑型号💻 |           Lenovo XiaoXin Air14 IML 2019            |
|    CPU    |        intel Core i5-10210U @ 1.60GHz 4core        |
|   主板    |                 lenovo LNVNB161216                 |
|   GPU👾    |           Nvidia GeForce MX250 ( 2 GB )            |
|   内存    |     板载4GB 2666+可更换内存(被我换成16GB 2666)     |
|   硬盘    |    512GB 2242 SATA固态 + HIKVISION c2000Pro 1TB    |
|  显示器🖥️  |             友达 AUO353D ( 14 英寸  )              |
|   声卡🔊   |                  Conexant CX8070                   |
|   网卡🌐   | intel Wireless-AC 9560(可驱动，但我换成了DW 1820A) |
|  读卡器🗂️  |     O2 Micro SD card reader(有概率读卡器不同)      |

## 目前状态：
* 系统🌌：10.15.7运行正常，Big Sur 11.2 Beta 2(20D5042d)运行正常(推荐macOS10.15.7。系统低于10.15.X触摸板跑不起来，系统低于10.15.4之前开机会卡顿)
* 硬盘：如果你硬盘是三星PM981A，建议换掉。或者按此方法安装系统 http://bbs.pcbeta.com/forum.php?mod=viewthread&tid=1867021
* 独立显卡👾：屏蔽了（反正驱动不了）
* 集成显卡👾：成功
* 触摸板🖐️：成功（支持手势，最多识别5点）
* 声卡🔊：仿冒layout-id 15成功，无爆音 [耳麦一体耳机需要这个](https://github.com/lietxia/XiaoXinAir14IML_2019_hackintosh/releases/tag/0.0.1)
* wifi🌐：DW1820A正常,AC 9560速度较慢，已驱动
* 蓝牙：DW1820A正常，AC 9560较不稳定
* HDMI：正常(可输出4k30帧,和win表现一致)
* 摄像头🎦：正常(USB摄像头还是很好驱动的)
* 读卡器🗂️：正常(联想居然弄了个走PCI通道的读卡器..有小概率型号不一样)
* 睡眠😴：支持原生休眠

## 相关机型
* [小新Pro13（i5-10210U / i7-10710U）](https://github.com/daliansky/XiaoXinPro-13-hackintosh)
* [小新13IML](https://github.com/sun19970908/XiaoXin13IML_2020_hackintosh)
* [小新air13IWL（i5-8265U / i7-8565U）](https://github.com/daliansky/Lenovo-Air13-IWL-Hackintosh)
* [小新air15IKBR（i5-8265U）](https://github.com/czy1024/XiaoXin-Air15-IKBR-2018-EFI)
* [小新air14（i5-1035G1）](http://bbs.pcbeta.com/viewthread-1873103-1-1.html)
* [小新air14（i7-1065G7）](http://bbs.pcbeta.com/viewthread-1878378-1-1.html)
* [小新air15（i5-1035G1）](http://bbs.pcbeta.com/viewthread-1874022-1-1.html)
* [小新air15（i5-10210U）](http://bbs.pcbeta.com/viewthread-1859586-1-1.html)
* [Lenovo-Ideapad-S540-15IML（i5-10210U）](https://github.com/3ig/IdeaPad-S540-15IML-hackintosh)
* [Lenovo-Ideapad-S540-15IML（i5-10210U）](https://github.com/ayush5harma/IdeaPad-S540-Hackintosh)
* [Lenovo-Ideapad-S540-15IWL（i5-8265U）](https://github.com/IvanAleksandrov94/Lenovo-s340-s540-Big-Sur-OpenCore-i5-8265u)
* [Lenovo-Ideapad-S540-14IML（i5-10210U）](https://github.com/marianopela/Lenovo-Ideapad-S540-14IML-Hackintosh)
* [Lenovo-Ideapad-S540-14IWL（i5-8265U）](https://github.com/Hasodikis/Lenovo-Ideapad-s540-14IWL---Hackintosh)

## BIOS 
https://newsupport.lenovo.com.cn/driveDownloads_detail.html?driveId=78312
<details>
<summary>展开查看</summary>
2021/01/18 BIOS Version: CKCN16WW http://newdriverdl.lenovo.com.cn/newlenovo/alldriversupload/78312/BIOS-CKCN16WW.exe <br />
2020/07/24 BIOS Version: CKCN15WW http://newdriverdl.lenovo.com.cn/newlenovo/alldriversupload/73409/BIOS-CKCN15WW.exe <br /> 
2020/06/22 BIOS Version: CKCN14WW http://newdriverdl.lenovo.com.cn/newlenovo/alldriversupload/72386/BIOS-CKCN14WW.exe <br />  
2019/12/16 BIOS Version: CKCN12WW http://newdriverdl.lenovo.com.cn/newlenovo/alldriversupload/67169/BIOS-CKCN12WW.exe <br />  
2019/08/08 BIOS Version: CKCN11WW http://newdriverdl.lenovo.com.cn/newlenovo/alldriversupload/60449/BIOS-CKCN11WW.exe <br />  
</details>

## 微码
https://newsupport.lenovo.com.cn/driveDownloads_detail.html?driveId=77695
<details>
<summary>展开查看</summary>
2020/12/17 Version: CKME03WW http://newdriverdl.lenovo.com.cn/newlenovo/alldriversupload/77695/FW-CKME03WW.exe <br /> 
2020/06/23 Version: CKME02WW http://newdriverdl.lenovo.com.cn/newlenovo/alldriversupload/72429/ME-CKME02WW.exe <br />
2019/12/16 Version: CKME01WW http://newdriverdl.lenovo.com.cn/newlenovo/alldriversupload/67174/FW-CKME01WW.exe <br /> 
</details>

## 不正常的：
* `指纹`无法驱动
* Nvidia MX250
* ~~耳麦一体的耳机🎧，麦克风🎤有问题~~ 2021-02-05:[可以驱动了](https://github.com/lietxia/XiaoXinAir14IML_2019_hackintosh/releases/tag/0.0.1)
* ~~无法禁音,但是可以把音量调最小就没声音了~~(已经解决)
* ~~开机会卡顿几秒~~(10.15.4解决)  
* ~~触摸板使用轮询方式,最多识别5指,但轮询并不是彻底完美,会有小瞬间丢状态~~ (新触摸板驱动大幅改善)

### YogaSMC `Experimental`
* 正常的：风扇三种模式切换、麦克风静音、飞行模式、F10切换屏幕、触摸板开关有提示、键盘背光、Fn功能键切换
* 不正常：摄像头有提示，但是关不掉、锁定功能用不了、Fn+Q不能修改、拔插电源会错误显示键盘背光、控制面板随机进不去、电池温度读不出来 

# 触摸板
如果触摸板(重建缓存触摸板仍不行，使用此方法)  
https://github.com/lietxia/XiaoXinAir14IML_2019_hackintosh/releases/tag/2020.04.05

## TIPS  
> 小新AIR14-2019 i5-10210u QQ群号1032311345  
> 如果你使用openCore，BIOS请使用1.0.2之外的版本
> （1.0.2需要关掉超线程才能使用oc，BIOS 1.0.1/1.0.4/1.0.5都没问题）

### macOS蓝牙与windows10同步
https://github.com/lietxia/BT-LinkkeySync

### Big Sur 开启hidpi（高分辨率）

    bash -c "$(curl -fsSL https://raw.githubusercontent.com/xzhih/one-key-hidpi/dev/hidpi.sh)"

### Catalina 开启hidpi（高分辨率）

    bash -c "$(curl -fsSL https://raw.githubusercontent.com/xzhih/one-key-hidpi/master/hidpi.sh)"
    
### DW1820A WINDOWS10驱动(DRIVER)
https://www.dell.com/support/home/zh-cn/drivers/driversdetails?driverid=98wfd

### 更新小记 (Changelog)
* 2021-02-10 12:00
    * 修复使用`YogaSMC`之后KP
    * 新增主题和开机音频

> 测试发现还是没声

* 2021-02-10 01:03
    * 添加`SSDT-NDGP_OFF-Air14IML.aml`用来屏蔽独立显卡
    * 触摸板`SSDT-TPAD-Air14IML.aml`改为GPIO中断模式，pin=`50`
    * 修正`SSDT-BATX-Air14IML.aml`，让其显示电池剩余可用时间
    * 更新`voodooi2c`到2.6.4
    * 删掉不再需要的`SSDT-XSPI.aml`,`SSDT-UIAC.aml`,`SMCSuperIO.kext`,`NoTouchID.kext`
    * 修正Clover不能引导BigSur的问题(需要选Preboot来引导bigSur)
    * 小幅改动`ALCPlugFix`的`install.command`和`uninstall.command`脚本

* 2021-02-05 08:20
    * 缩减itlwm和蓝牙固件，博通没有变化 

* 历史修改记录见[changelog.md](changelog.md)

## 安装方法
1. 如果你使用openCore，BIOS请使用1.0.2之外的版本 （1.0.2需要关掉超线程才能使用oc，BIOS 1.0.1/1.0.4/1.0.5都没问题）
2. 改BIOS设置（推荐和必须的地方必须改） https://github.com/lietxia/XiaoXinAir14IML_2019_hackintosh/wiki/bios
3. 完全按照 联想小新Pro13 的方法安装一次 
    * https://blog.daliansky.net/Lenovo-Xiaoxin-PRO-13-2019-and-macOS-Catalina-Installation-Tutorial.html
    * https://www.bilibili.com/video/BV1A54y1X78F
4. 改DVMT和 CFG Lock（见下文，必须做）
5. 安装成功后,把EFI换成这个 （可提前替换efi，安装过程一样）

## 建议
* 因目前休眠无法正常唤醒 , 为避免影响到睡眠 , 终端使用命令关闭休眠 `sudo pmset -a hibernatemode 0`

### 改DVMT和 CFG Lock
* 必须解锁 `CFG Lock` 不然无法使用opencore clover。 
* 建议解锁 `DVMT` 让显存大小变成64M，没有什么坏处。 

#### 推荐方法: 进隐藏BIOS  
BIOS里的 `onekeybattery` 需要关闭，才能进隐藏BIOS  
- 隐藏BIOS进入姿势
  - 电源键开机 → F2进入正常BIOS → 电源键关机 → 然后顺序按下下列键
    - `F4` → `4` → `R` → `F` → `V`
    - `F5` → `5` → `T` → `G` → `B`
    - `F6` → `6` → `Y` → `H` → `N`
  - 电源键开机 → F2进入隐藏BIOS , 如不成功请加快手速再次尝试
- 推荐设置选项
  - `Advanced` → `Power & Performance` → `CPU - Power Management Control` → `CPU Lock Configuration` → `CFG Lock` → `Disabled`
  - `Advanced` → `System Agent (SA) Configuration` → `Graphics Configuration` → `DVMT Pre-Allocated` → `64M`

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
AppleALC1.5.1没有这种问题了  
~~从win直接重启切换到mac,会导致声卡挂掉,这时候需要关机,再开机,声卡就恢复了~~  
~~咨询得到到回答:win的重启是热启动,会跳过硬件检测,直接win重启进黑苹果会出问题~~
* ~~建议: 从win切换到mac,不要用重启,先关机,再开机~~
* ~~mac重启mac,不会掉声卡~~

### 3. 进系统后黑屏了（01.06 EFI）
新版WhatEverGreen.kext的bug  
可通过重置nvram（如果改动efi后黑屏） , 退回WhatEverGreen.kext版本解决

## 如何更爽一点?
* 截图键(PrintScreen PrtSC)在mac下是不能用的,我把他映射到F13,自己把截图快捷键改到F13即可(系统偏好设置  键盘  快捷键  截屏)
* 开启hidpi 项目地址[这里](https://github.com/xzhih/one-key-hidpi) 使用方法:终端打命令 `bash -c "$(curl -fsSL https://raw.githubusercontent.com/xzhih/one-key-hidpi/master/hidpi.sh)"`


### 热补丁
| 补丁                    | 说明                            | 必备 | 建议 | 可选 |
| ----------------------- | ------------------------------- | ---- | ---- | ---- |
| ~~SSDT-OCPublic-Merge~~ | EC+RTC0+USBX+ALS0+MCHC          |      |      | √    |
| SSDT-SBUS-MCHC.aml      | SBUS + MCHC                     |      | √    |      |
| SSDT-EC-USBX.aml        | EC+USBX                         | √    |      |      |
| SSDT-TPAD-Air14IML      | I2C触摸板补丁(AIR14IML专用)     | √    |      |      |
| SSDT-DMAC               | 仿冒 DMA 控制器                 |      |      | √    |
| SSDT-GPRW               | 防秒醒:0D / 6D 睡了即醒补丁     | √    |      |      |
| SSDT-PMC                | PMC 设备                        |      | √    |      |
| SSDT-HPTE               | 屏蔽 HPET 补丁                  |      |      | √    |
| SSDT-PNLFCFL            | Coffee Lake 亮度控制补丁        | √    |      |      |
| SSDT-PR00               | (X86)CPU电源管理补丁(开启XCPM)  | √    |      |      |
| SSDT-RMCF-Air14IML      | PS2 按键映射补丁                | √    |      |      |
| ~~SSDT-UIAC~~           | 定制USB(不再需要)               |      | √    |      |
| ~~SSDT-XSPI~~           | 仿冒 XSPI 设备(不再推荐)        |      |      | √    |
| SSDT-BATX-Air14IML      | 电池附加信息                    |      |      | √    |
| SSDT-AWAC               | “伪” RTC时钟                    |      | √    |      |
| SSDT-ECRW               | yogaSMC的EC访问补丁             |      |      | √    |
| ~~SSDT-RCSM~~           | yogaSMC的Clamshell Mode所需补丁 |      |      | √    |

### KEXT
| KEXT                                | 说明                  | 必备 | 可选 |
| ----------------------------------- | --------------------- | ---- | ---- |
| AirportBrcmFixup.kext               | dw1820_Wifi           |      | √    |
| AppleALC.kext                       | HDMI以及声卡          | √    |      |
| BrcmBluetoothInjector.kext          | dw1820蓝牙            |      | √    |
| BrcmFirmwareData.kext               | dw1820蓝牙            |      | √    |
| BrcmPatchRAM3.kext                  | dw1820蓝牙>=10.15     |      | √    |
| ~~CPUFriend.kext~~                  | cpu变频               |      | √    |
| ~~CPUFriendDataProvider.kext~~      | cpu变频数据           |      | √    |
| ~~FakePCIID_Intel_HDMI_Audio.kext~~ | HDMI以及声卡          | √    |      |
| ~~FakePCIID.kext~~                  | HDMI以及声卡          | √    |      |
| Lilu.kext                           | 驱动扩展库(超重要)    | √    |      |
| ~~NoTouchID.kext~~                  | 取消指纹(不再需要)    |      | √    |
| SMCBatteryManager.kext              | SMC(超重要)           | √    |      |
| SMCProcessor.kext                   | SMC-处理器            | √    |      |
| ~~SMCSuperIO.kext~~                 | CPU-fan(无法读取)     |      | √    |
| VirtualSMC.kext                     | SMC(超重要)           | √    |      |
| VoodooI2C.kext                      | 触摸板-核心           | √    |      |
| VoodooI2CHID.kext                   | HID类型触摸板         | √    |      |
| VoodooPS2Controller.kext            | 键盘驱动              | √    |      |
| WhateverGreen.kext                  | 核显驱动              | √    |      |
| IntelBluetoothFirmware.kext         | AC9560蓝牙固件        |      | √    |
| IntelBluetoothInjector.kext         | AC9560蓝牙            |      | √    |
| AirportItlwm-Sur.kext               | AC9560 Wi-Fi Big Sur  |      | √    |
| AirportItlwm-Cata.kext              | AC9560 Wi-Fi Catalina |      | √    |
| YogaSMC.kext                        | YogaSMC               |      | √    |
| YogaSMCAlter.kext                   | YogaSMC               |      | √    |
| RestrictEvents.kext                 | 屏蔽一些系统加载项    |      | √    |
| NVMeFix.kext                        | 改善nvme固态          |      | √    |

## 鸣谢
- [Acidanthera](https://github.com/acidanthera) 开发的 [OpenCore](https://github.com/acidanthera/OpenCorePkg) 和 [其他驱动](https://github.com/acidanthera)
- [Apple](https://www.apple.com) 开发的 [macOS](https://www.apple.com/macos)
- [lietxia](https://github.com/lietxia) 维护EFI
- [zxystd](https://github.com/zxystd) 开发的 [itlwm](https://github.com/OpenIntelWireless/zxystd)
- [Bat.bat](https://github.com/williambj1) 开发的 [IntelBluetoothFirmware](https://github.com/OpenIntelWireless/IntelBluetoothFirmware) 和 [HeliPort](https://github.com/OpenIntelWireless/HeliPort)
- [alexandred](https://github.com/alexandred) 开发的 [VoodooI2C](https://github.com/VoodooI2C/VoodooI2C)
- [athlonreg](https://github.com/athlonreg/) 开发的 [ALCPlugFix](https://github.com/athlonreg/AppleALC-ALCPlugFix) 来修复耳麦一体耳机的问题
- [win1010525](https://github.com/win1010525) 翻译英文readme并制作AIO版本EFI
- [sun19970908](https://github.com/sun19970908) 提供ALC节点和修改ALCPlugFix
