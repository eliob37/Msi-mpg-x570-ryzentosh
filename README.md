# Msi-mpg-x570- ryzen9-3900x-ryzentosh

OpenCore 0.5.9 Files for AMD Board : MSI mpg X570 and ryzen 9 3900x.

BIOS-Version: 7C37vA84 (Beta version) | SMBIOS iMacPro1,1

---BIOS SETTING---

on save and exit-Restore default
on advanced/acpi settings-Avobe 4g memory           -SET TO enable

on advanced/super IO configuration/serial port COM  -SET TO-DISABLE

on power management setup/ErP READYS                -SET TO-Enable

on windows OS configuration/bios uefi/csm mode-UEFI -SET TO-UEFI

on advanced/wake up event setup                     -SET TO-ENABLE EVERYTHING

on boot/boot option 1                               -SET TO -Your hard disk name

on save and exit---reboot---

--Software--

OpenCore 0.5.9

Mac OS Catalina 10.15.5

--Hardware--

Motherboard: MSI mpg X570 Gaming edge wifi.

NVMe SSD samsung evo 970.

Amd Ryzen 9 3900x.

AMD GPU Radeon RX580 Nitro+.


-- What is working--

Builting Bluetooth.

Usb power on.

Ethernet.

Audio.

Messages,App Store,Icloud ....

Audio.

-- What is not working--

Sleep (Save Energy).
2 x USB 2.0 Ports (Backside).
WIFI.

BENCHMARK

on  GEECKBENCH 5-SINGLE CORE=1335 MULTICORE=12367 

ON CINEBENCH=7491.

Update # 1: replace RX 580 for rx 5700xt saphire nitro plus.

Mandatory:
in config.plist add gdpmod = pikera in boot-args.

-gpu bios in option 2.can confirm no fan noise and good temperatures.(33 to 37without charge)
-in bios pci generation in auto.
