#     Group Members with Enrollments and Branch:       
Teghdeep Kapoor 
Tanya Pandhi 
Divyam Shrivastava 
	Specification: 
 
#   Title. Hand Gestured Controlled VLC Player...
 
 #    Field of Invention of project. The Technology is based on Tensor Flow Technique...
	 
	Background: The concept behind the project is very simple. We will place two Ultrasonic (US) sensors on top of our monitor and will read the distance between the monitor and our hand using Arduino, based on this value of distance we will perform certain actions. To perform actions on our computer we use Python pyautogui library. The commands from Arduino are sent to the computer through serial port (USB). This data will be then read by python which is running on the computer and based on the read data an action will be performed 

#  Summary
Recently Gesture controlled Laptops or computers are getting very famous. This technique is called Leap motion which enables us to control certain functions on our computer/Laptop by simply waving our hand in front of it. It is very cool and fun to do it, but these laptops are really priced very high. So in this project let us try building our own Gesture control Laptop/Computer by combining the Power of Arduino and Python 

# Brief Description of the circuit diagram used in the project that is different from the existing one( no direct copy and past)
Detailed Description and Preferred Embodiment (that is changes in your work from the other existing work)
Recently Gesture controlled Laptops or computers are getting very famous. This technique is called Leap motion which enables us to control certain functions on our computer/Laptop by simply waving our hand in front of it. It is very cool and fun to do it, but these laptops are really priced very high. So in this project let us try building our own Gesture control Laptop/Computer by combining the Power of Arduino and Python. 
	
Definitions of each components of the project
 
A. Arduino: Arduino is an open-source hardware and software company, project and user community that designs and manufactures single-board microcontrollers and microcontroller kits for building digital devices. 
B.  UltraSonic sensor-:  Ultrasonic transducers or ultrasonic sensors are a type of acoustic sensor divided into three broad categories: transmitters, receivers and transceivers. Transmitters convert electrical signals into ultrasound, receivers convert ultrasound into electrical signals, and transceivers can both transmit and receive ultrasound 
C. LCD Screen: A liquid-crystal display (LCD) is a flat-panel display or other electronically modulated optical device that uses the light-modulating properties of liquid crystals 

#   Claims

 
   What is Claimed is:
1	A realtime arduino based hand gestured media player controler comprising: 
2	a real time distance calculator 
3	performing keyboard actions.

  Here are some different claim flavors from the claim buffet: 
1	Apparatus Claim. 
2	"A computer system comprising of the circuit of arduino UNO , 2 ultrasonic sensors and lcd screen using jump wires." 
3	Component Apparatus Claims. 
4	A circuit comprising of an Arduino UNO , 2 ultrasonic sensors, lcd screen. All are conneted using jump wires.
5	A computer system comprising of a circuit of arduino UNO , 2 ultasonic sensors and a lcd screen using jump wires.
 
	#Method Claim. 
7	We conneted the arduino UNO with the 2 ultrasonic sensors using the jump wires.
8	Then we conneted the lcd screen to the above circuit.
9	We wrote the code in C++ in the arduino software .
10	We wrote the front end code in python and used Python pyautogui to perform actions on our computer.
11	The commands from the arduino are sent to the computer through serial port(USB).
12	The distance measured by the ultrasonic sensors will be read by python which would be running on the computer and based on the the read data an action will be performed.
13	Product by Process Claim. 	
14	Computer Readable Medium (Beauregard) claim. 
15 Means-Plus-Function / Step-Plus-Function Claims.
 
#	General Claiming Notes
Describe invention: We have placed two Ultrasonic (US) sensors on top of our monitor which will read the distance between the monitor and our hand using Arduino, based on this value of distance we would perform certain actions. To perform actions on our computer we would use Python pyautogui library. The commands from Arduino are sent to the computer through serial port (USB). This data will be then read by python which is running on the computer and based on the read data an action will be performed.We have resticted it to controlling th VLC player as of now. But we can extend it to controlling the windows. 
Programming Language:This project is written in C++ in the arduino software and the distance information from Arduino is collected by a Python Program and a special library called PyAutoGUI which will convert the data into keyboard click actions. 
Cost of the project : arduino uno – Rs 1500
                                   ultrasonic sensors (Qty-2 ) - Rs  230 
                                  LCD screen -  Rs 235  

# Damages(disadvantages or limitation or restriction):
1.	Limitted to keyboard key shortcuts.
2.	Limitted to the sentivity of ultrasonic sensors.


#	Abstract
A system for arduino based hand gesture controlled media player is disclosed. The system  reads the distance between the monitor and our hand using Arduino, based on this value of distance it performs certain actions. 
 Photographs of the team members
   
