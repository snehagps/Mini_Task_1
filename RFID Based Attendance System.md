# RFID Based Attendance System 
# Aim:

Attendance in colleges is generally paper based which may sometimes cause errors. Taking attendance manually consumes more time. So the aim of this project  is to make a attendance system which uses RFID technology to take attendance.

# Working Principle:  
RFID based attendance system consists of  
* RFID Reader  
*	RFID Tag  
*	LCD display   
*	microcontroller unit  

RFID can be interfaced to microcontroller through USART. Data is transferred from RFID cards to reader and from there to microcontroller.
Radio frequency technology is used in many applications. RFID tags are of two types – 1) Passive Tags and 2) Active Tags. Passive tags contain 13 digit number tag inbuilt in it, where as active tag is read/write tag i.e. one can read from the tag and write to the tag. This project uses passive tag.
In real time, one can issue active tags to the students, with their roll numbers as their tags. RFID reader contains a copper winding in it. This winding acts as an antenna.
When the tag is placed near the reader, due to the induced mutual inductance energy, data is transferred to reader. Reader then transfers data to the microntroller. Microcontroller checks for the data continuously, if any data is received, microcontroller compares the data in data base.If the tag is authenticated, microcontroller takes the attendance
Circuit Diagram :
 

