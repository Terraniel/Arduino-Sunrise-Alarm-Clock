# Arduino-Sunrise-Alarm-Clock

Creating a LED color changing sunrise/sunset 
clock using an arduino Uno, a ds3231 rtc, and
rgb LEDs (or a mix of red, 2.7k and 5k if the
rgbs are too dim). Transistor driving the 
LEDs via PWM with separate power supply.

When choosing rgb LEDs, make sure to match
common cathode or common anode with matching
P-channel or N-channel MOSFETs respectively.
