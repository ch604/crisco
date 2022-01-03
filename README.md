Crisco is a 20% chorded keyboard inspired by the butterstick, originally created by [Germ](https://github.com/germ) at [gboards.ca](gboards.ca). The Crisco is bigger than it's cousin, being promicro-based instead of SMD, and MX switch spaced. But, it boasts LED strip support and an OLED 128x32 display.

Many thanks also to the [cookpad-pad repo](https://github.com/cookpad/cookpad-pad/tree/master), which jump started the build.

download [the gerber](https://github.com/ch604/crisco/blob/main/gerbers/crisco-v0.1-gerbers.zip?raw=true)

BOM:
1x 128x32 SSD1306 OLED display (optional)
2x 4.7k resistors (needed for optional OLED display)
11 LEDs worth of WS2812B 60/m RGB LED strip (optional)
1x Arduino Pro Micro (or compatible)
20x 1N4148 through-hole or 1N4007 SMD diodes (or similar)
20x 5-pin MX switches
20x keycaps (technically optional)
6x rubber feet
capton tape or electrical tape

INSTRUCTIONS:

#solder the diodes D1 through D20 to the top side of the board (on top of the silk screen)
#solder the legs for the pro micro and the pro micro itself on the top side of the board, component side up, with the USB port to the top of the board. check the silk screen for proper pin orientation
#solder the resistors to R1 and R2
#solder the switches in place
#add some capton tape to the top of the pro micro
#solder the OLED screen on top of the pro micro with the pins to the bottom of the board. ground will be the square pad
#cut and solder the LED strip to the bottom of the board. ground is the square pad, and "Din" on the strip should go to the middle pin. keep the strip in place with some more capton tape
#apply rubber feet to the bottom of the board to keep it from moving around. if you added the LED strip, you will need some thicker feet
#flash the board
#show it off to your discord buddies
#get frustrated with the keymap
#put it in a drawer for a few months
#sell it on mech market
