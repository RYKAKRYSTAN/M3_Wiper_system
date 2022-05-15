
## INTRODUCTION:
A windscreen wiper, windshield wiper is a device used to remove rain, snow, ice, washer fluid, water or debris from a vehicle's front window. Almost all motor vehicles, including cars, trucks, buses, train locomotives, and watercraft with a cabin and some aircraft are equipped with one or more such wipers, which are usually a legal requirement. A wiper generally consists of a metal arm one end pivots, the other end has a long rubber blade attached to it. The arm is powered by a motor, often an electric motor, although pneumatic power is also used for some vehicles. The blade is swung back and forth over the glass, pushing water, other precipitation, or any other impediments to visibility, from its surface. On vehicles made after 1969, the speed is normally adjustable, with several continuous speeds, and often one or more intermittent settings. On some vehicles, a windscreen washer system is also used to improve and expand the function of the wiper to dry or icy conditions. This system sprays water, or an antifreeze window washer fluid, at the windscreen using several well-positioned nozzles. This system helps remove dirt or dust from the windscreen when it is used in concert with the wiper blades. When antifreeze washer fluid is used, it can help the wipers remove snow or ice. For these types of winter conditions, some vehicles have additional heaters aimed at the windows, embedded heating wires in the glass in the wiper blade; these defroster systems can melt ice or help to keep snow and ice from building up on the windscreen.



## WORKING PROCESS

*   The RED LED is considered for the ACC position. Once the push button is pressed for 2 seconds, the RED LED keeps continuously glowing until the stop of the engine signifying the engine condition to be turned ON.
*   On press of the user input push button, the other three Blue, Green and Orange LEDs come ON one at a time with the set frequency. The frequency changes on every alternate key press, 3 frequency levels with 1, 4 and 8 Hz.
*   The LED glow pattern stops on the 4th press; the wiper action starts with the next press.
*   If the push button is pressed for 2 seconds continuously, the RED light goes off and the pattern stops bringing it to default position which signifies the engine is turned OFF.

## SWOT ANALYSIS

## Strength
*   The wiper comes back to default position even if stooped in the middle
*   Safety for the driver as well as the passengers in the vehicle
*   Clear Visibility to the Driver for neat ride.

## Weakness
*   The total cost of the wiper system is high if implemented in real-time.
*   The major disadvantage is that STM32 contains only one button for all the operation
*   User has to undergo a sequence to acquire desired result and can't attain his result directly with the press of the button.

## Opportunities
*   Rain sensing and automatic operation can be implemented as further enhancement.

## Threats
*   Replacing the board is not possible if it malfunctions.
*   Can't have more functions as the functionality of the board is very basic.

## Components Used

## Stm32

The STM32 family of 32-bit microcontrollers based on the Arm® Cortex®-M processor is designed to offer new degrees of freedom to MCU users. It offers products combining very high performance, real-time capabilities, digital signal processing, low-power / low-voltage operation, and connectivity, while maintaining full integration and ease of development.

![image](https://user-images.githubusercontent.com/102678112/167770911-b81487e4-ff98-461d-ad48-6cf34fb3f297.png)

## Servo Motor

A servomotor is a rotary actuator or linear actuator that allows for precise control of angular or linear position, velocity and acceleration. It consists of a suitable motor coupled to a sensor for position feedback.

## Resistors

A resistor is a passive two-terminal electrical component that implements electrical resistance as a circuit element. In electronic circuits, resistors are used to reduce current flow.

## Capacitor

A capacitor is a device that stores electrical energy in an electric field. It is a passive electronic component with two terminals. The effect of a capacitor is known as capacitance.

## LED's

A light-emitting diode is a semiconductor light source that emits light when current flows through it. Electrons in the semiconductor recombine with electron holes, releasing energy in the form of photons.

## Cables and Connector

A cable, also known as a cord, plug, or connector transmits power or data between devices or positions, which is covered in plastic by one or more wires.

## Push Button

A push-button or simply button is a simple switch mechanism to control some aspect of a machine or a process. Buttons are typically made out of hard material, usually plastic or metal. 

## High Level Requirements

| ID | Description | Status |
|----|--------------|-------|
| HLR01 | Detecting rainfall and active automobile rain wiper | Implemented |
| HLR02 | It operate manually | Implemented |
| HLR03 | Displaying the information in led | Implemented |

## Low Level Requirements

| ID | Description | Status |
|----|--------------|--------|
| LLR01 | It work functionally according to outside water | Implemented |
| LLR02 | Consume less power | Implemented |



## 4W's and 1H
## Who :
Used by drivers to get visiblity while driving.

## What :
Wiper system to clear snow ,dust,and water.

## When :
used while driving

## Where :
Used in automobiles

## How :
It is activated by switching the wiper button.
