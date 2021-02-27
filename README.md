# Lenovo-P340-Tiny-Hackintosh
Lenovo P340 Tiny Hackintosh complete working

macOS Big Sur 11.2.1 (20D75)

Hardware Specs:

CPU: i5 10400

RAM: Samsung 32GB 3200 *2 SODIMM

SSD: Samsung 970 EVO Plus 500GB

WiFi: BCM943602CS + Adapter

SMBIOS type  iMac20,1

If you use 10th gen core i7 or i9 which has 8 cores or more ,change it with iMac 20,2



Before installing:

do BIOS setup

1.Devices->ATA Drive Setup->Configure SATA as AHCI

2.Devices->Video Setup->Select Active Video:IGD,Pre-Allocated Memory Size 64MB(or larger)

3.Security->Secure Boot->Secure Boot ->Disable

Not working :
When use DP Cable connect to a monitor,there is no Audio output(Internal Speaker working well)
This may be caused by wrongly configured UHD630 driver

![](/Users/experienced/Lenovo-P340-Tiny-Hackintosh/sample.png)