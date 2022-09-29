# Hackintosh-Acer-Spin5-54N
Sep 2022, Opencore 0.8.3, compatible with macOS 12

Welcome to this repository, I will provide you info about my Hackintosh Acer Spin 5.

Spec:
Operating System: macOS 12.6 Monterey & Windows 10

CPU: I5-8250U (Kaby-Lake)
RAM: 8GB DDR4 2400 Mhz
GPU: Intel UHD 620
Audio: Realtak ALC 295 (w/ Intel Sunrise Point-LP HD Audio)
Wi-Fi: Broadcom 94352Z
Storage: Micron 1100 256GB SATA SSD

Working peripherals:
Almost everthing working 

EXCEPT:
Using a touchpen on the monitor (Work in Windows but not macOS)
BIOS (After installing both Opencore & Windows Boot Manager, I can't access the BIOS)
USB Card Reader
Fingerprint sensor
HDMI Port (Working DP output by using the Type-C)
Function key for toggling Wi-Fi

Preperation before installing:
Make sure you have a USB mouse with you.
Create a USB installer for macOS according to Dortania's Opencore guide.
(I'm using a 32GB USB with the Rufus Method)

In BIOS, turn OFF 1.Secure BOOT 2.ENABLE VT-D & VT-X (This two will be handled in the ACPI patch) 3.(Optional) Reset BIOS to default setting
