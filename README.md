# Asrock_b365m-hdv_i5-9400_rx-570

MacOS 10.15.2 Catalina 

Hardware:

ASRock B365M-HDV

Intel i5-9400

XFX RS XXX Edition Radeon RX 570

SAMSUNG 850 EVO 500GB SATA SSD

2x G.SKILL Aegis 16GB F4-2666C19S-16GIS

I have not tested NVME or the M.2 slot and my custom USB Port Limit patch (USBPorts.kext) probably disables it's internal USB Port.

I have disabled some of the front bracket USB Ports and set the black ports on the back of the motherboard to be USB2 only to be under the 15 port limit. Use USBInjectAll.kext and remove CLOVER/kexts/Other/USBPorts.kext if you want to temporarily enalbe all USB Ports so that you can customize USB settings. [1][2]

[1] https://github.com/RehabMan/OS-X-USB-Inject-All

[2] https://github.com/headkaze/Hackintool
