# EFI folder for OpenCore hackintosh for MSI GF63 Thin 10SCXR

Built for macOS Ventura (13.5.1, but should work on other versions of Ventura)

Official laptop link: https://www.msi.com/Laptop/GF63-Thin-10SCXR/Specification



## Useful specs:

CPU: Intel i7-10750H (Comet Lake)

iGPU: Intel UHD Graphics 630

Dedicated GPU: GTX 1650 (disabled with `-wegnoegpu`)

Wi-Fi: Intel Wi-Fi 6 AX201

Bluetooth: Intel Wireless Bluetooth

Ethernet: Realtek PCIe GbE Family Controller

Audio: Realtek ALC235

## Fixes / important notes

### (FIX) Black screen for 3 minutes after boot

Add `-igfxblr` in your boot-args

### Webcam

Make sure your webcam is ON while using USBToolBox tool, or you won't be able to use your webcam on macOS.

### AppleALC layout / ALCID

Use `alcid=29` in order for audio to work the best (works with internal speaker as well)
