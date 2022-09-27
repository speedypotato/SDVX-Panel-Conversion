# SDVX-Panel-Conversion
Turn an arcade Sound Voltex panel into a controller.

Requires a 1x2ft laser cutter, a 3d printer, and an assortment of m3 and m4 nuts and bolts.  And rubber feet.  And some more stuff.

![Wireframe](CAD/sdvx_ac/asm.png)

issues:  
- arduino holes didn't exactly line up, i just screwed in 2 screws diagonally and called it a day
- the m3x20 screws may fall out.  the corner brackets seem to do a good enough job,  can super glue m3 washers to make the m3x20 screws stay.

requires:  
- m3 mounting tape for arduino
- m3x6 arduino
- m3x20 edges
- m3x16 corner brackets
- m4x12 panel to box mount
- m3 nuts
- m4 nuts
- m3 washers
- m4 washers
- m4xsomething nuts to mount arcade panel to box
- m4 screwable rubber feet.  I got these https://www.mcmaster.com/8884T21
- top screws.  got them from a friend, they look like m4 low/slim profile of some sort.  m4x16 or something.

Assembly:  
- Note: I recommend doing a washer wherever a screw head touches wood or a 3d print.
- screw together box sides
- screw in corner pieces
- glue usb c - micro b extender into the usb holder
- screw in usb holder
- screw in front and back 3d printed mounts to box, don't forget to add nuts to all 3 points
- screw in panel
- mount arduino to plastic holder, apply 3m tape to holder.
- create wiring harness or just use dupont breadboard extenders and plug it directly into the connector using the wiring guide.  I recommend grouping all the - and COM to ground, except L/R Pot -, which get their own dedicated wire to ground
- assuming you've wired up arduino, plug in the micro usb adapter, peel off other side of 3m tape and mount it inside.  for me, i did it in the top left corner(looking at the top of the panel)
- mount feet to the bottom panel
- screw in the bottom panel

Setup https://github.com/veroxzik/arduino-konami-spoof (C:\Program Files (x86)\Arduino\hardware for me) and flash SkogaVoltex

This work is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.

My build, including extras:  
dupont	7.3  
ws2812b	8.26  
panel	63.51  
shipping	69.5  
arduino	14.99  
usb c to micro b	1.915  
wood	8.47  
screws	15.89  
feet	3.18  
3d prints	5  
jst	0  
wire	1  
torque limiter	44  
yuan leds	11.01  
usb c cable	1  
knobs	19.98 
3m tape 5 

Total: 280.005