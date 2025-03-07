# 联想小新 Air-14 2019IML
![air14iml-ven](img/air14iml-ven.png)
截图软件：/capXDR 
模板：Lenovo-Air14IML (我做的)  
QQ群号：1032311345

中文  
[ENGLISH](./README-en.md)

|   规格   | 状态  |                   详细信息                 |
| :-----: | ---- | :---------------------------------------: |
|  型号💻  | ✅    |      Lenovo XiaoXin Air14 IML 2019      |
|  系统🌌  | ✅    |   Catalina/Big Sur/Monterey/Ventura     |
|  CPU🎛️   | ✅    |    Intel Core i5-10210U / i7-10510U    |
|  主板🎛️  | ✅    |           Lenovo LNVNB161216            |
|  指纹🖐️  | ⛔    |               指纹无法工作                |
|  GPU👾   | ⛔    |       Nvidia GeForce MX250(屏蔽)        |
|  iGPU👾  | ✅    |              Intel UHD 620             |
|  内存💳  | ✅    |         内置4GB+可更换8GB DDR4 2666       |
|  硬盘💽  | ✅    |           见 Benchmarks/Disks           |
|  屏幕🖥️  | ✅    |   AUO353D/LGD05EC（14英寸） 1920x1080    |
|  声卡🔊  | ✅    |             Conexant CX8070             |
|  wifi🌐  | ✅    |     Intel Wireless-AC 9560/DW1820A     |
|  蓝牙🦷  | ✅    |            DW1820A正常，AC 9560          |
| 读卡器🗂️ | ✅    |   O2 Micro SD card reader（有可能不一样）  |
| 触摸板🖐️ | ✅    |          已运行在GPIO中断 Pin=50          |
|  HDMI📺  | ✅    |       可输出4k30帧,和win表现一致          |
| 摄像头🎦 | ✅    |           USB摄像头还是很好驱动的          |
|  睡眠😴  | ✅    |                支持原生休眠               |

## 目前状态：
* 系统🌌：Catalina/BigSur/Monterey/Ventura。推荐Catalina 10.15.7/BigSur 11.6.5/Monterey 12.7 （不推荐使用Ventura）
* 硬盘：如果你硬盘是三星PM981A，建议换掉。
* 声卡🔊：仿冒layout-id 15成功，无爆音 [耳麦一体耳机需要这个](https://github.com/lietxia/XiaoXinAir14IML_2019_hackintosh/releases/tag/0.0.1) 

## macOS12恢复台+EFI(u盘格式化FAT32，然后解压这个到根目录)
* 百度网盘（提取码: ggtj） https://pan.baidu.com/s/10RP9a_UNlNt1Y4ul_62Mpw?pwd=ggtj 
* 天翼网盘（访问码：0ufg）https://cloud.189.cn/web/share?code=QvayQb2UBbMv
* 123网盘 https://www.123pan.com/s/IvKKVv-jqeHh

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
2021/07/23 BIOS Version: CKEC17WW http://newdriverdl.lenovo.com.cn/newlenovo/alldriversupload/83713/BIOS-CKCN17WW.exe <br />
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
2021/07/23 Version: CKME05WW http://newdriverdl.lenovo.com.cn/newlenovo/alldriversupload/83714/FW-CKME05WW.exe <br />
2020/12/17 Version: CKME03WW http://newdriverdl.lenovo.com.cn/newlenovo/alldriversupload/77695/FW-CKME03WW.exe <br />
2020/06/23 Version: CKME02WW http://newdriverdl.lenovo.com.cn/newlenovo/alldriversupload/72429/ME-CKME02WW.exe <br />
2019/12/16 Version: CKME01WW http://newdriverdl.lenovo.com.cn/newlenovo/alldriversupload/67174/FW-CKME01WW.exe <br />
</details>

## 更新小记
* 2022-11-12 14:00
    * 新增`SSDT-PTSWAKTTS.aml`，以及选项`_PTS to ZPTS(1,N)`+`_WAK to ZWAK(1,S)`，取消WEG的`disable-external-gpu`屏蔽显卡方法。用于【修复睡眠唤醒】，详情 https://github.com/daliansky/OC-little/tree/master/20-SSDT%E5%B1%8F%E8%94%BD%E7%8B%AC%E6%98%BE%E6%96%B9%E6%B3%95
    * 更新opencore到0.8.6 
    * 更新 kext

* 2022-09-30 12:00
    * 修改`SSDT-UIAC.aml`防止windows下出现多余设备。

* 2022-09-27 12:00
    * Opencore 更新到 0.8.4 
    * 更新驱动
    * 添加启动参数 `agdpmod=vit9696` 解决hdmi输出
    * 更新测试版PS2键盘驱动，添加启动参数 `kbd_fixdisable=1` 解决macos12以上键盘失灵

* 历史修改记录见[changelog.md](changelog.md)

## [安装方法](https://www.bilibili.com/video/BV1C64y1q7r1/)
1. 如果你使用openCore，BIOS请使用1.0.2之外的版本 （1.0.2需要关掉超线程才能使用oc）
2. 改BIOS设置（推荐和必须的地方必须改） https://github.com/lietxia/XiaoXinAir14IML_2019_hackintosh/wiki/bios
3. 改DVMT和 CFG Lock（见下文，必须做）
4. 下载[balenaEtcher](https://www.balena.io/etcher/)，用它写入:[2022-06-19-XiaoXinAir14IML-4in1-installerV7.dmg](https://pan.baidu.com/s/1cYWvpfH9B0i6_Y0BnfAA0w?pwd=q27r)(提取码：q27r)
5. 引导写入的镜像的第二个EFI分区，选择需要安装的系统即可。

## 建议  
* 【防止黑苹果间歇性断网-解决方案 感谢@Unstoppablesss】修改 系统偏好设置/节能/电源适配器/如果可能，使硬盘进入睡眠（修改为off） 如果硬盘进入休眠，保持wifi运转的EFI文件将停止工作
* 因目前休眠无法正常唤醒 , 为避免影响到睡眠 , 终端使用命令关闭休眠 `sudo pmset -a hibernatemode 0`

> XiaoXin AIR14-2019 i5-10210u QQ群号: 1032311345

### YogaSMC `Experimental`
* 正常的：风扇三种模式切换、麦克风静音、飞行模式、F10切换屏幕、触摸板开关有提示、键盘背光、Fn功能键切换
* 不正常：摄像头有提示，但是关不掉、锁定功能用不了、Fn+Q不能修改、拔插电源会错误显示键盘背光、电池温度读不出来 

### 触摸板
如果触摸板(重建缓存触摸板仍不行，使用此方法)  
https://github.com/lietxia/XiaoXinAir14IML_2019_hackintosh/releases/tag/2020.04.05

### macOS蓝牙与windows10同步
https://github.com/lietxia/BT-LinkkeySync

### Big Sur 开启hidpi（高分辨率）

    bash -c "$(curl -fsSL https://raw.githubusercontent.com/xzhih/one-key-hidpi/dev/hidpi.sh)"

### Catalina 开启hidpi（高分辨率）

    bash -c "$(curl -fsSL https://raw.githubusercontent.com/xzhih/one-key-hidpi/master/hidpi.sh)"
    
### DW1820A WINDOWS10驱动(DRIVER)
https://www.dell.com/support/home/zh-cn/drivers/driversdetails?driverid=98wfd

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

### 声卡挂了 
从win直接重启切换到mac,会导致声卡挂掉,这时候需要关机,再开机,声卡就恢复了  
咨询得到到回答:win的重启是热启动,会跳过硬件检测,直接win重启进黑苹果会出问题  
* 建议: 从win切换到mac,不要用重启,先关机,再开机
* mac重启mac,不会掉声卡

## 如何更爽一点?
* 截图键(PrintScreen PrtSC)在mac下是不能用的,我把他映射到F13,自己把截图快捷键改到F13即可(系统偏好设置  键盘  快捷键  截屏)

## 热补丁
| 补丁               | 说明                           | 必备 | 建议 | 可选 |
| ------------------ | ------------------------------ | ---- | ---- | ---- |
| SSDT-SBUS-MCHC.aml | SBUS + MCHC                    |      | √    |      |
| SSDT-EC-USBX.aml   | EC+USBX                        | √    |      |      |
| SSDT-TPAD-Air14IML | I2C触摸板补丁(AIR14IML专用)      | √    |      |      |
| SSDT-DMAC          | 仿冒 DMA 控制器                  |      |      | √    |
| SSDT-GPRW          | 防秒醒:0D / 6D 睡了即醒补丁       | √    |      |      |
| SSDT-PMC           | PMC 设备                        |      | √    |      |
| SSDT-HPTE          | 屏蔽 HPET 补丁                  |      |      | √    |
| SSDT-PNLFCFL       | Coffee Lake 亮度控制补丁         | √    |      |      |
| SSDT-PR00          | (X86)CPU电源管理补丁(开启XCPM)    | √    |      |      |
| SSDT-RMCF-Air14IML | PS2 按键映射补丁                 | √    |      |      |
| SSDT-UIAC          | 定制USB                         |      | √    |      |
| SSDT-BATX-Air14IML | 电池附加信息                     |      |      | √    |
| SSDT-AWAC          | “伪” RTC时钟                    |      | √    |      |
| SSDT-ECRW          | yogaSMC的EC访问补丁              |      |      | √    |

## KEXT
| KEXT                        | 说明                  | 必备 | 可选 |
| --------------------------- | --------------------- | ---- | ---- |
| AirportBrcmFixup.kext       | dw1820_Wifi           |      | √    |
| AppleALC.kext               | HDMI以及声卡           | √    |      |
| BluetoolFixup.kext          | 修复Monterey 蓝牙       |     | √    |
| BrcmBluetoothInjector.kext  | dw1820蓝牙            |      | √    |
| BrcmFirmwareData.kext       | dw1820蓝牙            |      | √    |
| BrcmPatchRAM3.kext          | dw1820蓝牙>=10.15     |      | √    |
| Lilu.kext                   | 驱动扩展库(超重要)      | √    |      |
| SMCBatteryManager.kext      | SMC(超重要)           | √    |      |
| SMCProcessor.kext           | SMC-处理器            | √    |      |
| VirtualSMC.kext             | SMC(超重要)           | √    |      |
| VoodooI2C.kext              | 触摸板-核心            | √    |      |
| VoodooI2CHID.kext           | HID类型触摸板          | √    |      |
| VoodooPS2Controller.kext    | 键盘驱动               | √    |      |
| WhateverGreen.kext          | 核显驱动               | √    |      |
| DebugEnhancer.kext          | 修复msgbuf卡EB         |      | √    |
| IntelBluetoothFirmware.kext | AC9560蓝牙固件         |      | √    |
| IntelBluetoothInjector.kext | AC9560蓝牙             |      | √    |
| AirportItlwm-Sur.kext       | AC9560 Wi-Fi Big Sur  |      | √    |
| AirportItlwm-Cata.kext      | AC9560 Wi-Fi Catalina |      | √    |
| AirportItlwm-Monterey.kext  | AC9560 Wi-Fi Monterey |      | √    |
| YogaSMC.kext                | YogaSMC               |      | √    |
| YogaSMCAlter.kext           | YogaSMC               |      | √    |
| RestrictEvents.kext         | 屏蔽一些系统加载项       |      | √    |
| NVMeFix.kext                | 改善nvme固态           |      | √    |
| VerbStub.kext               | 耳麦切换               |      | √    |

## 备注
* 拆机需要6号的6角螺丝。螺丝拿下来之后，用不用的银行卡，慢慢从屏幕那一侧慢慢拆开 https://www.bilibili.com/video/BV1X341157kf/  
* 如果要买【圆口转USB type转接器】，注意【圆口直径4毫米，孔直径1.7毫米】  
![IMG](img/pd+luosi.png)

## 鸣谢
- [Acidanthera](https://github.com/acidanthera) 开发的 [OpenCore](https://github.com/acidanthera/OpenCorePkg) 和 [其他驱动](https://github.com/acidanthera)
- [Apple](https://www.apple.com) 开发的 [macOS](https://www.apple.com/macos)
- [lietxia](https://github.com/lietxia) 维护EFI
- [zxystd](https://github.com/zxystd) 开发的 [itlwm](https://github.com/OpenIntelWireless/itlwm)
- [Bat.bat](https://github.com/williambj1) 开发的 [IntelBluetoothFirmware](https://github.com/OpenIntelWireless/IntelBluetoothFirmware) 和 [HeliPort](https://github.com/OpenIntelWireless/HeliPort)
- [alexandred](https://github.com/alexandred) 开发的 [VoodooI2C](https://github.com/VoodooI2C/VoodooI2C)
- [athlonreg](https://github.com/athlonreg/) 开发的 [ALCPlugFix](https://github.com/athlonreg/AppleALC-ALCPlugFix) 来修复耳麦一体耳机的问题
- [win1010525](https://github.com/win1010525) 翻译英文readme并制作AIO版本EFI
- [sun19970908](https://github.com/sun19970908) 提供ALC节点，修改ALCPlugFix并测试CPUFriend
- [stevezhengshiqi](https://github.com/stevezhengshiqi) 开发的 [one-key-cpufriend](https://github.com/stevezhengshiqi/one-key-cpufriend)
- [SoMeone](https://user.qzone.qq.com/504674749/infocenter) 破解的隐藏 BIOS
