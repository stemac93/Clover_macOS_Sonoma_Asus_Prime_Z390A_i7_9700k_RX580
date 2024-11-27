# Clover_macOS_Sonoma_Asus_Prime_Z390A_i7_9700k_RX580
This is a Clover version of ASUS Z390-A Prime Hackintosh EFI. It works on macOS Monterey 14,4. Sleep, Airdrop and Handoff are supported.



## Notes
For USB ports I builded USBMap.kext with usb3 disabled to the 2 dark blue ports at the side of the ethernet ports and the usb2 functionality disabled to one of the ports right under the hdmi port. All other ports of the mono and the 2 usb3.1 ports to the side of the case will have all their functionality active.


## Hardware
| Item | Brand | Model | Driver | Comment |
|-----|-----|-----|-----|-----|
| Motherboard | ASUS | Z390-A Prime | | |
| CPU | Intel | i7-9700K | | |
| RAM | Corsair | 2x16GB DDR4 3600 | | XMP 3600 |
| iGPU | Intel | UHD 630 | built-in | |
| dGPU | Saphire | RX580 8GB Nitro+ | built-in | |
| SSD1 | Samsung | 980 Evo 512gb nvme | | Main SSD Mac OS |
| Wireless | Broadcom | BCM94360CD | built-in | |
| Ethernet | Intel | I219-V | [IntelMausi](https://github.com/acidanthera/IntelMausi) | |
| Audio | Realtek | ALC S1220A | [AppleALC](https://github.com/acidanthera/AppleALC) | |



## BIOS Setup
| Name | Option | Comment |
| --- | --- | --- |
| Intel SpeedStep | Enabled | |
| Turbo Mode | Enabled | |
| CFG Lock | Disabled | |
| VT-d | Enabled | |
| Above 4G Decoding | Enabled | |
| Re-Size BAR Support | Auto | |
| SR-IOV Support | Enabled | |
| Primary Display | PCIE | |
| iGPU-Multi-Monitor | Enabled | |
| DVMT Pre-Allocated | 1024M | |
| TPM Device Selection | Firmware TPM | |
| Security Device Support | Enable | |
| TPM2.0 UEFI Spec Version | TCG_2 | |
| Serial Port | Off | |
| ErP Ready | Disabled | |
| Legacy USB Support | Enabled | |
| XHCI Hand-off | Disabled | |
| Fast Boot | Disabled | |
| OS Type | Other OS | in case you want windows uefi mode use this [Guide](https://www.tonymacx86.com/threads/guide-opencore-and-uefi-secure-boot-using-windows-subsystem-for-linux.317166/#post-2295190) |
| Launch CSM | Disabled | |

## Known issue
No issues found

## Acknowledgement
Apple for macOS

CloverHackyColor for Clover Bootloader

headkaze for Hackintool

m4ary for OpenCore-Asus-Prime-Z390A_i7-9700K_RX580
