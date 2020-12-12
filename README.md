# B460M-MORTAR-Comet-Lake-IGPU-AGPU
This EFI can support Comet Lake's single-core graphics card output (HDMI + DP), and also supports 5500-5700 graphics cards and NVIDIA graphics card output that is drive-free in macOS Catalina

This EFI can support Comet Lake's coreless graphics card to use Nvidia or AMD graphics card output

### EFI

OpenCore: 0.6.4

Kext：

Lilu--------------------------------------1.5.0

VirtualSMC------------------------------------1.1.9

WhateverGreen---------------------------------1.4.5

AppleALC--------------------------------------1.5.5

LucyRTL8125Ethernet---------------------------1.1.0

USBInjectAll---------------------------------0.7.6


macOS Version:

macOS High Sierra 10.13.6（17G66）

macOS Mojave 10.14.6（18G103）

macOS Catalina 10.15.7（19H15）

macOS Big Sur 11.0.1 （20B29）

macOS Big Sur 11.1.1 （20C69）

<img src='https://github.com/IlikemacOS/B460M-MORTAR-Comet-Lake-IGPU-AGPU/blob/main/Screenshot/1.jpg'/>

<img src='https://github.com/IlikemacOS/B460M-MORTAR-Comet-Lake-IGPU-AGPU/blob/main/Screenshot/2.jpg'/>

<img src='https://github.com/IlikemacOS/B460M-MORTAR-Comet-Lake-IGPU-AGPU/blob/main/Screenshot/3.jpg'/>

<img src='https://github.com/IlikemacOS/B460M-MORTAR-Comet-Lake-IGPU-AGPU/blob/main/Screenshot/6.jpg'/>


架構: iMac20,1

功能測試

☑️ 並行 Sidecar

☑️ 接力 Handoff

<img src='https://github.com/IlikemacOS/B460M-MORTAR-Comet-Lake-IGPU-AGPU/blob/main/Screenshot/1.jpg'/>

<img src='https://github.com/IlikemacOS/B460M-MORTAR-Comet-Lake-IGPU-AGPU/blob/main/Screenshot/4.jpg'/>

<img src='https://github.com/IlikemacOS/B460M-MORTAR-Comet-Lake-IGPU-AGPU/blob/main/Screenshot/5.jpg'/>

☑️ iMessage/FaceTime

☑️ AirDrop

<img src='https://github.com/IlikemacOS/B460M-MORTAR-Comet-Lake-IGPU-AGPU/blob/main/Screenshot/7.jpg'/>

<img src='https://github.com/IlikemacOS/B460M-MORTAR-Comet-Lake-IGPU-AGPU/blob/main/Screenshot/8.jpg'/>

☑️ 睡眠/喚醒 Sleep

☑️ USB 端口已定制

☑️ 內顯加速

☑️ 板載聲卡

☑️ 板載乙太網路卡

板载乙太網路卡設定

系統偏好設定 -> 網路 -> 乙太網路（進階） -> 硬體 -> 設定:手動, 速度:1000baseT（根據你的路由器速率進行設定）, 雙工:全雙工, MTU:標準 1500


<img src='https://github.com/IlikemacOS/B460M-MORTAR-Comet-Lake-IGPU-AGPU/blob/main/Screenshot/%E7%B6%B2%E8%B7%AF%E8%A8%AD%E5%AE%9A.jpg'/>

<img src='https://github.com/IlikemacOS/B460M-MORTAR-Comet-Lake-IGPU-AGPU/blob/main/Screenshot/%E9%80%B2%E9%9A%8E.jpg'/>

BIOS設定（請更新你的BIOS版本為7C82v13，BIOS檔案名為E7C82IMS.130，BIOS更新日期為2020-10-13，否則無法進行我下面的某些設定

<img src='https://github.com/IlikemacOS/B460M-MORTAR-Comet-Lake-IGPU-AGPU/blob/main/Screenshot/BIOS%E8%A8%AD%E5%AE%9A/Menu.bmp'/>

<img src='https://github.com/IlikemacOS/B460M-MORTAR-Comet-Lake-IGPU-AGPU/blob/main/Screenshot/BIOS%E8%A8%AD%E5%AE%9A/Settings-Advanced.bmp'/>

<img src='https://github.com/IlikemacOS/B460M-MORTAR-Comet-Lake-IGPU-AGPU/blob/main/Screenshot/BIOS%E8%A8%AD%E5%AE%9A/Adobe%204G%20memory.bmp'/>

<img src='https://github.com/IlikemacOS/B460M-MORTAR-Comet-Lake-IGPU-AGPU/blob/main/Screenshot/BIOS%E8%A8%AD%E5%AE%9A/IGD%20Multi-Monitor.bmp'/>

<img src='hhttps://github.com/IlikemacOS/B460M-MORTAR-Comet-Lake-IGPU-AGPU/blob/main/Screenshot/BIOS%E8%A8%AD%E5%AE%9A/XHCI%20Hand-Off.bmp'/>

<img src='https://github.com/IlikemacOS/B460M-MORTAR-Comet-Lake-IGPU-AGPU/blob/main/Screenshot/BIOS%E8%A8%AD%E5%AE%9A/Resume%20By%20USB%20Device.bmp'/>

<img src='https://github.com/IlikemacOS/B460M-MORTAR-Comet-Lake-IGPU-AGPU/blob/main/Screenshot/BIOS%E8%A8%AD%E5%AE%9A/OC-CPU%20Features.bmp'/>

<img src='https://github.com/IlikemacOS/B460M-MORTAR-Comet-Lake-IGPU-AGPU/blob/main/Screenshot/BIOS%E8%A8%AD%E5%AE%9A/CFG%20Lock.bmp'/>

USB睡眠喚醒問題請看BIOS設定例子

如有其他問題，請加Q群：1125705781，備註小明或B站
