# Smart-Home-Security-System-2.0
The project was updated and currently utilizes the Raspberry Pi GUI with the Arduino to control hardware components like sensors to utilize basic home security system that identify hazards like force entry, fire, and flood.

## Project Description
The Raspberry and the Arduino will be communicating to each other using Serial Communication. Serial Communication is a way to transfer data. This will allow you to communicate between 2 boards. The physical connection will be handled through a USB connector.

The smart home security system will consist of three sub-parts, the detection of intruder with smart locks and keyless entry, fire detection, and flood detection. 
In intruder detection and keyless entry composes of smart locks and motion sensors. This function will also give the user the ability to have keyless entry due to its feature of using PIN code and unique card/tag for entry access. The sensors like the PIR sensors and Reed switch are only enabled if the system is activated. The smart door lock will always be enabled, with or without the system being activated.

Other smart features like fire detection and flood detection are also included in the features of this project. The functions of these sensors are straight forward, they detect fire and water in the area. These sensors are always activated whether the system is enabled or disabled. The system can just be disabled by entering the correct pin. You can also enable and disable specific sensors through the Raspberry Pi GUI. This will also serve as the monitoring of sensors that are triggered using their data that is been passed from the Arduino.

&nbsp;
## The GUI
The GUI composes of the following: Door controls, Security System controls, Lights control, Sensor Status, and serial monitor text pad. The GUI can have two-way controls in the Door, Security System and Lights control. 

They have a very distinguishable appearance if they are enabled or disabled. The serial monitor pad has the widest area in the GUI, it focuses on the prompts from the Arduino to the Raspberry Pi, it has a scrollable interface for scrolling multiple lines of text and it also has a clear button for removing the contents of the serial monitor.

&nbsp;
![image](https://github.com/user-attachments/assets/8d7410c3-f503-405c-884f-06dd0c1d1728)

&nbsp;
## Findings, Recommendations and Conclusion:
During the creation of the protype, working with a lot of sensors are very tedious and a long process, restrictions like the speed of the Raspberry Pi to process all the multitasking operations like opening both the Arduino and the Thonny IDE at the same time while uploading and debugging the codes in both Arduino and Raspberry Pi. Connections should also be considered, making sure all end-to-end connections are aligned to each other. The other thing that should be considered is the power connections, both boards need an external source of power like wall outlet/socket, this is due to the amount of the sensors being used at the same time, and also sending serial connections in between the boards may result to low voltage.

The result of executing the command from Raspberry Pi to Arduino is very responsive compare to using the Arduino to toggle features in the prototype. It also responds immediately in sending serial data for the monitoring of the responses. For recommendation, it is recommended to utilize more features of the Raspberry Pi in controlling the Arduino. It is shown in the results that both boards are so responsive in communicating between each other, maybe more advance additional features can be added to the prototype like voice commands, can be controlled remotely or maybe things like adding camera and more lights to control would be the best upgrade for the system.

In conclusion, the protype works perfectly and is very compatible to each other, from controlling different features in the system, to monitoring data that is been passed from one board to another, it can still offer more features that will not just limit both boards from just passing serial connections to each other. More complex features can be added to the system with different combinations and different approach. It just showed the basic capabilities of using both boards at the same time and adding more to it will just expand its capabilities.
