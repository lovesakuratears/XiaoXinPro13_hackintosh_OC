# XiaoXinPro13_hackintosh_OC
## Lenovo XiaoXin Pro13（S）i5-10210U/i7-10710U  [English](README_EN.md)

适用于 2019 款联想小新Pro13（S）Intel 版本（2020 款需自测）

## 预览
<img width="1417" alt="image" src="https://github.com/lovesakuratears/XiaoXinPro13_hackintosh_OC/assets/54654377/0fe3e92e-a536-4646-b4f8-8ab140ee867b">
<img width="560" height="1058" src="https://github.com/user-attachments/assets/d4240751-30b0-4256-b07c-eb9732b4b726" />
<img width="939" alt="image" src="https://github.com/lovesakuratears/XiaoXinPro13_hackintosh_OC/assets/54654377/f8c4b04b-4e04-48bf-b82a-1b3555ca4fbb">
<img width="310" height="310" src="https://github.com/user-attachments/assets/bfc49ff2-0fae-445c-acd5-52c60755c7e5" />


## 更新日志
随缘更新，详细更新记录请查看：[Changelog](Changelog.md)

## 系统要求
- 联想小新Pro13（S）2019款 Intel 版本（i5-10210U/i7-10710U）
- 已安装 macOS（建议先参考 [XiaoXinPro-13-hackintosh](https://github.com/daliansky/XiaoXinPro-13-hackintosh) 进行安装）
- 支持的 macOS 版本：只支持14.4.1-15以下（不包含15），未来不确定适配15以上,

## 安装步骤
1. 下载本仓库的 EFI 文件夹
2. 将 EFI 文件夹复制到硬盘的 EFI 分区


## 注意事项
1. 引导设置包含倒计时，请及时选择启动项，可根据需求自行修改
2.  **重要**：更新系统前请先更新 OpenCore 至最新版本
3.建议使用稳定版本的 macOS，不要盲目追求最新版本
4. 12-15以下的系统需要，需要自行下载对应的airportitlwm替换kext，本项目适配14.4-15（不含15）

## 网络支持
- **原装 Intel 网卡 AX201**： 可直接使用
- ![1b76f95606c885f6ccbd08a606fe8c02](https://github.com/user-attachments/assets/f85256f8-d872-4dec-9278-b39c11bd525c)

- **BCM94360Z4**：由于 Apple 移除了 Broadcom 驱动，需要OCLP补丁，直接用WiFi 可能失效，但蓝牙正常，后续懒得适配，需要双向airport考虑博通和白果
- **白果网卡（macOS 14）**：用就完了

<img width="720" alt="image" src="https://github.com/lovesakuratears/XiaoXinPro13_hackintosh_OC/assets/54654377/6e1dd8de-cce0-46b0-bde9-2b85904d731d">

## 蓝牙适配
- **原装 Intel 网卡 AX201**： 可直接使用，已经usb定制，理论ax201可直接使用，隔空传送已经测试，单向可用（Mac->iPhone）
  <img width="638" height="336" alt="微信图片_20251125152643_4_152" src="https://github.com/user-attachments/assets/2b8685cd-8276-4593-952d-d48eaa9a20b6" />
<img width="398" height="212" alt="微信图片_20251125154347_7_152" src="https://github.com/user-attachments/assets/b8dc1e87-0dfe-4e9c-a60e-75783071f79a" />
- **BCM94360Z4**：由于 Apple 移除了 Broadcom 驱动，但蓝牙正常，后续懒得适配，需要双向airport考虑博通和白果
- **白果网卡（macOS 14）**：用就完了
## 功能拓展
- **开启 HIDPI**：使用 [one-key-hidpi-dev](one-key-hidpi-dev) 工具
- **OC 配置工具**：[OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools)
- **屏幕校色**：[Lenovo Pro13 2019华星屏幕校色.zip]（华星屏幕可用）
- **音频测试**：[Audio Test.mp3]
- **跑马模式**：默认跑马模式，如确认可以正常使用，需要直接出logo则在下图位置删除“-V”启动参数保存即可
  <img width="2226" height="1169" alt="微信图片_20251125155000_8_152" src="https://github.com/user-attachments/assets/0c6ba0a1-5d60-45b8-b3af-eb74394c772f" />


## 参考资源
- [XiaoXinPro-13-hackintosh](https://github.com/daliansky/XiaoXinPro-13-hackintosh)
- [OpenCore-Legacy-Patcher](https://github.com/dortania/OpenCore-Legacy-Patcher)
- [OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools)
- [itlwm](https://github.com/OpenIntelWireless/itlwm)

