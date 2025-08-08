# <div align="center">Asus X509FB Hackintosh</div> 
EFI hackintosh for Asus Vivobook X509FB with Nvidia MX110 (disabled).

## Bootloader and macOS Versions

| OpenCore  | macOS   |
| --------  | ------- |
|   1.0.5   | Sequoia 15.6 (Use SMBIOS ```MacBookPro15,3```) |

## Screenshots

<div align="center">

<img width="1920" height="1080" alt="Captura de pantalla 2025-08-08 a la(s) 5 32 04 p  m" src="https://github.com/user-attachments/assets/d669a685-6def-4d22-807e-666381788021" />

</div>

## Laptop Specification
 
|                     | Specifications| Note |
| ---------------------------- | ---------------------- |------------------|
| ``Chipset``| Intel Chipset |   |
| ``CPU``| QuadCore Intel Core i5-8265U 1.60 GHz |   |
| ``Memory``| 8GB DDR4 2400Mhz | 2 x 4GB DDR4. |
| ``iGPU``| Intel UHD Graphics 620 1100 MHz | Spoofed as Iris Plus 655, HDMI working |
| ``eGPU``| Nvidia MX110 2GB GDDR5 | Disabled with -wegnoegpu |
| ``Disk``| SSD NVMe SK Hynix 128GB | NVMe Fix kext |
| ``Fingerprint`` | Synaptics FP Sensors | Not working in macOS. |
| ``Wifi``| Realtek RTL8821ce | (Not working) Using Archer T2U Plus dongle, configured with [Chris111's driver](https://github.com/chris1111/Wireless-USB-Big-Sur-Adapter). | 
| ``Audio``| Realtek ALC256 | Add `alcid=66` to boot-arg or add layout-id to DeviceProperties. |

## Recommendations

Get a cheap Intel WiFi card from AliExpress, like 7260NGW or 7265NGW. 

