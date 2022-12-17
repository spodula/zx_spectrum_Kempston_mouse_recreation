# zx_spectrum_Kempston_mouse_recreation
This is a copy of the classic Kempston mouse interface re-designed to use Amiga mice.
it uses all the same components, just pinout of the mouse connector differs from the classic kempston mouse.
(So in the unlikely event you have an original kempston mouse, DO NOT plug it in)
I personally use an amiga Mouse adapter I got from Ebay with an old Dell Optical mouse. This seems to work fine. 

Gerbers files are complete, and you should just be able to zip them up and send them straight to your PCB manafacturer of your choice. 

All of this was done from the Schematics available at: 
Kio at https://k1.spdns.de/Vintage/Sinclair/82/Peripherals/Mouse%20Interfaces/Kempston%20Mouse%20Interface/
My additions are:
* support for 3 button mice
* Re-arrange pinout so its compatable with the Amiga mouse. 

Parts required: 
74LS191 x4
74LS257 x2
74LS138
74LS00
74LS1235
10nf capacitor x2
100nf capacitors x9
PCB mount DB9 connector.
Edge connector x1 (If required)

Note, the jumpers J2,3,4,5 are there because i wasnt sure of the X1/X2 Y1/Y2 order. 
Now i know, you can just jumper the squared pins off (technically Pins 2/3), so the next version probably wont have them. 
(look at the terrible photos in the folder)

No licence on this board, use it, manafacture it, sell it, fart in its general direction, have fun with it..
If you do modify it, be sure to credit Kio at the above URL. 
