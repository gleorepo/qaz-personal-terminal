# QAZ Model 100

The QAZ Personal Terminal [QAZterm] is a cyberdeck inspired by the TRS/Tandy Model 100 portable computer from the mid 1980s. The QAZterm follows the TRS 100 in being keyboard-focused, but substitutes out the antiquated 75% keyboard for a 35% layout known as QAZ. It ditches single-purpose keys for key chords and layers that eliminates wild hand acrobatics while increasing input speed. 

The QAZterm pairs this keyboard with a 7.9 inch screen. The brains are provided by any of a RPi Zero 2, Banana Pi M2, or RADXA Zero, and the whole system is powered by an Ampripper 3000 power supply and 3500mah battery. 

All of this is packed into case that under an inch thick and no wider than a sheet of letter paper. 

The CPU is cooled by a custom copper heatsink and optional copper case back that let's the computer run overclocked without fans. 

## Parts List
* QAZ Keyboard PCB
	* [cbkbd.com](https://www.cbkbd.com/product/qaz)
* Banana Pi M2 Zero
	* [Amazon](https://amzn.to/3dN8PNy) or [Amazon](https://amzn.to/3Chq7Mb)
* Waveshare 7.9 Screen
	* [Amazon](https://amzn.to/3DZmZps) or [Amazon](https://amzn.to/3DZn7VY)
* Ampripper 3000
	* [Kickstart Design](https://www.kickstart-design.com/our-products/p/amp-ripper-3000)
* Lipo Battery
	* [Amazon](https://amzn.to/3BOCNZH)
* Wire
	* [Amazon](https://amzn.to/3RiXVNh)
* Usb-C Ends
	* [Amazon](https://amzn.to/3SHZcym) 
* Usb-Micro Ends
	* [Amazon](https://amzn.to/3xZ4yxv)
	
* 4x m2 screws- 6mm
* 6x m2.5 screws- 8mm
* 3d Printed Parts

## Instructions

This build proceeds in 4 steps.

1. Print the case.
2. Make the keyboard.
3. Make the usb cables.
4. Connect it up!

The most difficult part of this build is making the usb cables. This does not require special soldering skills, but you should be comfortable soldering. A *third hand* is highly recommended. 

### Keyboard Build

The QAZ build is no different than building a QAZ as a normal keyboard. So, you can follow the steps available here: [CBKBD](https://docs.cbkbd.com/build-guides/qaz.html)

### The USB Cables

You need to make 3 cables. The first is a usb micro to usb micro OTG cable that connects the keyboard to the Banana Pi. The second is a usb c to usb micro power-only cable that connects the Banana Pi to the Ampripper 3000 usb c output. The third is a half cable with two bare wires on one end and a usb micro on the other to connect the 5v and Ground pads of the amp ripper to the usb micro in port of the screen. 
