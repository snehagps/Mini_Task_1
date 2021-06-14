# Smart Garbage Segregation Dustbin Level Indicator System
## Aim:
The aim of this project is to design a garbage disposal system that uses multiple dustbins with a voice based system that speaks to the user each time he she stands before the dustbin.
## Working Principle:
The system makes use of a camera to detect presence if any person in front of the dustbin. If a person is detected, the system issues voice instructions to the user about throwing right garbage in the right bin. In case the dustbin is full it instructs the user to find another dustbin to throw garbage in.<br />
To develop this system we make use of a raspberry Pi controller. The controller is interfaced with a camera and a voice speaker for detection and communication. The controller gets dustbin level input using ultrasonic level sensors each having LED indicators interfaced to it. The level sensors are used to constantly feed the raspberry pi with bin levels.
The raspberry pi is also interfaced with a Wifi module to transmit the level data over the internet. The Level sensor panels are made to be easily mounted over any dustbin. This allows the system to be easily screwed over any dustbin for instant installation.
The data is transmitted over IOT to IOT gecko platform which displays the bin level data over internet. This indication can be used to alert the authorities that the garbage bins need to be emptied. Thus the system automates garbage segregation and level monitoring to help counter the garbage crisis using IOT.
