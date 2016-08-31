This here Arduino code is to be used in this here kind of application:
(instructables link)
Points to note:
-If you do not intend to use an LCD screen and a 5-pin rotary encoder with a push button
you better find some other code
-The relay modules I currently use for the installation "click" when they get the signal 
LOW. This affects the light, air humidifier and irrigation.
-The soil humidity sensor that the code currently supports is the simplest of its kind, a 
2-pin one.
Some things I would work on if I had more time to spend on this:
-A light dependant resistor to keep checking the lights and warn the user if they don't 
work as usual. With this should come a calibrating function similar to the Calibrate RHs
sensor.
-A flow rate sensor to do the same as above for the watering system.
-Add some slides on the LCD for possible manual control of outputs.
-Add data logging.
-Tidy up the code in the sense of making it more modular, and changing piles of 
if statements with the switch, and similar.