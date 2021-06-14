# Automatic Plant Irrigation System
## Aim:
This project aims to water plants automatically without any human interference 

## Block Diagram of Automatic Plant Irrigation System:
![image](https://user-images.githubusercontent.com/85859889/121845614-5899c300-cd03-11eb-9135-d872daf4e6a3.png)


## Working Principle
 * Concept in this circuit is. soil have high resistance when it is dry and has very low resistance when it is wet.
 * By using this concept we will make the system work. We insert two probes in the soil in such a way that that they will conduct when the soil is wet and they will not conduct when the soil is dry. So, when the probes do not conduct, system will automatically detect this condition with the help of HEX inverter which will become high when the input is low.
 * HEX inverter will trigger the NE555 Timer and this NE555 timer will trigger another NE555 which is connected to the output of first NE555. Now the second NE555 which is configured as astable multivibrator will help to switch on the Electric valve and as result, it will allow the water to flow to the soil.
 * When the water wet the soil, probes will again conduct and make the output of 7404 low which will make the first NE555 to low and drive remaining circuit to low. So, automatically it will switch off the valve.




 
