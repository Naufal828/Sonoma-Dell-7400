![macOS version](https://img.shields.io/static/v1?label=MacOS-Sonoma&message=14.8.2&color=green)
![OpenCore version](https://img.shields.io/badge/OpenCore-1.0.7-informational.svg)


<img src="https://cdn.jim-nielsen.com/macos/512/macos-sonoma-2023-09-26.png?rf=1024" width="150"/>


# Dell 7400 Hackintosh
| Geekbench 5 Score                 |            Comment                |
|----------------------|-----------------------------------|
| [Geekbench 5](https://browser.geekbench.com/v5/cpu/23905147) | Single Channel|
|  coming soon when RAM prices return to normal :b | Dual Channel|

# Read For Setting your smbios
- [Platfrom Info ](https://dortania.github.io/OpenCore-Install-Guide/config.plist/haswell.html#platforminfo)
- [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)

## Supported SMBIOS
| Type                 |            Comment                |
|----------------------|-----------------------------------|
| MacBookPro15,2       | Quad Core 15W                     |

## Bios Settings
| Settins              |            Comment                |
|----------------------|-----------------------------------|
| Bios Mode            | UEFI                              |
| Secure Boot          | Disable                           |
| FastBoot             | Minimal                           |
| SATA Mode            | AHCI                              |
| Intel SGX            | Software Controled                |

## Hardware

| Type                 | Name                              |
|----------------------|-----------------------------------|
| CPU                  | [Intel® Core™ i5-8365u](https://www.intel.com/content/www/us/en/products/sku/193555/intel-core-i58365u-processor-6m-cache-up-to-4-10-ghz/specifications.html)             |
| Audio                | [Realtek® Audio Codec ALC295](https://github.com/acidanthera/applealc/wiki/supported-codecs)       |
| IGPU                 | Intel® UHD Graphics 620        |
| RAM                  | 8GB DDR4 2400Mhz                 |
| Trackpad             | I2C HID |
| Keyboard             | PS2|
| Wi-Fi Bluetooth      | Intel AC 9560                          |
| Storage              | TOSHIBA KXG60ZNV256G   |

## resources
- https://github.com/acidanthera/OpenCorePkg
- https://github.com/headkaze/Hackintool
- https://mackie100projects.altervista.org/opencore-configurator/
- https://github.com/corpnewt/ProperTree
- https://github.com/0xCUB3/About-This-Hack

## Functional

-  QE/CI of Intel UHD 620
-  Restart, Sleep and Shutdown
-  -  Hibernate, with hibernate mode 03, default pmset, entering hibernate mode battery under 50%
-  CPU Power Management, with voltageshift undervolt cpu offset and cpu cache voltage -100mv, PL1 20, PL 25
-  HDMI Out
-  All Port USB, 2x USB 3.0, 2x USB 2.0, Type C Running USB 2.0 & 3.0
-  Wifi
-  Bluetooth
-  Touchpad with gesture
-  Touchscreen
-  Keyboard
-  audio jack 3.5mm, fix with alcplug
-  Web Camera


## Doesn't Work
- airdrop
- screen mirroring from iphone
- drm safari
- find my devices

## Untested
- AirDrop not tested on Intel AC 9560
- thunderbolt untested
- imessages, dont have iphone
  
## Contact
 - [Contact](https://t.me/naufaliosk)

## Support Me
 - [For Buy a coffee](https://saweria.co/Naufaal)

## Special Thanks to
- [God](https://id.wikipedia.org/wiki/Tuhan)
- [Apple](https://www.apple.com) For MacOS
- [Acidantera](https://github.com/acidanthera) The maker of OpenCore
- [Dortania People](https://github.com/orgs/dortania/people) for the OpenCore Install Guide
- 

## Screenshot
<img src="https://github.com/Naufal828/Sonoma-Dell-7400/blob/main/Resource/Screenshot%202025-11-18%20at%2014.10.16.png" width="500"/>
<img src="https://github.com/Naufal828/Sonoma-Dell-7400/blob/main/Resource/Screenshot%202025-11-18%20at%2014.17.57.png" width="500"/>
<img src="https://github.com/Naufal828/Sonoma-Dell-7400/blob/main/Resource/Screenshot%202025-11-18%20at%2022.31.47.png" width="1000"/>
<img src="https://github.com/Naufal828/Sonoma-Dell-7400/blob/main/Resource/Screenshot%202025-11-18%20at%2022.31.53.png" width="1000"/>
<img src="https://github.com/Naufal828/Sonoma-Dell-7400/blob/main/Resource/Screenshot%202025-11-18%20at%2022.32.58.png" width="1000"/>
<img src="https://github.com/Naufal828/Sonoma-Dell-7400/blob/main/Resource/Screenshot%202025-11-18%20at%2022.33.19.png" width="1000"/>








