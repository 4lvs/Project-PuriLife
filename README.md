# Project-PuriLife
PuriLife is a Smart Air Quality Monitor and Purifier that detects surrounding air quality using an MQ-135 gas sensor and purifies the air through a double-layered-dual-filter system made of an activated carbon filter and an electrostatic air filter. 

## Problem Statement
People with respiratory conditions fight battles every time they are outside in this air polluted world. Especially here in the Philippines, where the culture of transportation are jeepneys that emit black smoke, students, workers, and every commuter are exposed to this kind of air, everyday, every morning, and every way back home, plus the ever endless traffic of this country, you aren't just exposed to low air quality, but are also exposed to the extreme heat and traffic. Existing solutions such as face masks, massive air purifiers, and air quality monitors either restrict the breathing of users, lack portability, or lack action to solve the problem. This is where Project PuriLife comes in, inspired by the Jisulife handheld fans, a popular product and brand in the Philippines, to ensure the acceptance of the masses. The fan is needed to counter the extreme heat, while also acting as the purifier. 

## Current Prototype
An Arduino Nano processes the sensor data and controls a centrifugal fan, which provides strong airflow to pull air through the filters. The device has two modes: Auto Mode, where the fan turns on automatically when air quality becomes poor, and the On Mode. A single press button lets you toggle between off, and on, to switch to auto the button needs to be pressed for 1.5 seconds. An HC-05 Bluetooth module makes the project accessible from your phone, with this, it can send real-time air-quality readings to your phone for monitoring whenever “Demo” mode is toggled on from the phone, additionally, it sends alerts to the phone when it senses that the air quality is getting worse. The whole setup runs on batteries, making it portable and convenient for everyday use.

## Authorship
This project was designed and developed by Jacob Alvaro in 2025 as an original prototype for educational and exploratory purposes.

## Future Plans
To test the effectiveness of purification <br/>
To make the project more compact <br/>
To add more components like a small oled screen <br/>
Find a way to hide the mq-135 sensor <br/>
Make it from PCBs (not accessible in our country) <br/> 
Find a better and stronger fan <br/> 

## License
This project is released under the MIT License.
