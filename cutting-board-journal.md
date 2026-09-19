---
title: "Cutting Board "
author: "stolen_username"
description: "a custom made rp2040 board"
created_at: "2026-08-25"
---

# 2026-09-18: Added an Accelerometer to make it more unique

**Total time spent: 1 hour 40 minutes**

so my devboard returned to me once again for almost being a replica of the tutorial, so i decided to add something unique

# what did i do?
- added mpu-6050 (accelerometer) in the devboard
- INT is connected to GPIO25 so that the rp2040 can talk with the accelerometer.
- controlling pins are GPIO4 and GPIO5 for the mpu-6050
- mentioned in the github readme that im going to hand solder this

schematic:
![Screenshot_2026-09-18_at_6.58.44_PM.png](https://cdn.hackclub.com/01a0b4b4-9c8b-7c4d-8a88-8cdbd83f21dd/Screenshot_2026-09-18_at_6.58.44_PM.png)

pcb:
![Screenshot_2026-09-18_at_6.59.38_PM.png](https://cdn.hackclub.com/01a0b4b5-a348-7b42-b7a5-b754cefb2ad4/Screenshot_2026-09-18_at_6.59.38_PM.png)

# 2026-09-06: 1 minute

**Total time spent: 1 minute**

# what did i do?
- i decided im going to order the parts, and going to hand solder them.
- its going to be one in my aah for sure, but i guess its the most cheapest option i have.

![Screenshot_2026-09-07_at_12.05.43_AM.png](https://cdn.hackclub.com/01a07801-5d24-758c-8d95-63a824a7c249/Screenshot_2026-09-07_at_12.05.43_AM.png)

# 2026-09-01: Updated BOM

**Total time spent: 5 minutes**

# what did i do?
- updated bom with item prices
- links are not there as they are chosen from the jlcpcb pcba option

![Screenshot_2026-09-01_at_9.36.07_PM.png](https://cdn.hackclub.com/01a05db8-90da-7f98-af4c-607b60de14bd/Screenshot_2026-09-01_at_9.36.07_PM.png)

# 2026-08-26: setup github repo + made bom and cpl

**Total time spent: 25 minutes**

# what did i work on?
- added gerber/bom/cpl files to the repo
- made the bom and cpl compatible for jlcpcb
- found the parts and selected them asper the jlcpcb library
- added the pcba finally to the cart (holy expensive)
- then made the readme.md for this
- then added journal to the repo
- then i hit ship ( i think its ready? )

no lapse for this coz i did this very very fast, but it GENUINELY TOOK ME 25 minutes coz why the hell are the names for the components so complicated and long???

![Screenshot_2026-08-26_at_8.16.13_PM.png](https://cdn.hackclub.com/01a03f1a-0f5c-79ac-9969-cd3441d1c809/Screenshot_2026-08-26_at_8.16.13_PM.png)

# 2026-08-26: Silkscreen

**Total time spent: 21 minutes**

# what did i do?
- found some cool designs and set up the silkscreen.

lapse recording -> https://lapse.hackclub.com/timelapse/9ISGdCb-K3YG

![Screenshot_2026-08-26_at_7.01.17_PM.png](https://cdn.hackclub.com/01a03e44-a697-79a0-a13c-b3ebe8f7d295/Screenshot_2026-08-26_at_7.01.17_PM.png)

![Screenshot_2026-08-26_at_7.01.42_PM.png](https://cdn.hackclub.com/01a03e45-077b-7306-b80b-6389a5f4fe58/Screenshot_2026-08-26_at_7.01.42_PM.png)
( it is written "routing was hell. nevertheless, we did it." )

# 2026-08-26: completed the pcb

**Total time spent: 1 hour 53 minutes**

# what did i do?
- i have won, but at what cost?
- finally completed the routing (it was hell)
- first i completed setting up some leftover components
- then started the routing
- when i was routing, i had realised i had put some resistors in place of capacitors (on god im dumb)
- fixed those and got back to work
- routed the usb c
- routed the gpio pins to the gpio of the rp2040 chip
- routed the decoupling capacitors
- placed A LOT of vias
- spilled copper on the pcb coz im not covering the entire thing with a million vias
- it made a nice little net for gnd, so every gnd pin is connected to gnd, and every other is connected to their respective end
- some errors had come in the DRC (design rule checker if you didn't know (im sure u have)), checked that out and fixed those quickly
- and finally completed the routing and pcb was done finally.

lapse recording -> https://lapse.hackclub.com/timelapse/yU2to8uIAMKQ

![Screenshot_2026-08-26_at_6.50.00_PM.png](https://cdn.hackclub.com/01a03e3a-6541-7297-ab05-49d63326edd0/Screenshot_2026-08-26_at_6.50.00_PM.png)

![Screenshot_2026-08-26_at_6.50.25_PM.png](https://cdn.hackclub.com/01a03e3a-cd88-7d43-b197-62785ce96532/Screenshot_2026-08-26_at_6.50.25_PM.png)

# 2026-08-26: Started the routing + 50% pcb done (hurray)

**Total time spent: 38 minutes**

# what did i do?
- added all the decoupling capacitors
- it took me a solid minute to learn how to rotate an smd capacitor 45 deg
- also fun fact, i recorded the lapse when spain won the world cup

lapse recording -> https://lapse.hackclub.com/timelapse/5kd-ANLFqNg0

![Screenshot_2026-08-26_at_6.43.47_PM.png](https://cdn.hackclub.com/01a03e34-9e81-7a5d-ad4d-1c5801e4fbb2/Screenshot_2026-08-26_at_6.43.47_PM.png)

# 2026-08-26: Started the PCB for this monstrosity

**Total time spent: 33 minutes**

# what did i do?
- assigned the footprints
- opened the pcb editor (r we srs gng)
- positioned the gpio pins correctly (took me so long to figure out how it works)
- positioned the rp2040 chip and the usb c :p

lapse recording -> https://lapse.hackclub.com/timelapse/PoyksY5xZc1w

![Screenshot_2026-08-26_at_5.20.37_PM.png](https://cdn.hackclub.com/01a03de8-d737-7e9c-aa4f-f8f8fc9722dc/Screenshot_2026-08-26_at_5.20.37_PM.png)

# 2026-08-25: Added Flash Storage + GPIO Pins and also added decoupling capacitors + schematic complete

**Total time spent: 32 minutes**

# what did i do?
- added flash storage
- added a button which would potentially load the devboard into bootsel mode (i think it is called that)
- added gpio pins which would go on the pcb (no shit)
- mapped those gpio with the rp2040 gpio
- added decoupling capacitors
- tidied up the schematic, it looks good now

lapse recording -> https://lapse.hackclub.com/timelapse/iEin5HjV4DM5

![Screenshot_2026-08-25_at_2.14.47_PM.png](https://cdn.hackclub.com/01a03818-0371-773f-9dd5-5367c7d25b7d/Screenshot_2026-08-25_at_2.14.47_PM.png)
![Screenshot_2026-08-25_at_2.15.11_PM.png](https://cdn.hackclub.com/01a03818-65d6-74ae-b313-c783abef6356/Screenshot_2026-08-25_at_2.15.11_PM.png)

# 2026-08-25: Made the Project + Basic Schematic made

**Total time spent: 41 minutes**

# what did i work on?
- started the project (duh)
- made a basic schematic
- added the parts in the schematic editor and mapped only a few
- learned how usb c adapter works (wow)
- also learned about the ams 3.3v converter thing

lapse recording -> https://lapse.hackclub.com/timelapse/9J0623Afvo5e

![Screenshot_2026-08-25_at_2.08.38_PM.png](https://cdn.hackclub.com/01a03812-5f70-706c-84ab-1f8a4e23dd59/Screenshot_2026-08-25_at_2.08.38_PM.png)
![Screenshot_2026-08-25_at_2.09.34_PM.png](https://cdn.hackclub.com/01a03813-415e-7d47-a58f-7152467bb8c9/Screenshot_2026-08-25_at_2.09.34_PM.png)

