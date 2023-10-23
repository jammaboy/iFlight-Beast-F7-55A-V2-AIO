# iFlight-Beast-F7-55A-V2-AIO
PRODUCT DESCRIPTION
What if you could get the combined MCU speed and ESC power of a big stack, but carefully arranged on a 25×25 whoop size board? That would be crazy right? Well, we just did it…

This is our new iFlight BEAST series AIO FCs for your ultimate build. A future proof all-in-one FC to step up the game and make some more room for future flight firmware development like Betaflight, Emuflight etc. Lightweight, minimum size, minimum work.This could only be achieved by using BGA chipsets instead of ordinary QFP (big size) MCUs and ultra powerful Mosfets for almost any build. Solder your motor wires on and let’s go! DJI Plug&Play plug and so many UARTs most people wouldn’t even use em’ all. Compatible to digital and analog FPV, onboard Barometer for possible long range flights and much more. Unleash the beast!

 

Top Features:


Vista digital system Plug-and-Play (VBAT passthrough)

MCU: BGA-STM32F745, 216MHz

OSD: AT7456E

Gyro: Bosch BMI270

Blackbox: 16MB Onboard Flash

BEC output: 5V 2.5A

Changelog:


V1.2-V2:  Updated some circuit improvements implemented.

V2-V2.2:  Gyro updated to BMI270.

Safety reminder:


The DJI plug&play port has no voltage regulator (BEC) and is passing through VBAT. The Caddx Vista goes up to 26.4V (6S), the DJI Air Unit goes up to 17.6V (4S). Make sure not to plug-in your DJI Air Unit directly when you’re flying 6S, because this would fry it.


Small motor 4S builds should usually need an additional capacitor of at least 16V/220uF, for 6S go up to 35V or even 50V. Bigger motors have a bigger current draw, higher voltage spikes and more serious back EMF (motor braking, works like a generator). Make sure to add big enough or even bigger low ESR capacitors on the AIO battery pad or on your battery lead the more aggressive motors you fly. There’s a choice of capacitors in the package, but it’s never a bad idea to make sure to protect your board. Smaller boards have less capacitance which has to be covered with external capacitors, there’s no way around.

![Imgur](https://imgur.com/KNHapkQ.png)
 


FC -Beast F7 AIO


Specification:


MCU: BGA-STM32F745

Gyro: Bosch BMI270

Blackbox: 16MB Onboard Flash

BEC output: 5V 2.5A

Barometer: NO

Connector: Micro-USB

OSD: IFLIGHT OSD (AT745E）

FC Firmware：IFLIGHT_F745_AIO_V2

Mounting pattern: 25.5*25.5mm φ3mm

Dimensions: 32.5*32.5mm

Weight: 8.5g
 


ESC - 55A 2-6S

![Imgur](https://imgur.com/ZAVI7RG.png)


Specification:


Uarts: 5

Current Sensor: Yes

Input: 2-6S LIPO

Current scale: 100

Constant: 55A / Burst: 60A

BLHeli: BLHeli-S

Telemetry: no

ESC Firmware: G-H-30 BLS

Mounting pattern: 25.5*25.5mm/Φ3mm

Dimensions: 32.5*32.5mm
