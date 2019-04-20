# Lane-Change-Experiment-Data
Autonomous Vehicle (AV) technologies can significantly improve traffic safety and reduce traffic congestion, and have attracted much attention in recent years. Some companies have already begun AV testing on highways, such as Waymo, Tesla and Ford. For AV, lane change is a fundamental part which could comprises path planning and path following control.
![](https://github.com/sgzzgit/Autonomous-Vehicle-Lane-Change-Experiment-Data/blob/master/Lane%20Change.JPG)
This folder contains data of all vehicle particpiated in the lane change experiment.
The data set contains two main floders, namely AV Lane Change Data and HV Lane Change Data. AV lane change data means the vehicle 3 is driven by computer commands, and HV means vehicle 3 is driven by human driver.
The data is originzed as standard NMEA GPS message. 

Global Positioning System Fix Data

Name									Example Data	Description
Sentence Identifier						$GPGGA			Global Positioning System Fix Data
Time(Just for reference)				170834			17:08:34 Z
Latitude								4124.8963, N	
Longitude								08151.6838, W	
Fix Quality:
- 0 = Invalid
- 1 = GPS fix
- 2 = DGPS fix	1	Data is from a GPS fix

Number of Satellites					05				5 Satellites are in view
Horizontal Dilution of Precision (HDOP)	1.5				Relative accuracy of horizontal position
Altitude								280.2, M		280.2 meters above mean sea level
Height of geoid above WGS84 ellipsoid	-34.0, M		-34.0 meters
Time since last DGPS update	blank		No 	last update
DGPS reference station id	blank	No station id
Checksum								*75				Used by program to check for transmission errors
