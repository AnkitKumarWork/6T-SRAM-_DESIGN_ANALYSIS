# 6T-SRAM-_DESIGN_ANALYSIS
Objective:
To design a 6T SRAM cell and measure its characteristics, including stability, power consumption, and performance.
Circuit Description:
The 6T SRAM cell uses six transistors (two cross-coupled inverters and two access transistors) to store a single bit of data. The design focuses on read/write stability, power efficiency, and performance in memory applications.
Schematic:
The 6T SRAM cell schematic was created in 90 nm technology using Cadence Virtuoso. Describe how the cell performs read and write operations and the role of each transistor in data retention. 

![image](https://github.com/user-attachments/assets/954eed8e-d683-47fc-9666-0537de4c553d)

EDA Tool Setup:
•	Schematic Creation: Cadence Virtuoso in 90 nm technology.
•	Simulation: ADL window for analyzing read and write operations, hold.
•	PVT Analysis: ADL XL using 180 nm and 65 nm process parameters to test stability and performance. Making all transistor width parameter as Wn for Nmos and Wp for Pmos.

Experimental Results:
1.	DC Response:
![image](https://github.com/user-attachments/assets/92fd8bde-3470-4865-bf8a-eb4b860b40b1)

2.	Transient Response:

![image](https://github.com/user-attachments/assets/78c562a7-f8c6-4aca-a323-debe1c0b7aab)

3.	Noise Margine- BUTTERFLY CURVE

![image](https://github.com/user-attachments/assets/e8d54d7b-5790-4c0d-8d45-3c5dc3b0f632)

4.	Power Dissipation: Pdyanmic = 51.3e-6,  
dynamic Power Dissipation of CMOS:

![image](https://github.com/user-attachments/assets/6b0cdb7b-1a84-4267-a8b7-0e96d693f858)

Static Power Dissipation of CMOS:'

![image](https://github.com/user-attachments/assets/206e7868-4da2-4710-a243-ec5a7c37bd2e)

5.	delay:   20.3e-9
6.	PVT Analysis:
o	Use 180 nm and 65 nm process parameters.
o	Evaluate the SRAM cell's stability under varying conditions.

![image](https://github.com/user-attachments/assets/bec0b315-6874-4647-93ef-65b3b5c81305)

![image](https://github.com/user-attachments/assets/add989fa-2e56-4b89-85b1-17eb4441a872)

LAYOUT DESIGN – 
Circuit design - 

![image](https://github.com/user-attachments/assets/8c017847-3a9a-45f0-9ab7-0988244626db)

Layout design - 

![image](https://github.com/user-attachments/assets/d60298f6-b15f-4cf9-82a9-d89e91e4b137)

DRC CHECK

![image](https://github.com/user-attachments/assets/ecd52a9f-31fd-476b-9c59-cc36480a78f5)

LVS CHECK

![image](https://github.com/user-attachments/assets/e5e21deb-00cb-4e71-a831-1cf444481527)

Observations:
The 6T SRAM cell was created in 90 nm technology, tested, and analyzed using Cadence software. The design successfully balances speed, power, and stability, with performance verified under PVT variations.







