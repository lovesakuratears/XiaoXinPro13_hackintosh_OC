# XiaoXinPro13_hackintosh_OC
## Lenovo XiaoXin Pro13（S）i5-10210U/i7-10710U  [中文](README.md)

For 2019 Lenovo XiaoXin Pro13（S）Intel version (2020 version needs self-test)

## Preview
![System Preview 1](https://github.com/lovesakuratears/XiaoXinPro13_hackintosh_OC/assets/54654377/0fe3e92e-a536-4646-b4f8-8ab140ee867b)
![System Preview 2](https://github.com/user-attachments/assets/d4240751-30b0-4256-b07c-eb9732b4b726)
![System Preview 3](https://github.com/lovesakuratears/XiaoXinPro13_hackintosh_OC/assets/54654377/f8c4b04b-4e04-48bf-b82a-1b3555ca4fbb)
![System Preview 4](https://github.com/user-attachments/assets/bfc49ff2-0fae-445c-acd5-52c60755c7e5)

## Update Log
Updated irregularly. For detailed update records, please check: [Changelog](Changelog.md)

## System Requirements
- Lenovo XiaoXin Pro13（S）2019 Intel version (i5-10210U/i7-10710U)
- macOS already installed (recommend to follow [XiaoXinPro-13-hackintosh](https://github.com/daliansky/XiaoXinPro-13-hackintosh) for initial installation)
- Supported macOS versions: Only supports 14.4.1-15 (excluding 15), future compatibility with 15+ is uncertain

## Installation Steps
1. Download the EFI folder from this repository
2. Copy the EFI folder to the EFI partition of your hard drive

## Notes
1. Boot settings include countdown, please select boot item in time, can be modified according to needs
2. **Important**: Please update OpenCore to the latest version before updating the system
3. It is recommended to use stable version of macOS, do not blindly pursue the latest version
4. For systems below 12-15, you need to download the corresponding airportitlwm to replace kext, this project is compatible with 14.4-15 (excluding 15)

## Network Support
- **Original Intel NIC AX201**: Can be used directly
- **BCM94360Z4**: Due to Apple removing Broadcom drivers, OCLP patch is required, WiFi may fail to work directly, but Bluetooth works normally
- **Genuine Apple Wireless Card (macOS 14)**: Works perfectly

![Network Support](https://github.com/lovesakuratears/XiaoXinPro13_hackintosh_OC/assets/54654377/6e1dd8de-cce0-46b0-bde9-2b85904d731d)

## Bluetooth Support
- **Original Intel NIC AX201**: Can be used directly, USB port has been customized, AirDrop has been tested and works unidirectionally (Mac->iPhone)
  ![Bluetooth Support 1](https://github.com/user-attachments/assets/2b8685cd-8276-4593-952d-d48eaa9a20b6)
  ![Bluetooth Support 2](https://github.com/user-attachments/assets/b8dc1e87-0dfe-4e9c-a60e-75783071f79a)
- **BCM94360Z4**: Due to Apple removing Broadcom drivers, Bluetooth works normally
- **Genuine Apple Wireless Card (macOS 14)**: Works perfectly

## Function Expansion
- **Enable HIDPI**: Use [one-key-hidpi-dev](one-key-hidpi-dev) tool
- **OC Configuration Tool**: [OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools)
- **Screen Color Calibration**: [Lenovo Pro13 2019 Huaxing Screen Color Calibration.zip] (available for Huaxing screen)
- **Audio Test**: [Audio Test.mp3]
- **Verbose Mode**: Default is verbose mode, if you want to directly display the logo, delete the "-V" boot parameter in the position shown below
  ![Verbose Mode Settings](https://github.com/user-attachments/assets/0c6ba0a1-5d60-45b8-b3af-eb74394c772f)

## Reference Resources
- [XiaoXinPro-13-hackintosh](https://github.com/daliansky/XiaoXinPro-13-hackintosh)
- [OpenCore-Legacy-Patcher](https://github.com/dortania/OpenCore-Legacy-Patcher)
- [OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools)
- [itlwm](https://github.com/OpenIntelWireless/itlwm)