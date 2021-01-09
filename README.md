# MP2359, LP5030 and TCA9544A Breakout Board

This breakout board allows you to test an LP5030 LED driver, with a TCA9544A i2c mux/hub, being powered by a MP2359 buck power converter. The board was design to be powered by +12V, but should work with anything from +5 to +12. Place a jumper across the 3.3V 2-pin header to enable the use of the onboard power supply. Or, supply 3.3V directly to the pin marked 3.3V to bypass the onboard power supply. 

I built this board because of a larger project where I wanted to use these three components. However, having not used them before in a design and without access to well priced evaluation board, I decided to make my own. TI sells an eval board for the LP5030 but it's $100+ which is ridiculous. There is a well priced board available to eval the MP2359 but it's rather huge. And so, I decided to build my own. 

The gerber and assembly files included herein have been successfully used with JLCPCB and their SMT Assembly surface to order these boards with everything but the LP5030, TCA9544A and headers already assembled. Those, you'll need to take care of yourself. 

If you have any questions you can find me on Twitter @scotchandcode, and streaming regularly at twitch.tv/jdotw. 

Datasheet links:

MP2359: https://www.monolithicpower.com/en/mp2359.html

LP5030: https://www.ti.com/product/LP5030

TCA9544A: https://www.ti.com/product/TCA9544A

Enjoy! 

-jw