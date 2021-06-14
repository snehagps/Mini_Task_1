# Sun Tracking Solar Panel:

# Aim :
This project aims to make a Sun Tracking Solar Panel circuit which will track the Sun and position the solar panels accordingly. 

# Working Principle:
The Sun tracking solar panel consists of two LDRs, solar panel and a servo motor and ATmega328 Micro controller. Two light dependent resistors are arranged on the edges of the solar panel. Light dependent resistors produce low resistance when light falls on them. The servo motor connected to the panel rotates the panel in the direction of Sun. Panel is arranged in such a way that light on two LDRs is compared and panel is rotated towards LDR which have high intensity i.e. low resistance compared to other. Servo motor rotates the panel at certain angle.
When the intensity of the light falling on right LDR is more, panel slowly moves towards right and if intensity on the left LDR is more, panel slowly moves towards left. In the noon time, Sun is ahead and intensity of light on both the panels is same. In such cases, panel is constant and there is no rotation.

![solar](https://user-images.githubusercontent.com/85859889/121843136-5a618780-ccff-11eb-8dc1-3e260f54f41c.gif)

# Circuit Diagram 
![image](https://user-images.githubusercontent.com/85859889/121843071-369e4180-ccff-11eb-8d52-6ee307ed3a10.png)
