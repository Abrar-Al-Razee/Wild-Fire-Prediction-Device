### Wild Fire Prediction Device


Wildfires are among the most destructive and unpredictable natural disasters. They lead to the loss of vast areas of forests, wildlife, and human property, costing millions of dollars. Relying solely on satellite monitoring is inadequate, as fires can spread rapidly before they are detected. Additionally, patrolling is often ineffective and unsafe, while drone monitoring can be costly and time-consuming. Approximately 85% of wildfires in the U.S. are initiated by human activities, such as unattended campfires, debris burning, equipment malfunctions, discarded cigarettes, or arson. Natural causes include lightning, underground coal fires, and rare events like meteor strikes.

Now I will build a device that will be installed in the forest and work like a mesh network. and monitor the forest with real-time data. I researched, and the most common time I got to take the sample is 10 to 30 minutes, so i will try this with a 20-minute interval.

![Sensor Interval data](/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MjIxNzksInB1ciI6ImJsb2JfaWQifX0=--1d0ebd51b545d9efe85363c2f691d3ec79adcdda/Screenshot%202025-12-11%20at%2012.20.55%E2%80%AFAM.png)


### How it will works 

There will be a tree-top device installed in the forest as a mesh network. It will send the data from one node to another node, and the master will send all the data to the server with a 20-minute time interval. 

![Hand drawing](/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MjM1NjgsInB1ciI6ImJsb2JfaWQifX0=--8a961be3e31b8de32044bd99e8633d073f0d15b1/WhatsApp%20Image%202025-12-13%20at%207.07.25%20PM.jpeg)


Flowchart of working

![Device work flow](/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MjM1NzEsInB1ciI6ImJsb2JfaWQifX0=--1f8a5a070768fae571f948806138e862d65ec5ab/Screenshot%202025-12-13%20at%207.10.08%E2%80%AFPM.png)

![Data proccessing](/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MjM1NzIsInB1ciI6ImJsb2JfaWQifX0=--966cbb60394e7d90aa07b2b18ed8b7b119593d3d/Screenshot%202025-12-13%20at%207.11.34%E2%80%AFPM.png)

### Circuit diagram

I have finalized all the components and built a BOM, and then made the citcuit diagram to show how it will be wired and how it goes on

**Circuit diagram**

![Untitled design](/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MjUxMzcsInB1ciI6ImJsb2JfaWQifX0=--564dbb0fcf05ff342728e1ba8be48033fc30f51c/Untitled%20design.png)

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


![CAD](/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MjUyNjcsInB1ciI6ImJsb2JfaWQifX0=--ac7cc9b152537e23d8ed37e53398594b82de5ca8/Screenshot%202025-12-16%20at%207.23.57%E2%80%AFPM.png)


![CAD](/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MjUyNjgsInB1ciI6ImJsb2JfaWQifX0=--afd6b06626892a4699f4c99c12852eeac7e971ae/Screenshot%202025-12-16%20at%207.24.07%E2%80%AFPM.png)


![CAD](/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MjUyNjksInB1ciI6ImJsb2JfaWQifX0=--ca8c89dc2e86e09be8df7bf2b77aec40606a6d7c/Screenshot%202025-12-16%20at%208.40.29%E2%80%AFPM.png)



### BOM
Here I made the Bill of Materials and other things. 

https://docs.google.com/spreadsheets/d/1B_3vjF6hnGuylOTRCjDW6Ru4Rz02-M3GZ2_8QcCnpDA/edit?usp=sharing


![Screenshot 2025-12-16 at 11.50.37 PM](/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MjUyNzEsInB1ciI6ImJsb2JfaWQifX0=--b4cf3b36521b1e362c498812048f9c2aadedc876/Screenshot%202025-12-16%20at%2011.50.37%E2%80%AFPM.png)


![Cart view](/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6MjUyNzAsInB1ciI6ImJsb2JfaWQifX0=--4a4ef199c647802e4f4ba4c8cfdf7f39adf5d43f/Screenshot%202025-12-16%20at%203.56.40%E2%80%AFPM.png)





