# Room_Occupancy_Detection
This project involves analyzing sensor data from various sensors placed in a room. These sensors include motion detectors, temperature sensors, light sensors, and even sound sensors. The objective is to develop a machine-learning model that can classify whether the room is currently occupied or unoccupied based on the sensor readings. This is a binary classification task where the model predicts one of two classes: "occupied" or "unoccupied."

## Data Description
The data is of secondary source and is taken from <br>
Candanedo,Luis. (2016). Occupancy Detection . UCI Machine Learning Repository.<br> https://doi.org/10.24432/C5X01N.

It has 20560 instances and 7 attributes. <br>
The data is divided into 3 sets one for training, testing, and validation. Ground-truth occupancy was obtained from time-stamped pictures that were taken every minute. <br>
It has no missing values.

### Attribute Information
date time year-month-day hour:minute:second <br>
Temperature, in Celsius <br>
Relative Humidity, in percentage <br>
Light, in Lux <br>
CO2, in ppm <br>
Humidity Ratio, Derived quantity from temperature and relative humidity, in kgwater-vapor/kg-air <br>
Occupancy, 0 or 1, 0 for not occupied, 1 for occupied status 

## Objectives
1. **Energy Efficiency:** Predicting room occupancy can be essential for optimizing energy consumption in buildings. By knowing when a room is unoccupied, heating, cooling, and lighting systems can be adjusted or turned off, leading to significant energy savings.
2. **Security and Safety:** Knowing if a room is occupied is important for security and safety purposes. In a smart home or office environment, this information can be used to trigger security systems or alerts when unauthorized access is detected.
3. **Resource Optimization:** Predicting occupancy helps in resource allocation. For example, in a hotel, the cleaning staff can be directed to rooms that are vacant, reducing labor costs and minimizing disturbance to guests.
4. **Occupancy Insights:** Beyond energy efficiency and security, occupancy data can provide valuable insights into space utilization. Organizations can use this information to optimize office layouts or to plan for future space requirements.
