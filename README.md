## Adafruit USB Type C Plug Breakout PCB

<a href="http://www.adafruit.com/products/5978"><img src="assets/5978.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit USB Type C Plug Breakout. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5978

### Description

Throw out all those Mini and Micro B USB cables you have in a plastic bin - the next generation of USB connectors is here with USB C! You've seen these connectors pop up on all sorts of devices, as the industry moves from micro B or lightning to the new standard. Well, at least until the next standard comes out

USB C features a symmetric/reversible connector, more data pins and higher current output capability. But, for most developers, the pin usage you know and love from older USB will work just fine. This breakout gives you all the basics you need and a resistor configuration that will make sure you get 5V power. We chose a plug that has a semi-through hole mounting configuration that seems fairly mechanically stable. That said, it will not survive purposeful bending the way a Type A would.

There's one 5.1K resistor on the CC1 pin, so if you plug this into a computer or power supply, the upstream port to provide 5V and up to 1.5A. Whether the upstream can supply that much current depends on what you're connecting to.

Unlike USB Type C sockets, the plug side purposefully does not use both sets of D+/D-/CC pins: that's how the host figures out which way the cable is plugged. So, when you connect to the pads on the breakout, know that you're going to be on the 'A' side. The socket on the other end should be tying the data lines together for you.

For most usages, you can just connect VBUS to your 5V input, GND to ground, and D+ and D- as you expect.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
