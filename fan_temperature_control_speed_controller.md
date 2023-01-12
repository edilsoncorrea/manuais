# PWM fan speed control module Single 12V Temperature control speed controller 2-3 wire can be shut down temperature control speed controller Small size


IMAGEM 1


## Why do I need to use a governor?

In a conventional fan cooling system, the common practice is to directly supply power to the fan, regardless of the temperature of the system, as long as the fan is powered on, it will run at full speed.

## In fact, this approach is improper:

1. The fan is actually a mechanical operating device, running at the highest speed at any time, which will accelerate wear and shorten the life of the fan! 2. In most practical applications, when the temperature is not high, there is no need to run the fan, which will waste electrical energy and increase unnecessary wind noise!

## Scenes to be used:
This governor completely adopts industrial-grade technical solutions and is suitable for industrial control environments.

1. Energy-saving and noise-reduction of fans for outdoor chassis and cabinets
2. Energy saving and noise reduction of the fan in the computer room
3. Other fan temperature control and speed regulation applications

IMAGEM 2

IMAGEM 3

IMAGEM 4

The temperature probe matched with this module is made of 1% high precision thermistor and epoxy resin seal, which is waterproof and moisture-proof. The metal part of the probe is the temperature sensing point, and the length of the connecting wire is 50cm by default, and it can be extended with a wire! When using, fix the probe on the heating source.

## Instructions:
### 1. Wiring diagram

IMAGEM 5


### 2. This controller is designed as a combination of manual control and automatic temperature control:

1. It is purely manual when the temperature probe is not installed: single click/double click (the double click speed should not be too fast) to increase/decrease the gear position. Each time you change the gear position and continue to run for 20 seconds, the gear position will be automatically stored. Within 20 seconds, the No. 2 indicator light will flash rapidly (the temperature control is invalid at this time). When the flashing stops, the gear position has been stored. When in the position where it cannot continue to increase/decrease. the 3/1 indicator light will be on. 
To

2. Install a temperature probe: the manual speed adjustment is the initial low speed (bottom line speed). When the temperature exceeds the acceleration temperature, the fan speed will smoothly accelerate with the increase in temperature. When the temperature reaches or exceeds the sum of the acceleration temperature and the acceleration width (That is, the temperature at full speed), the fan is at full speed, the setting acceleration temperature and acceleration width parameters are detailed in the following setting diagram. The numbers 1 2 3 in the figure represent that the on (red) and off (white) states of the indicator lights on the board are displayed in binary order:

IMAGEM 6


During normal operation: Click the button to increase the bottom line output by 5%, and the double break button to decrease the bottom line output by 5%. After changing the value, run for 20 seconds. After the middle indicator light stops flashing rapidly, brake and save the parameters. Enter the temperature control setting by long pressing the button.

#### Temperature control setting status:
Accelerate temperature setting (slow flash) by single click double click to increase and decrease the value respectively, long press to enter the acceleration width setting. Acceleration width setting (fast flashing) also double click to change the value and long press to save and exit the temperature setting.

#### Note: 
If there is no operation for 20 seconds in the setting state, it will automatically exit the setting without saving the parameters.

### 3. Fan shutdown strategy setting:
First, turn off the power and remove the fan, press and hold the setting button to power on the controller, keep the setting button always pressed (about 3 seconds) until the three lights become double flashing at the same time, then release the button, the indicator light becomes a single When the light flashes double, it means entering the mode setting state. The controller is divided into three working modes, corresponding to the double flashing of No. 1, 2 and 3 indicator lights, which can be switched by short pressing the button. After setting, long press the button to save and exit the setting mode and automatically return to normal working state,

## The three working modes:
1. Does not shut down the output.
2. When the acceleration temperature is lower than 2 degrees Celsius, the output will be shut down.
3. When the acceleration temperature is lower than 5 degrees Celsins, the output will be shut down.

### For example: 
Set the acceleration temperature to 35 degrees Celsius, the acceleration width to 10 degrees Celsius, and the shutdown strategy mode 3 (shut down at 5 degrees Celsius below the acceleration temperature). After this setting, the fan will not rotate when the temperature is lower than 35 degrees when power is on. When the temperature rises to 35 degrees, the fan starts according to the manual setting. The temperature continues to rise, the speed slowly accelerates, and the fan is at full speed when it reaches or exceeds 15 degrees. When the temperature drops to between 35-30 degrees, the fan always runs at the manually set speed, and the fan stops rotating below 30 degrees.
Note that the fan shut down strategy is controlled in a hysteresis mode, which can effectively prevent the repeated switching of the fan near the critical point. For example, after the above setting, the temperature rises to 35 degrees to start the fan, and the temperature drops below 30 degrees to turn off the fan.

### Precautions for use:
Since most fans can run at low output but cannot start, when setting the minimum speed of the temperature control, you should first adjust to the lowest speed and stop the fan by hand, and then increase the output step by step until the fan starts normally. After the actual setting, do not lower than this position, otherwise the fan may not start at low speed.
