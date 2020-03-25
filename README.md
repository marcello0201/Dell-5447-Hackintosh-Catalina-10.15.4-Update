https://ibb.co/g4FXB4F

Dell Inspiron 5447 Bios A12

Intel Core i7 4510U @2.00GHZ

Intel HD4400

16GB DDR3L 1600MHZ

SSD 1TB SanDisk

Clover_r5107 / MacOS x 10.15.4 (19E266)

Hardware Specs:

Suportado:

Audio / Microfone : Realtek ALC255 | Ok

Video / HDMI : Intel HD4400 | Ok 

Backlight: | Ok 

Wifi & bluetooth: Artheros AR9565 | Ok Substituído a placa  por Broadcom bcm94352z (NGFF DELL DW 1560)

Rede cabeada: Realtek RTL 8100 | Ok

Teclado e Touchpad | Ok

Portas notebook USB 3.0 / 2.0 | Ok

Não suportado:

Placa Video:Radeon r7 M265

SD card reader:RTS5179

TouchScreen 

EFI/CLOVER/kexts/Other : Onde fica a maioria das Kexts para funcionar o sistema.

/Library/Extensions/ :  As kexts dão suporte ao bluetooth.

/System/Library/Displays/Contents/Resources/Overrides : A pasta da suporte ao display do notebook. 

/usr/bin : Da suporte ao CodecCommander.kext , corrigindo o audio 

Iniciar com o sistema - Repara o chiado do som usando fones de ouvido P2

Kexts usados:

 EFI/CLOVER/kexts/Other
 
ACPIBatteryManager.kext

AppleALC.kext

CodecCommander.kext

FakePCIID_Broadcom_WiFi.kext

FakePCIID_Intel_HD_Graphics.kext

FakePCIID.kext

FakeSMC.kext

Lilu.kext

RealtekRTL8100.kext

VoodooPS2Controller.kext

WhateverGreen.kext

/Library/Extensions/

BrcmBluetoothInjector.kext

BrcmFirmwareRepo.kext

BrcmPatchRAM3.kext

/System/Library/Displays/Contents/Resources/Overrides

DisplayProductID-5f1

/usr/bin

hda-verb

Iniciar com o sistema 

AudioScript

Jack fix
