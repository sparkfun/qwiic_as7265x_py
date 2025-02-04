# Sparkfun AS7265X Examples Reference
Below is a brief summary of each of the example programs included in this repository. To report a bug in any of these examples or to request a new feature or example [submit an issue in our GitHub issues.](https://github.com/sparkfun/qwiic_as7265x_py/issues). 

NOTE: Any numbering of examples is to retain consistency with the Arduino library from which this was ported. 

## Qwiic As7265X Ex1 Basic
This example takes all 18 readings, 372nm to 966nm, over I2C and outputs
 them to the serial port.

## Qwiic As7265X Ex2 Leds
This example takes all 18 readings and blinks the illumination LEDs 
 as it goes. We recommend you point the Triad away from your eyes, the LEDs are *bright*.

## Qwiic As7265X Ex3 Settings
This example shows how to change the gain, mode, and LED drive currents

## Qwiic As7265X Ex4 Read Raw
This example shows how to output the raw sensor values. This is probably never needed since the 
 calibrated values are tuned to each sensor. But it does run faster (2 bytes per channel instead of 4)

## Qwiic As7265X Ex5 Max Read Rate
This example shows how to setup the sensor for max, calibrated read rate.
 Printing floats is the greatest bottleneck so we increase it to 115200.

## Qwiic As7265X Ex6 Read Temp
This example shows how to read the temperature of the ICs

## Qwiic As7265X Ex7 Get Version
This example shows how to read the temperature of the ICs


