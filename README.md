# Self-Driving-RC-Car

Project resources: It include hardware as well as software resources. Hardware resources include following resources:

1-Arudnio:
Arduino is an open-source electronics platform based on easy-to-use hardware and software. Arduino boards are able to read inputs - light on a sensor, a finger on a button, or a Twitter message - and turn it into an output - activating a motor, turning on an LED, publishing something online.

2-HC-05 Bluetooth Module: 
HC-05 module is used Bluetooth communication.  There are several different versions of this this module but I recommend the one that comes on a breakout board because in that way it’s much easier to be connected. The HC-05 module is a Bluetooth SPP (Serial Port Protocol) module, which means it communicates with the Arduino via the Serial Communication.
			
3- WIFI module ES8299:
ESP8266 is Wi-Fi enabled system on chip (SoC) module developed by Espresso system. It is mostly used for development of IoT (Internet of Things) embedded applications.
ESP8266 comes with capabilities of
•	2.4 GHz Wi-Fi (802.11 b/g/n, supporting WPA/WPA2),
•	general-purpose input/output (16 GPIO),
•	Inter-Integrated Circuit (I²C) serial communication protocol,
•	analogue-to-digital conversion (10-bit ADC)
•	Serial Peripheral Interface (SPI) serial communication protocol,
•	I²S (Inter-IC Sound) interfaces with DMA (Direct Memory Access) (sharing pins with GPIO),
•	UART (on dedicated pins, plus a transmit-only UART can be enabled on GPIO2), and
•	pulse-width modulation (PWM)

4-Rasberry pi model B+:
Raspberry Pi 3 Model B+ features a 1.4GHz 64-bit quad-core ARM Cortex-A53 CPU Broadcom processor. This single board computer provides dual-band 2.4GHz and 5GHz wireless LAN and 
Bluetooth 4.2/BLE. The Raspberry Pi 3 Model B+ offers faster Ethernet (Gigabit Ethernet over USB 2.0) and Power-over-Ethernet (PoE) capability via separate PoE HAT. 
This single board computer also provides improved Reboot Execution Environment (PXE) network, USB mass-storage booting, and improved thermal management.

5-Connecting cables: male-to male, male to female

6-Ultrasonic sensor: -
As the name indicates, ultrasonic sensors measure distance by using ultrasonic waves.
The sensor head emits an ultrasonic wave and receives the wave reflected back from the target. 
Ultrasonic Sensors measure the distance to the target by measuring the time between the emission and reception.

Thanks to Zheng Wang, for his beaitiful blog on RC Car- https://zhengludwig.wordpress.com/projects/self-driving-rc-car/


A RC car is designed that detects various object and gives an estimate if collision can occur. 
The car is being developed using motors, Arduino Uno, Raspberry Pi Model B+, Bluetooth HC05, Wi-Fi ES8299,sensors such as ultrasonic sensor and camera,
and an Android app. 
The raspberry pi model takes the input from the ultrasonic sensor and the camera. 
These inputs are sent to the computer where the processing takes place, A trained model detected the safe distance and image processing is used to detect and 
classify the objects. This further interpreted result is given to Arduino Uno over Wi-Fi. The Wi-Fi model is finally used to brake the RC car. 


