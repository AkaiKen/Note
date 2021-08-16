# Windows bootloader failure

#Nov 15, 2020

When I had installed dual system, which is each SSD have one window 10, I found that the old OS can not be boot even I change the boot disk in BIOS.

The reason is that when user install window 10 offline, it will cover other boot loader (maybe bootloader in other disks). Without boot loader, computer can not boot OS in disk anymore. 

So we should use GRUB the solve.

