### Wild Fire Prediction Device


Wildfires are among the most destructive and unpredictable natural disasters. They lead to the loss of vast areas of forests, wildlife, and human property, costing millions of dollars. Relying solely on satellite monitoring is inadequate, as fires can spread rapidly before they are detected. Additionally, patrolling is often ineffective and unsafe, while drone monitoring can be costly and time-consuming. Approximately 85% of wildfires in the U.S. are initiated by human activities, such as unattended campfires, debris burning, equipment malfunctions, discarded cigarettes, or arson. Natural causes include lightning, underground coal fires, and rare events like meteor strikes.

Now I will build a device that will be installed in the forest and work like a mesh network. and monitor the forest with real-time data. I researched, and the most common time I got to take the sample is 10 to 30 minutes, so i will try this with a 20-minute interval.

<img width="832" height="534" alt="image" src="https://github.com/user-attachments/assets/fc3583a8-fe10-4e45-ac86-ad1b52018280" />



### How it will works 

There will be a tree-top device installed in the forest as a mesh network. It will send the data from one node to another node, and the master will send all the data to the server with a 20-minute time interval. 

<img width="900" height="1600" alt="image" src="https://github.com/user-attachments/assets/32adeb54-f164-4e4a-819a-f0500d8886a8" />




Flowchart of working

<img width="1180" height="790" alt="image" src="https://github.com/user-attachments/assets/f08e0370-aa4f-4e0f-addd-258a4ba02021" />

<img width="934" height="562" alt="image" src="https://github.com/user-attachments/assets/3cd2d986-351c-4534-a8ab-03255f30e7f2" />


### Circuit diagram

I have finalized all the components and built a BOM, and then made the citcuit diagram to show how it will be wired and how it goes on

**Circuit diagram**

<img width="1200" height="630" alt="image" src="https://github.com/user-attachments/assets/9c58c7d4-3901-4bce-ba03-30df32b0c7e5" />

Component list 

- Esp Fire Bettle p4
- Esp32 Ai cam
- MICS4514
- Temperature Sensor
- PM2 Dust Sensor
- RS485 output soil moisture and temperature sensor
- 10k Potentiometer
- GPS Module NEO-7N Satellite Positioning STM32 NEO 7N
- SIM800C Development Board GSM
- 0.96 Inch OLED Display Screen SSD1315 SSD1306
- 1pcs 18x30cm Stripboard Veroboard vero Board
- 1-8PCS KY-040 360 Degrees Rotary Encoder Module

### CAD Designing 

I designed a protective enclosure for the wildfire predictor device using Fusion 360. The enclosure consists of a base box and a removable top lid, sized to hold the electronic components securely. Cutouts were added for ports, sensors, and airflow to ensure proper functionality. This design allows easy assembly, protection, and future maintenance of the device.


<img width="3420" height="2224" alt="image" src="https://github.com/user-attachments/assets/3bee2f24-c9a5-49cb-88cb-fb19e6c314bb" />



<img width="3420" height="2224" alt="image" src="https://github.com/user-attachments/assets/91974ca8-9f01-4158-b01b-84e2bc64eb13" />


<img width="3420" height="2224" alt="image" src="https://github.com/user-attachments/assets/58703f98-55c3-4c75-b67f-0f44edde7ce6" />




### BOM
Here I made the Bill of Materials and other things. 

https://docs.google.com/spreadsheets/d/1B_3vjF6hnGuylOTRCjDW6Ru4Rz02-M3GZ2_8QcCnpDA/edit?usp=sharing


<img width="822" height="1752" alt="image" src="https://github.com/user-attachments/assets/7bf83029-cacb-406a-af3e-f88fac8c01cf" />



<img width="3420" height="2062" alt="image" src="https://github.com/user-attachments/assets/049f57c2-8c29-4c06-b39d-2932295c9830" />

<img width="2020" height="1238" alt="image" src="https://github.com/user-attachments/assets/3e525644-a779-4ee9-94b9-4fee16858cea" />

<img width="1776" height="1252" alt="image" src="https://github.com/user-attachments/assets/749636b8-ab24-4f09-9f9b-65f9739efcc8" />




