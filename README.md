# LED Sequence Control

- **Setup**: 
  - Serial communication is initialized at a baud rate of 9600.
  - Pin modes for LED1, LED2, and LED3 are set as output pins.
  - Initial states of the LEDs are set to LOW.

- **Main Loop**: 
  - LED1 is turned ON for 2 seconds, then OFF for a short delay.
  - LED2 is turned ON for 500 milliseconds, then OFF for a short delay.
  - LED3 is turned ON for 2 seconds, then OFF for a short delay.
  - This sequence repeats indefinitely.

This code creates a sequence where each LED is illuminated in turn with varying durations, providing a visual effect controlled by the Arduino board.

