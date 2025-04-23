# MaaXBoard-Mini-HUB
![Title](https://github.com/Avnet/MaaXBoard-Mini-HUB/assets/88205887/1afc265c-0d1c-4831-a0b6-7d81c94fe3be)

Welcome to the information hub for MaaXBoard Mini, featuring the [NXP i.MX 8M Mini](https://www.nxp.com/products/processors-and-microcontrollers/arm-processors/i-mx-applications-processors/i-mx-8-applications-processors/i-mx-8m-mini-arm-cortex-a53-cortex-m4-audio-voice-video:i.MX8MMINI) applications processor based on Arm® Cortex®-A53 and Cortex-M4 cores provide advanced audio, voice and video processing for applications that scale from consumer home audio to industrial building automation and mobile computers. This repository serves as a central hub for all resources related to MaaXBoard Mini. <br />

[Buy MaaXBoard](https://www.avnet.com/wps/portal/us/products/avnet-boards/avnet-board-families/maaxboard/maaxboard?family=&nodeClicked=d8e2c09b-9600-4ba7-b7ed-82a834b5177d)

## Table of Contents
- [MaaXBoard-Mini-HUB](#maaxboard-mini-hub)
  - [Table of Contents](#table-of-contents)
  - [About](#about)
    - [Processing](#processing)
    - [Form Factor \& Interfaces](#form-factor--interfaces)
    - [Memory \& Storage](#memory--storage)
    - [Software \& BSP](#software--bsp)
      - [Board Support Package](#board-support-package)
      - [Image Package](#image-package)
      - [Yocto SDK Install Scripts](#yocto-sdk-install-scripts)
      - [BootLoader u-boot Image](#bootloader-u-boot-image)
      - [Pre-Built Linux Image](#pre-built-linux-image)
      - [Reference Design Tools](#reference-design-tools)
    - [Accessories](#accessories)
  - [Related Repositories](#related-repositories)
  - [Related Blog Posts](#related-blog-posts)
    - [Element14 projects](#element14-projects)
    - [Hackster.io projects](#hacksterio-projects)
  - [Getting Started and Manuals](#getting-started-and-manuals)
    - [Product Brief](#product-brief)
    - [Software Documents](#software-documents)
    - [Getting Started Guides](#getting-started-guides)
    - [Hardware Guides](#hardware-guides)
    - [Quick Start Card](#quick-start-card)
    - [Development Guides](#development-guides)
    - [Production Documents](#production-documents)
    - [Release Notes](#release-notes)
    - [Errata and Product Change Notices](#errata-and-product-change-notices)


## About
MaaXBoard Mini is a low-cost, production ready development board in the popular and compact Raspberry Pi form-factor, which supports a versatile set of I/O interfaces. This [NXP i.MX 8M Mini](https://www.nxp.com/products/processors-and-microcontrollers/arm-processors/i-mx-applications-processors/i-mx-8-applications-processors/i-mx-8m-mini-arm-cortex-a53-cortex-m4-audio-voice-video:i.MX8MMINI) processor-based platform contains everything necessary to support and create a Linux, Android, or other OS based system. MaaXBoard Mini provides industry-leading audio, voice, and video processing for applications that scale from consumer home audio to industrial building automation and embedded computers.<br />

<details>
    <summary>More information & Specs</summary>

### Processing
The i.MX 8M device is architected with 2 separate processing domains: The application domain includes Quad Arm® Cortex®-A53 cores @1.8GHz. The Real Time domain includes an Arm Cortex-M4F core @400MHz.


### Form Factor & Interfaces
<p align="center">
    <img src="https://github.com/Avnet/MaaXBoard-Mini-HUB/assets/88205887/fa4eeefe-822b-4aa7-a15c-6754e1fa365b" width="500">
</p>
MaaXBoard Mini is engineered in compact Raspberry Pi form-factor, which supports a versatile set of I/O interfaces. These include Gigabit Ethernet, quad USB 2.0 host interfaces, MIPI DSI display and MIPI CSI camera interfaces, Wi-Fi 802.11 b/g/n/ac, Bluetooth 4.2 (BLE), Onboard Ceramic Antenna with an optional external antenna support, a Pi-HAT compatible 40-pin header and Audio Expansion.

Power is sourced via a USB-C connector and is managed via onboard voltage regulators.

### Memory & Storage

MaaXBoard Mini is well resourced with 2GB DDR4 SDRAM, MicroSD Slot, plus eMMC Boot memory expansion support (optional, not populated by default).

### Software & BSP

#### Board Support Package
[Debian source files](https://avnet.me/maaxboard-mini-debian)

[Yocto source files](https://avnet.me/maaxboard-mini-yocto)

[Android source files](https://github.com/Avnet/android-imx-platform-hardware-imx)

#### Image Package
[Debian Linux Out of Box Image (zip)](https://downloads.element14.com/downloads/zedboard/MaaxBoard/maaxboard-mini/02LinuxShipmentImage_Debian.zip)

[Yocto Linux Out of Box Image V1.1.0r03 (zip)](https://avtinc.sharepoint.com/:u:/t/ET-Downloads/EW03iCLdcKhDqTb67jT6KfkB2xK56wNLuOeKIzSDqklaaQ?e=Qa9FX2)

[Android 9 Out of Box Image (zip)](https://downloads.element14.com/downloads/zedboard/MaaxBoard/maaxboard-mini/02AndroidShipmentImage.zip)

#### Yocto SDK Install Scripts
[Yocto SDK Install Scripts](https://avtinc.sharepoint.com/:u:/t/ET-Downloads/EajJSq93xtJAhx6hytvI-e8BTYhO4iHovizJnS0awc_W0Q)

#### BootLoader u-boot Image
[BootLoader u-boot Image](https://avtinc.sharepoint.com/:u:/t/ET-Downloads/EX0QXULJ4vJMhiKvh0CTVTYBq9dW9tXiHJRAikRoUqLQTg)

#### Pre-Built Linux Image
[Pre-Built Yocto Linux Image](https://avtinc.sharepoint.com/:u:/t/ET-Downloads/EYfSNUQLFdhGuTZMyuvl370BZzo_VtoD-FBxTgarm_6JRA)

[Manifest for Yocto Linux Image](https://avtinc.sharepoint.com/:u:/t/ET-Downloads/EfrPHU0k_TlEtGWS_TXhkpwBbXG2omVJxNKUmKaLgRnlSw)

#### Reference Design Tools
[Android Environment Tools (zip)](https://www.avnet.com/wps/wcm/connect/onesite/731417ce-b8bd-4b86-87ad-a4c6cd1d3c09/Android_Enviroment_Tools.zip?MOD=AJPERES&CVID=nAsWbyw&CVID=nAsWbyw&CVID=nAsWbyw&CVID=nAsWbyw&CVID=nAsWbyw&CVID=nAsWbyw)

[Linux Environment Tools (zip)](https://www.avnet.com/wps/wcm/connect/onesite/e7405566-56dc-4829-9727-5e2c8c4ac7ba/Linux_Environment_Tools.zip?MOD=AJPERES&CVID=nAsXwXg&CVID=nAsXwXg&CVID=nAsXwXg&CVID=nAsXwXg&CVID=nAsXwXg&CVID=nAsXwXg)



### Accessories 
Available accessory options include a [MIPI 7-inch display](https://www.avnet.com/shop/us/products/avnet-engineering-services/aes-acc-maax-disp2-3074457345648625681/), [MIPI CSI camera](https://www.arducam.com/product/arducam-5mp-mipi-camera-for-rzboard-v2l-with-renesas-rz-v2l-processor/), [Monarch Go Pi HAT](https://www.avnet.com/shop/us/products/avnet-engineering-services/aes-sqn-mnrchgo-ht1-g-3074457345643590213?krypto=e0lzEpB9jb7ah4ATyfiftdtPavKJ51pxv9nj8tghkWtFraife%2B18YAUtSlZZwiYtG1f3luULUju9b20mXEPp18V85bfzqsmsRUyjuptqCXtGdXnLNSvpTcsqvon3OBXd) and [5V/3A USB Type C power supply](https://www.avnet.com/shop/us/products/avnet-engineering-services/aes-acc-maax-pwrul-3074457345642357173/).

[View other Avnet boards](https://www.avnet.com/wps/portal/us/products/avnet-boards/)
</details>


## Related Repositories
- [MaaXBoard Metalayer](https://github.com/Avnet/meta-maaxboard): Contains the Yocto metalayer for MaaXBoards as well as **building information**
- [U-boot source code](https://github.com/Avnet/uboot-imx): Contains the source code for U-Boot, a boot loader for Embedded boards.
- [Linux kernel source code](https://github.com/Avnet/linux-imx): Contains the source code for the Linux kernel.
- [imx-mkimage source code](https://github.com/Avnet/imx-mkimage): i.MX Mkimage Bootloader Tool for Yocto and Android.
- [imx-atf source code](https://github.com/Avnet/imx-atf): Trusted Firmware-A (TF-A) is a reference implementation of secure world software for Arm A-Profile architectures.


## Related Blog Posts 
### Element14 projects
[MaaXBoard Chronicles](https://www.element14.com/community/community/designcenter/single-board-computers/blog/2021/08/02/maaxboard-chronicles)

### Hackster.io projects
| Topic | Description | Difficulty |
| -- | -- | -- |
| [Getting Started with MaaXBoard](https://www.hackster.io/monica/getting-started-with-maaxboard-ca362d) | Getting started guide for the Avnet MaaXBoard | Beginner |
| [Hard Hat Detection with Edge Impulse on MaaXBoard Mini](https://www.hackster.io/monica/hard-hat-detection-with-edge-impulse-on-maaxboard-mini-dfd0ca) | Detect hard hats using the Edge Impulse Linux SDK on MaaXBoard Mini | Intermediate |
| [Build Your Own Tensorflow for MaaXBoard and MaaXBoard Mini](https://www.hackster.io/monica/build-your-own-tensorflow-for-maaxboard-and-maaxboard-mini-91cddc) | Build a Tensorflow wheel that runs on MaaXBoard and MaaXBoard Mini. | Intermediate |

## Getting Started and Manuals
### Product Brief
[MaaXBoard Mini Product Brief](https://www.avnet.com/wcm/connect/d40a297c-2805-4c5f-af34-cc246ac3e2da/FY25_1574_Tria_Maaxboard_Mini_Product_Brief-2_vp.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE-d40a297c-2805-4c5f-af34-cc246ac3e2da-pm6msEQ)

### Software Documents
[MaaXBoard Mini Linux Yocto User Manual](https://www.avnet.com/wcm/connect/a1d48ca9-a3f9-4423-bac2-f60f82ffb85b/MaaXBoard-Mini-Linux-Yocto-UserManual-V2.0.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE-a1d48ca9-a3f9-4423-bac2-f60f82ffb85b-oFe8sVG)

[MaaXBoard Mini Linux Yocto Development Guide](https://www.avnet.com/wcm/connect/9a31960c-201d-467d-862b-ef0af00cd866/MaaXBoard-Mini-Linux-Yocto-Development_Guide-V2.0.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE-9a31960c-201d-467d-862b-ef0af00cd866-oFe8iKg)

[MaaXBoard Mini Linux Yocto Release Note](https://www.avnet.com/wcm/connect/9bf9b035-9276-4583-bb1b-8253a99595af/MaaXBoard-Linux-ReleaseNote-V1.2.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE-9bf9b035-9276-4583-bb1b-8253a99595af-nubRh1m)

### Getting Started Guides
[MaaXBoard Mini Android User Manual V1.0-EN](https://www.avnet.com/wps/wcm/connect/onesite/7184c5c1-6339-4d81-ac54-65ffb8e57b5d/MaaXBoard_Mini-Android-UserManual-V1.0-EN.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-7184c5c1-6339-4d81-ac54-65ffb8e57b5d-nygepxY)

[MaaXBoard Mini Linux Debian User Manual V1.1-EN](https://www.avnet.com/wps/wcm/connect/onesite/bad2e2f0-d31a-4d81-8693-cc1de264ef56/MaaXBoard_Mini-Linux-Debian-UserManual-V1.1-EN.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-bad2e2f0-d31a-4d81-8693-cc1de264ef56-nygeq5z)

[MaaXBoard Mini Linux Yocto Lite User Manual V1.1-EN](https://www.avnet.com/wps/wcm/connect/onesite/97bbd003-867f-45fb-848c-c816c2f7e26f/MaaXBoard-Mini-Linux-Yocto-Lite-UserManual-V1.1-EN.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-97bbd003-867f-45fb-848c-c816c2f7e26f-nZCsEec)

[MaaXBoard-Mini-Linux-Yocto-UserManual-V2.0](https://www.avnet.com/wps/wcm/connect/onesite/a1d48ca9-a3f9-4423-bac2-f60f82ffb85b/MaaXBoard-Mini-Linux-Yocto-UserManual-V2.0.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-a1d48ca9-a3f9-4423-bac2-f60f82ffb85b-oFe8sVG)

### Hardware Guides
[MaaXBoard Mini Hardware User Manual V1.0-EN](https://www.avnet.com/wps/wcm/connect/onesite/46fcceb4-9be3-4242-a660-b0504ec2e383/MaaXBoard+Mini-Hardware_UserManual-V1.0-EN.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-46fcceb4-9be3-4242-a660-b0504ec2e383-nygepQ2)

### Quick Start Card
[MaaXBoard Mini QSG Booklet](https://www.avnet.com/wps/wcm/connect/onesite/2294f241-5b95-4f24-96be-2d22635956e6/MaaXBoard_Mini_QSG_Booklet-20200401.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-2294f241-5b95-4f24-96be-2d22635956e6-nygerDB)

### Development Guides
[MaaXBoard Mini Android Development Guide V1.0-EN](https://www.avnet.com/wps/wcm/connect/onesite/1133e541-cf1c-4dc6-a5a6-92f94a79c75f/MaaXBoard_Mini-Android-Development_Guide-V1.0-EN.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-1133e541-cf1c-4dc6-a5a6-92f94a79c75f-nygemce)

[MaaXBoard Mini Linux Development Guide V1.0-EN](https://www.avnet.com/wps/wcm/connect/onesite/3a6d2aca-6b31-4a5f-af8b-c5071493b5e7/MaaXBoard_Mini-Linux-Development_Guide-V1.0-EN.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-3a6d2aca-6b31-4a5f-af8b-c5071493b5e7-nygeqoN)

[MaaXBoard Mini Linux Yocto Lite Development Guide V1.2-EN](https://www.avnet.com/wps/wcm/connect/onesite/35645cc9-4317-4ca0-a2fa-30cce5f9ff17/MaaXBoard-Mini-Linux-Yocto-Lite-Development_Guide-V1.2-EN.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-35645cc9-4317-4ca0-a2fa-30cce5f9ff17-nZCsDM0)

[MaaXBoard-Mini-Linux-Yocto-Development_Guide-V2.0](https://www.avnet.com/wps/wcm/connect/onesite/9a31960c-201d-467d-862b-ef0af00cd866/MaaXBoard-Mini-Linux-Yocto-Development_Guide-V2.0.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-9a31960c-201d-467d-862b-ef0af00cd866-oFe8iKg)

### Production Documents
[MaaX LifeCycle 2020](https://www.avnet.com/wps/wcm/connect/onesite/a53baeab-92bf-4f89-b632-43d9ae893cd8/MaaX_LifeCycle_2020.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-a53baeab-92bf-4f89-b632-43d9ae893cd8-nubSE-M)

### Release Notes
[MaaXBoard Mini Android Release Note V1.0](https://www.avnet.com/wps/wcm/connect/onesite/57c8b44b-fd3f-4338-8eb0-2f552546a27c/MaaXBoard_Mini_Android_ReleaseNote-V1.0.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-57c8b44b-fd3f-4338-8eb0-2f552546a27c-nygeonc)

[MaaXBoard Mini Linux Release Note V1.0](https://www.avnet.com/wps/wcm/connect/onesite/594cd104-a280-4d0e-98f1-794add3f2f9c/MaaXBoard_Mini-Linux-ReleaseNote-V1.0.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-594cd104-a280-4d0e-98f1-794add3f2f9c-nyger22)

[MaaXBoard Mini Linux Yocto Lite Release Note V1.1](https://www.avnet.com/wps/wcm/connect/onesite/8db9b6c6-7a8a-43a9-8971-6638a8fa61e8/MaaXBoard-Mini-Linux-Yocto-Lite-ReleaseNote-V1.1.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-8db9b6c6-7a8a-43a9-8971-6638a8fa61e8-nVcmMg6)

### Errata and Product Change Notices
[PCN 21003 Manufacturer Changes](https://www.avnet.com/wps/wcm/connect/onesite/260403e3-abc2-4bfc-b174-3d456a1dc93f/Product+Change+Notification+PCN+21003.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-260403e3-abc2-4bfc-b174-3d456a1dc93f-nDEpL3N)
