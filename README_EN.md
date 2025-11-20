# XiaoXinPro13_hackintosh_OC
## Lenovo XiaoXin Pro13（S）i5-10210U/i7-10710U  

For 2019 Lenovo XiaoXin Pro13（S）Intel version (2020 version needs self-test) [中文](README.md)

## Preview
<img width="1417" alt="image" src="https://github.com/lovesakuratears/XiaoXinPro13_hackintosh_OC/assets/54654377/0fe3e92e-a536-4646-b4f8-8ab140ee867b">
<img width="939" alt="image" src="https://github.com/lovesakuratears/XiaoXinPro13_hackintosh_OC/assets/54654377/f8c4b04b-4e04-48bf-b82a-1b3555ca4fbb">

## Update Log
Updated irregularly. For detailed update records, please check: [Changelog](Changelog.md)

## System Requirements
- Lenovo XiaoXin Pro13（S）2019 Intel version (i5-10210U/i7-10710U)
- macOS already installed (recommend to follow [XiaoXinPro-13-hackintosh](https://github.com/daliansky/XiaoXinPro-13-hackintosh) for initial installation)
- Supported macOS versions: macOS Ventura and above

## Installation Steps
1. Download the EFI folder from this repository
2. Copy the EFI folder to the EFI partition of your hard drive
   
## Notes
1. Boot settings include countdown, please select boot item in time, can be modified according to needs
2. -v boot parameter has been removed, directly display LOGO
3. **Important**: Please update OpenCore to the latest version before updating the system
4. It is recommended to use stable version of macOS, do not blindly pursue the latest version

## Network Support
- **Original Intel NIC AX201**: Supported
- **Apple Wireless Card**: BCM94360Z4 can be used directly
- **Apple Wireless Card (macOS 14)**: Due to Apple removing Broadcom drivers, WiFi may fail, but Bluetooth works normally

<img width="720" alt="image" src="https://github.com/lovesakuratears/XiaoXinPro13_hackintosh_OC/assets/54654377/6e1dd8de-cce0-46b0-bde9-2b85904d731d">

## Function Expansion
- **Enable HIDPI**: Use [one-key-hidpi-dev](one-key-hidpi-dev) tool
- **OC Configuration Tool**: [OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools)
- **Screen Color Calibration**: [Lenovo Pro13 2019 Huaxing Screen Color Calibration.zip] (available for Huaxing screen)
- **Audio Test**: [Audio Test.mp3]

## Reference Resources
- [XiaoXinPro-13-hackintosh](https://github.com/daliansky/XiaoXinPro-13-hackintosh)
- [OpenCore-Legacy-Patcher](https://github.com/dortania/OpenCore-Legacy-Patcher)
- [OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools)

