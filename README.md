# Breakdown-Displaying-System

I was assigned to develop and install the breakdown displaying system which is very essential to employees every minute. This system was introduced to display any breakdown or any size change that occurred on a machine. It has the ability to automatically real-time recordings on an excel sheet. This system was invented to use for all the machines in the CEAT Company. 

### The main objectives are: 
-	To give an idea about the system for employees and authorities  
-	To verify the functionality of the system  
-	To confirm whether there is an error or not 
-	To get an understanding of the maximum range of the system  
-	To increase the feasibility and accuracy of the use of wireless methods 
-	It reduces time-wasting by sending real-time notifications to relevant persons 

### Used components are: 
##### 1)	Arduino UNO  
   This is the used microcontroller for the system. Previously NRF 24LO1 was used and it was replaced using Arduino UNO. It transmits data as we want. Arduino UNO (Figure 39) is a low-cost, flexible, and easy use programmable open-source microcontroller. 
 Figure 39: Arduino UNO board 
##### 2)	ESP 8266 
This module was used as the solution for NRF 24LO1. This Wi-Fi Module has self-contained SOC an with integrated TCP/IP protocol stack that can give any microcontroller access to the Wi-Fi network. So, this module helps to send real-time data for the excel sheet. Figure 40 shows the Node MCU board which I used.
Figure 40: Node MCU board 
##### 3)	32×16 LED display  
This module was used as the display. It has 32 LEDs for each row and 12 LEDs for each column. This panel works as per the microcontroller outputs. The LED display is shown in Figure 41.
Figure 41: LED Display 
##### 4)	Buck Converter
This is an LM2596 DC-DC buck converter (Figure 42) step-down power module with a high-precision potentiometer, capable of driving a load up to 2A with high efficiency. 
Figure 42: Converter
##### 5)	SMPS 
SMPS (Figure 43) is an electronic power supply system that makes use of a switching regulator to transfer electrical power effectively. Like other power supplies, an SMPS transfers power from a DC or AC source to a DC load. 
Figure 43: SMPS
 
Receiver – Programming part (Figure 44):
 Figure 44: Receiver - programming

Transmitter – programming code (Figure 45-1, 45-2)











Figure 45-1: Transmitter- programming i 
Figure 45-2: Transmitter- programming ii 
Implemented circuit (Figure 46):
Figure 46: Implemented circuit

