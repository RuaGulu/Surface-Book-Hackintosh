# Surface Book Hackintosh
 Microsoft Surface Book 1 Hackintosh with macOS 11 supported, using OpenCore.

[![License](https://img.shields.io/badge/License-CC--BY--NC--ND-orange)](/LICENSE)

A Working OpenCore Setup for Microsoft Surface Book 1st Gen.

macOS Catalina & Big Sur Supported, tested up to macOS 11.4.

## Device Specification


    Model: 1st Gen. Microsoft Surface Book

    CPU: Intel Core i5-6300U @2.5 GHz

    GPU: Intel HD 520 Graphics

    Memory: 8GB 1866MHz LPDDR3

## Extra Info

- ***This Repo does not provide any help or support.***

- ***All content in this repository has been licensed under the CC-BY-NC-ND license, it is illegal to use the content in this repository for any commercial activities.***

- **SMBIOS info should be unique for your device, please change the required entries to your own before using this config.**
  
  ```diff
    <key>MLB</key>
  - <string></string>
    <key>ROM</key>
  - <data></data>
    <key>SpoofVendor</key>
  + <false/>
    <key>SystemProductName</key>
  + <string>MacBookPro13,1</string>
    <key>SystemSerialNumber</key>
  - <string></string>
    <key>SystemUUID</key>
  - <string></string>
  ```

- **There are possibilities to stuck during boot progress caused by keyboard & trackpad connection, please try to shut down your device completely and then reboot the device for a few times.
- **As the Wi-Fi Network Adapter is not working, I used a USB Wi-Fi Network Adapter which is working well.
- **Battery Percentage may not show or showing wrong data sometimes, use the battery shown in "iStats Menus" App may solve this issue.



## Features

| Supported | Features                                                                 |
| :-------: | :----------------------------------------------------------------------- |
|     ✔️     | Native Hardware NVRAM                                                    |
|     ✔️     | Intel HD 520 Graphics Card                                               |
|     ✔️     | 2 x USB 3.0 Ports</br>with Apple Device Charging                             |
|     ✔️     | Battery Percentage                                                       |
|     ✔️     | Sleep & Wake (Sometimes working)                                                |
|     ✔️     | Sensors                                                                  |
|     ✔️     | CPU Turbo Boost                                                  |
|     ✔️     | Trackpad</br>With Gestures                                                |
|     ✔️     | Built-in 3000*2000 Display</br>With Native HIDPI & APIC Interrupt |
|     ✔️     | Built-in Speakers                                       |
|     ✔️     | Surface Book Detach & Attach                          |
|     ✔️     | Internal Keyboard                                                  |
|     ✔️     | Screen Brightness Control                                             |
|     ❌     | Built-in Touchscreen                                                             |
|     ❌     | Built-in Microphone                                                             |
|     ❌     | 2 x Built-in Cameras & Face Recognition System                             |
|     ❌     | Marvell AVASTAR Wireless-AC Network Adapter</br>and Bluetooth      |
|     ❌     | Airdrop & Handoff                                                             |
|     ❌     | NVIDIA GeForce Discrete GPU                                                  |

## Special Thanks

- [Headkaze](https://github.com/headkaze) for the awesome [Hackintool](https://github.com/headkaze/Hackintool)

## Credits

- [Acidanthera](https://github.com/acidanthera)
  - [AppleALC](https://github.com/acidanthera/AppleALC)
  - [CpuTscSync](https://github.com/acidanthera/CpuTscSync)
  - [Lilu](https://github.com/acidanthera/Lilu)
  - [OpenCore](https://github.com/acidanthera/OpenCorePkg)
  - [VirtualSMC](https://github.com/acidanthera/VirtualSMC)
  - [WhateverGreen](https://github.com/acidanthera/WhateverGreen)
- [VoodooI2C Team](https://github.com/VoodooI2C)
  - [VoodooI2C](https://github.com/VoodooI2C/VoodooI2C)
  - [VoodooI2CHID](https://github.com/VoodooI2C/VoodooI2C)
