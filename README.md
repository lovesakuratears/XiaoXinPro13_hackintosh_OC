# XiaoXinPro13_hackintosh_OC
## Lenovo XiaoXin Pro13（S）i5-10210U/i7-10710U  [English](README_EN.md)

适用于 2019 款联想小新Pro13（S）Intel 版本（2020 款需自测）

## 预览
<img width="1417" alt="image" src="https://github.com/lovesakuratears/XiaoXinPro13_hackintosh_OC/assets/54654377/0fe3e92e-a536-4646-b4f8-8ab140ee867b">
<img width="939" alt="image" src="https://github.com/lovesakuratears/XiaoXinPro13_hackintosh_OC/assets/54654377/f8c4b04b-4e04-48bf-b82a-1b3555ca4fbb">

## 更新日志
随缘更新，详细更新记录请查看：[Changelog](Changelog.md)

## 系统要求
- 联想小新Pro13（S）2019款 Intel 版本（i5-10210U/i7-10710U）
- 已安装 macOS（建议先参考 [XiaoXinPro-13-hackintosh](https://github.com/daliansky/XiaoXinPro-13-hackintosh) 进行安装）
- 支持的 macOS 版本：macOS Ventura 及以上（升级到 macOS 14 需额外步骤）

## 安装步骤
1. 下载本仓库的 EFI 文件夹
2. 将 EFI 文件夹复制到硬盘的 EFI 分区


## 注意事项
1. 引导设置包含倒计时，请及时选择启动项，可根据需求自行修改
2. 已移除 -v 启动参数，直接显示 LOGO
3. **重要**：更新系统前请先更新 OpenCore 至最新版本
4. 建议使用稳定版本的 macOS，不要盲目追求最新版本

## 网络支持
- **原装 Intel 网卡 AX201**： 可直接使用
- ![1b76f95606c885f6ccbd08a606fe8c02](https://github.com/user-attachments/assets/f85256f8-d872-4dec-9278-b39c11bd525c)

- **BCM94360Z4**：由于 Apple 移除了 Broadcom 驱动，WiFi 可能失效，但蓝牙正常，后续懒得适配，需要双向airport考虑博通和白果
- **白果网卡（macOS 14）**：用就完了

<img width="720" alt="image" src="https://github.com/lovesakuratears/XiaoXinPro13_hackintosh_OC/assets/54654377/6e1dd8de-cce0-46b0-bde9-2b85904d731d">

## 功能拓展
- **开启 HIDPI**：使用 [one-key-hidpi-dev](one-key-hidpi-dev) 工具
- **OC 配置工具**：[OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools)
- **屏幕校色**：[Lenovo Pro13 2019华星屏幕校色.zip]（华星屏幕可用）
- **音频测试**：[Audio Test.mp3]

## 参考资源
- [XiaoXinPro-13-hackintosh](https://github.com/daliansky/XiaoXinPro-13-hackintosh)
- [OpenCore-Legacy-Patcher](https://github.com/dortania/OpenCore-Legacy-Patcher)
- [OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools)

