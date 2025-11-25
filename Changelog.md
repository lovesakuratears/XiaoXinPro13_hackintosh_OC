# XiaoXinPro13_hackintosh_OC
 
24.11.22 第一次更新
更新内容如下：
1.更新 oc 版本至目前最新 v1.0.2
2.更新所有 kext 包括 oclp 的 kext
3.支持最新的Sequoia 15.1.1(24B91) 正式版，注意更新oclp 保持最新
4.添加Intel 网卡蓝牙驱动如有需要自行启用 IntelBTPatcher.kext  IntelBluetoothFirmware.kext   AirportItlwm.kex（关闭IOSkywalkFamily.kext IO80211FamilyLegacy.kext IO80211FamilyLegacy.kext/Contents/PlugIns/AirPortBrcmNIC.kext AMFIPass.kext，未测试，理论上可正常使用）

25.11.22 第二次更新
更新内容如下：
1.更新 oc 版本至目前最新 v1.0.6
2.更新所有 kext 包括 oclp 的 kext
3.回退 14.4.1，（15太麻烦了驱动适配，未来再说）
4.添加Intel 网卡驱动AirportItlwm.kext，支持原装AX201
5.添加IntelBluetoothFirmware.kext，BlueToolFixup.kext 支持AX201 蓝牙
6.更新USBMap.kext，usb 映射，修复AX201蓝牙usb定制问题
遗留问题：IntelBTPatcher.kext官方要求Monterey and newer 版本，但是我测试发现14.4.1 不加载也可以正常使用，所以暂时保留

