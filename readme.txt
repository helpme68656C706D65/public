If you have been looking for a degree symbol in the Adafruit GFXfont collection you may have seen the 
post below by J-M-L Jackson where he beautifully goes through the steps to replace anything with anything.

https://forum.arduino.cc/t/adding-glyphs-to-adafruit-gfx-builtin-font/689424/10 

These 2 files are my interpretation of his suggestion in replacing the ~ for a DIY degree:
FreeSans18pt7b.h
FreeSansBold18pt7b.h

To use, insert a ~ in you code where you want a degree symbol, like:
display.print(" ~F");

To install just swap out you existing library files for these. Keep the old in case you need a ~.
.../Arduino/libraries/Adafruit_GFX_Library/Fonts

Note: The FreeSans18pt7b.h did not exactly follow the outline and had a couple of extra bytes at the end

Special thanks to Adafruit for making all this possible in the first place!
 
 
