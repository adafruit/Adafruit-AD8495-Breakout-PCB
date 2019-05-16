# PCB files for Adafruit Analog K-Type Thermocouple Amplifier AD8495 Breakout

<a href="http://www.adafruit.com/products/1778"><img src="assets/image.jpg?raw=true" width="500px"></a>

Thermocouples are very sensitive, requiring a good amplifier with a cold-compensation reference. We have a couple digital thermocouple amplifiers in the shop already from Maxim. Now we're happy to introduce an excellent analog-output amplifier. This is a very simple sensor to use, and if your microcontroller has analog input capability, you'll be ready to go really fast!

The AD8495 K-type thermocouple amplifier from Analog Devices is so easy to use, we documented the whole thing on the back of the tiny PCB. Power the board with 3-18VDC and measure the output voltage on the OUT pin. You can easily convert the voltage to temperature with the following equation: Temperature = (Vout - 1.25) / 0.005 V. So for example, if the voltage is 1.5VDC, the temperature is (1.5 - 1.25) / 0.005 = 50¡C

Each order comes with a 2 pin terminal block (for connecting to the thermocouple), a fully assembled PCB with the AD8495 + TLVH431 1.25V precision voltage reference, and pin header (to plug into any breadboard or perfboard). [Goes great with our 1m K-type thermocouple (not included)](http://www.adafruit.com/products/270). Not for use with any other kind of thermocouple, K type only!

- Works with any K type thermocouple
- Will not work with any other kind of thermocouple other than K type
- Easy to use analog output
- Temp range with 5V power: -250¡C to +750¡C output (0 to 5VDC) as long as the thermocouple can handle that range
- Temp range with 3.3V power: -250¡C to +410¡C output (0 to 3.3VDC) as long as the thermocouple can handle that range

__Note:__ The terminal blocks included with your product may be blue or black.

## License

Adafruit invests time and resources providing this open source design, 
please support Adafruit and open-source hardware by purchasing 
products from Adafruit!

Designed by Limor Fried/Ladyada for Adafruit Industries.
Creative Commons Attribution, Share-Alike license, check license.txt for more information
All text above must be included in any redistribution
