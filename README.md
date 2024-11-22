# XiaoXinPro13_hackintosh_OC
## Lenovo XiaoXin Pro13（S）i5-10210U/i7-10710U  [英文](README_EN.md)
## 适用于 2019 款的联想小新Pro13（S）Intel 版本（2020 款自测）

<img width="1417" alt="image" src="https://github.com/lovesakuratears/XiaoXinPro13_hackintosh_OC/assets/54654377/0fe3e92e-a536-4646-b4f8-8ab140ee867b">
<img width="939" alt="image" src="https://github.com/lovesakuratears/XiaoXinPro13_hackintosh_OC/assets/54654377/f8c4b04b-4e04-48bf-b82a-1b3555ca4fbb">

## 更新
！！！随缘更新
[Changelog](Changelog.md)

 ## 操作
 ！！！需先根据[XiaoXinPro-13-hackintosh](https://github.com/daliansky/XiaoXinPro-13-hackintosh)安装 Macos 后才可使用本库
### 1.下载 EFI 文件夹，复制到硬盘的 EFI 分区
### 2.安装 OLP后执行（升级到 macOS14+需要下载）[OpenCore-Legacy-Patcher](https://github.com/dortania/OpenCore-Legacy-Patcher)
Post-Install Root Patch -->Start RootPatching-->输入root 密码-->reboot
<img width="636" alt="image" src="https://github.com/lovesakuratears/XiaoXinPro13_hackintosh_OC/assets/54654377/9928e111-55e5-4b47-8cf3-0cc1e13ab308">
   
## 注意
已去掉-v，直接出 LOGO，引导设置倒计时注意及时选择，有需求自行更改。

( Intel网卡 / BCM94360Z4 / 白果拆机网卡 )

-----白果卡/BCM94360Z4可直接使用本项目，这两种卡原先免驱，但 14去掉博通驱动，wi-fi 免驱失效，蓝牙正常，usb 网卡也无效

-----其他网卡如[原装网卡AX201] 参考[此教程](https://github.com/daliansky/XiaoMi-Pro-Hackintosh/wiki/驱动内置英特尔无线网卡)添加 i 卡驱动以支持
24.11.22 更：添加Intel 网卡蓝牙驱动如有需要自行启用 

enbale ：IntelBTPatcher.kext  IntelBluetoothFirmware.kext   AirportItlwm.kex

false：IOSkywalkFamily.kext IO80211FamilyLegacy.kext IO80211FamilyLegacy.kext/Contents/PlugIns/AirPortBrcmNIC.kext AMFIPass.kext
！！！未测试，理论上可正常使用！！！

！！！更新系统前请先更新 OC 至最新版本，另不知未来黑果环境如何最好不要最求最新版本（稳定第一位）！！！

   <img width="720" alt="image" src="https://github.com/lovesakuratears/XiaoXinPro13_hackintosh_OC/assets/54654377/6e1dd8de-cce0-46b0-bde9-2b85904d731d">
## 拓展
可以开启 [HIDPI](one-key-hidpi-dev)

OC配置工具[OCAT](https://github.com/ic005k/OCAuxiliaryTools)

校色文件（华星屏幕可用）[Lenovo Pro13 2019华星屏幕校色.zip]

音频测试[Audio Test.mp3]

更多可以查看 [XiaoXinPro-13-hackintosh](https://github.com/daliansky/XiaoXinPro-13-hackintosh)

