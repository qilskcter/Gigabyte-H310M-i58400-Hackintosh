# <div align="center">Gigabyte H310M i5-8400 Hackintosh</div> 

## Intro

| | Version |
|-|---------|
| OpenCore | 0.9.3 Mod |
| macOS | Monterey 13.4.1 |


## Desktop Specification

|                     | Specifications| Note |
| ---------------------------- | ---------------------- |------------------|
| ``CPU``| Intel Core i5-8400 2.80GHz |  |
| ``Memory``| 16GB DDR4-2666MHz |  |
| ``iGPU``| Intel UHD Graphics 630 |  |
| ``Wifi and Bluetooth``| Intel® Dual Band Wireless-AX200 | Use [AirportItlwm](https://github.com/OpenIntelWireless/itlwm/releases) for Wifi and [IntelBluetoothFirmware](https://openintelwireless.github.io/IntelBluetoothFirmware/) for Bluetooth. |
| ``Ethernet``| RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | Use [RealtekRTL8111](https://github.com/Mieze/RTL8111_driver_for_OS_X/releases). |
| ``Audio``| Realtek ALC887 | Add `alcid=7` to boot-arg or add layout-id to DeviceProperties. |

## Features

| ``Features``|``Working``| 
|-------------|-----------|
| ``Audio``|✅|
| ``Wifi and Bluetooth``|✅|
| ``Keyboard``|✅|
| ``Headphone Jack``|✅|
| ``Graphics``|✅|
| ``Power Management``|✅|                                                                        
| ``USB Port``|✅|
| ``Facetime and iMessage``|✅|
| ``Ethernet``|✅|
| ``Sleep``|✅|
