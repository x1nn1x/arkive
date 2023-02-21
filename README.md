# Arkive v0.1 - 
Build your own Ark Dev Kit

A full Ark Dev Kit consists of a [screen](https://mou.sr/3QI0UAi), [battery](https://mou.sr/3QJygi1), [micro-sd card](https://mou.sr/3WlwoNI), [compute module](https://www.raspberrypi.com/products/compute-module-3-plus/), a case, and the Ark PCB both of which are available to be printed using this Arkive.

How To:

Upload one of these Gerber .zips to a PCB Manufacturer for them to print and deliver the PCBs needed you need to build an Ark Dev Kit. Print the case at home, or upload the files to a 3D printing service.

Notes:

Enabling touch screen

    Add Distro/pullup.dtbo to /boot/overlays
    Add Distro/touchscreen.dtbo to /boot/overlays
    Replace /home/pi/.bashrc with the Distro/.bashrc provided
    Make sure you are using the provided Distro/config.txt in /boot/

Enabling buttons

    Add Distro/buttons.dtbo to /boot/overlays
    Make sure you are using the provided Distro/config.txt in /boot/

Raspberry Pi Compute Module 3L+ (pending transition to CM4 and RISC-V): https://www.raspberrypi.com/products/compute-module-3-plus/

Newhaven Display 4.3" Capacitive Touch (pending transition to OLED and e-ink options]): [Mouser #: 763-4.3480272EFASXVC](https://mou.sr/3QI0UAi)

2500mAh LiPo battery: [Mouser #: 485-328](https://mou.sr/3QJygi1)

SD Card: [Mouser #: 467-SDSDQAD-128G](https://mou.sr/3WlwoNI)

Made with Love by Humans on Earth
