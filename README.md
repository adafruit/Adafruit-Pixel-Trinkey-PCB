## Adafruit Pixel Trinkey - USB Key for NeoPixel / DotStar Driving PCB

<a href="http://www.adafruit.com/products/5953"><img src="assets/5953.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit Pixel Trinkey - USB Key for NeoPixel / DotStar Driving. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5953

### Description

Blast-off to Pixel Planet with the Adafruit Pixel Trinkey, a co-pilot for those who like to shine bright. This little microcontroller board plugs into your computer's USB port and can drive tons of NeoPixel (SK6812, WS2812, etc) or DotStar (e.g. AP102) LEDs without having to do any soldering or complex wiring. The SAMD21 chip on board has 32KB of SRAM, that means thousands of pixels! All from the convenience of your computer with support for Arduino, CircuitPython or Windows 11's built-in Dynamic Light Control

NeoPixels and Dotstars are 'smart' LEDs that can display 24-bit color, they're bright, colorful, individually-addressable, and come in dozens of different shapes: from flexible strips, to individual dots, to rings, and beyond. However, you need a microcontroller to drive them: something that can generate the exact pattern of data that they desire to set each pixel color. Normally folks use something like an Arduino, which will work just fine, but sometimes needs level shifting or separate power, or just has gangly wires.

This board contains the microcontroller, plus level shifting in a compact package that pokes out an inch from your computer USB port. On the end is a screw terminal block that can accept stranded or solid-core wires 26 to 18 AWG with four ports: 5V power, Data, Clock and Ground. If you're using DotStars, wire up the 'input' side of your LEDs to the 4 pads. If you're using NeoPixels, you can have one or two strands, where the second strand uses the Clock pin as the data generator.

Computer USB ports can provide up to 1A which we've found will drive about 150 pixels without difficulty as long as they are not all on full white at max brightness. If you need to drive a ton more pixels, simply disconnect the 5V power wire and use an external power source - just make sure that the ground wire from the external power is connected to the ground of the Trinkey+pixels. You can monitor the USB 5V line voltage thanks to a resistor divider on the board.

If you want to add additional circuitry, such as an Infrared remote input, or potentiometer, or a button, there's a JST-SH 3-pin connector on board. Use a JST SH 3-pin cable to access the 3V, ground and pin D4. There's also a separate mini NeoPixel for status feedback if desired.

Features:

* ATSAMD21E18 32-bit Cortex M0+ - 48 MHz 32-bit processor with 256KB Flash and 32 KB RAM
* Native USB supported by every OS - can be used in Arduino or CircuitPython as a USB serial console, MIDI, Keyboard/Mouse HID, and even a little disk drive for storing Python scripts
* Can be used with Arduino IDE or CircuitPython
* 0.1" / 2.54mm Terminal Blocks - Attach LEDs with no soldering! Just use a common screwdriver.
* On-board RGB NeoPixel LED
* JST SH 3-pin compatible connector - For extra hardware connectivity
* Reset switch to start your project code over or enter bootloader mode
* Open Source Hardware so you have full control over your LEDs

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
