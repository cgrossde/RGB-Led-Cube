
# 4x4x4 RGB LED Cube

These are the schematics and the necessary code to build and control a 4x4x4 RGB LED Cube. It was a project of mine in early 2014 to get a better understanding of digital electronics. The design might not be perfect but I learned a lot along the way.

Beware there are some **minor changes missing** in the schematics which were applied after the board was already etched:

 - Added a diode for reverse polarity protection!!
 - Added a switch so the cube can be turned off
 - Power the Arduino only if the switch is on (e.g. connect 5V and GND after the switch with the Arduino)
 - This also makes sure that the Arduino does not try to power the whole circuit while programming it over USB 

Check out the image folder for pictures, my iPhone camera might not be the best camera to capture images of bright LEDs ;)

![The finished Product](Images/IMG_1353.JPG?raw=true)

![Bright red](Images/IMG_1852.JPG?raw=true)

Credits go to Kevin Darrah who inspired me to build this cube with his great Youtube videos and a code base to start programming it.