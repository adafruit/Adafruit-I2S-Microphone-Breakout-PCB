## Adafruit I2S Microphone Breakout PCB

<a href="http://www.adafruit.com/products/3421"><img src="assets/image.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit I2S Microphone Breakout. Format is EagleCAD schematic and board layout
* https://www.adafruit.com/products/3421

### Description

Listen to this good news - we now have a breakout board for a super tiny I2S MEMS microphone. Just like 'classic' electret microphones, MEMS mics can detect sound and convert it to voltage, but they're way smaller and thinner. This microphone doesn't even have analog out, its purely digital. The I2S is a small, low cost MEMS mic with a range of about 50Hz - 15KHz, good for just about all general audio recording/detection.

For many microcontrollers, adding audio input is easy with one of our analog microphone breakouts. But as you get to bigger and better microcontrollers and microcomputers, you'll find that you don't always have an analog input, or maybe you want to avoid the noise that can seep in with an analog mic system. Once you get past 8-bit micros, you will often find an I2S peripheral, that can take digital audio data in! That's where this I2S Microphone Breakout comes in.

Instead of an analog output, there are three digital pins: Clock, Data and Left-Right (Word Select) Clock. When connected to your microcontroller/computer, the 'I2S Master' will drive the clock and word-select pins at a high frequency and read out the data from the microphone. No analog conversion required!

The microphone is a single mono element. You can select whether you want it to be on the Left or Right channel by connecting the Select pin to power or ground. If you need stereo, pick up two microphones! You can set them up to be stereo by sharing the Clock, WS and Data lines but having one with Select to ground, and one with Select to high voltage.

This I2S MEMS microphone is bottom ported, so make sure you have the hole in the bottom facing out towards the sounds you want to read. It's a 1.6-3.6V max device only, so not for use with 5V logic (its really unlikely you'd have a 5V-logic device with I2S anyways). Many beginner microcontroller boards don't have I2S, so make sure its a supported interface before you try to wire it up! This microphone is best used with Cortex M-series chips like the Arduino Zero, Feather M0, or single-board computers like the Raspberry Pi.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. See license.txt for additional details.
