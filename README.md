# IoT-Based-IV-Bag-Monitoring-System
🩺 IoT-Based IV Bag Monitoring System
--------------------------------------------------------------------------------
This IoT-based project automates the monitoring of intravenous (IV) fluid levels to enhance patient safety and reduce manual errors in hospitals. Using an ESP8266 microcontroller with a load cell and HX711 amplifier, the system measures the weight of the IV bag and displays it in real-time on a 16×2 LCD screen. A PCF8574 I2C expander simplifies wiring, while the Blynk IoT platform enables healthcare providers to monitor the bag status remotely through a smartphone app.

The system features local alerts using LED indicators for both low-level and full-level detection, ensuring caregivers are notified when a bag needs to be replaced or has been refilled. This improves efficiency and response time, minimizing the risk of air embolism or fluid interruption.


------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------



Key Features
-------------------------------------------------------------------------------------------------------------------
-Real-time IV fluid monitoring

-Alerts for both empty and full bag status

-Remote notifications via Blynk app

-User-friendly LCD display

-Wireless data transfer with ESP8266

-Cost-effective and easy to integrate


-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Block Diagram
-----------------------------------------------------------------------------------------------------------------------------------------

![BLOCK DIAGRAM](https://github.com/user-attachments/assets/3f742135-c8ee-4264-9979-b71b1a1630a4)



--------------------------------------------------------------------------


Components Required
----------------------------------------------------------------------------------------

 Software Requirements
 --------
 -Blynk App
 
 -Arduino ID

 Hardware Requirements
 ------------------
-ESP8266 Wi-Fi module – for wireless data transfer

-HX711 amplifier – to amplify the load cell signal

-10 kg load cell – to measure IV bag weight

-PCF8574 I2C expander – to interface the LCD with fewer pins

-16×2 LCD display – to show real-time weight

-LED indicators – to signal empty or full bag conditions

-5V DC power supply – to power the circuit

-Connecting wires and resistors – for circuit assembly


-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Flowchart
-------------------------------------------------------------------------------------------------------------------------------------------

![FLOWCHART - Copy](https://github.com/user-attachments/assets/4ca13bf7-be30-4b13-a046-9a7523181d1b)




------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


 Hardware Design
 ---------------------------------------------------------

![IV BAG](https://github.com/user-attachments/assets/56d47d3f-a5ae-4665-b670-4cf552717749)


 Figure: Hardware desig


----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


 Result
 ---------------------------------------------------------------
 The IoT-based IV Bag Monitoring System was successfully designed and tested.The system utilizes an ESP8266 microcontroller, a 16x2 LCD, a HX711 load cellamplifier, and a 10kg load cell to monitor the weight
 of  the IV bag. The weight data is continuously monitored and displayed on the LCD for real-time feedback. Whenthe IV bag’s fluid level falls below the predefined threshold, the system triggers analert via
 the Blynk mobile app, notifying healthcare personnel about the situation.

Figure: Output

![HARDWARE 1 (2)](https://github.com/user-attachments/assets/c8bb96b8-6330-4733-bcfd-a896e738db1a)


![HARDWARE 3](https://github.com/user-attachments/assets/154e88c2-c791-4259-9918-53d5090acc3b)


![NOTIFICATION](https://github.com/user-attachments/assets/f05d4f4a-76b1-4470-8ecf-1c7dcea736d6)


 Overall, this system holds great potential for improving patient safety by enhancingiV monitoring in healthcare facilities. It also serves as a prototype for future advancements in IoT-based medical solutions.


---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


 Applications
---------------------------------------------------------------------------
-Hospitals and clinics for continuous IV monitoring

-Rural or remote healthcare centers with limited staff

-Emergency medical camps or disaster relief situations

-Telemedicine and remote patient monitoring systems

-Intensive Care Units (ICUs) for critical patient observation



-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Future Scope
------------------------------------------------------------------------------------------------------
-Predictive analytics for fluid demand

-Integration with hospital management systems

-Smart flow control


-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Contributors
---------------------------------------------------------------------------------------------------------------------------------
Ajmal T A

Arya Sasikumar

Gowthami S 

Mahitha M

Guided by: Ms. Swetha C, Department of ECE, Ahalia School of Engineering and Technology


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------  


Project Status: Completed ✅
