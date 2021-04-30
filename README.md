# jetson-arduino-temp
Arduino + Jetson + a sensor + Azure = a whole lot of headahces

This is basically a hodgepodge of a bunch of other (smarter) people's code. My setup was as follows:

* SparkFun SHTC3 sensor:
    * Plugged into SCL, SDA, GND, and 3.3V of the Arduino (I'm using a Arduino Uno)
    * Original code pulled from Sparkfun:        https://github.com/sparkfun/SparkFun_SHTC3_Arduino_Library/blob/master/examples/Example1_BasicReadings/Example1_BasicReadings.ino
* Arduino was plugged into the Jetson's USB port
* Jetson was connected to Azure following the instructions for Microsoft's IoT lab: https://github.com/microsoft/iot-curriculum/tree/main/labs/iot/environment-monitor
  * The program for this portion was modified from step 3: https://github.com/microsoft/iot-curriculum/blob/main/labs/iot/environment-monitor/steps/set-up-pi.md
