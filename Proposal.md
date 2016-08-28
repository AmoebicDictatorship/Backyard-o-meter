# Backyard-o-meter #

## Brian Maher, Forest Eckardt, and Michael Biscotti ##

Goal: collect metrics on how many people pass through our backyard at various times and identify traffic patterns. 

## Implementation ##

### Design Considerations ###

#### Raw data collection ####

##### IR Sensors #####
Description: use IR sensors to count the number of times 

Advantages: 
- Inexpensive
- Good effective range

Drawbacks: 
- Unsure of reliability
- May be difficult to count number of people passing simultaneously

Other considerations:
- Scan pattern (cone, beam, other?)

##### Video Processing #####
Description: record video and process images 

Advantages:
- Reliable
- Works in all lighting conditions
- Algorithms exist to count number of people in image 

Drawbacks: 
- Difficult to implement
- Computationally expensive
- Video output requires large amounts of data to store
- Requires light

Other considerations:
- Legality of video surveillance
- Research pre-existing open source solutions

##### Laser ####
Description: use a laser beam to measure crossings through the area

Advantages:
- Inexpensive

Drawbacks:
- Requires some exterior setup
- Unreliable for counting number of people

Other considerations:
- More computationally/algorithmically complex than IR Sensor
- Laser eye safety

##### Thermal Cameras #####
Description: use cameras to detech the heat signatures of people

Advantages:
- Accuracy
- Works in all lighting conditions

Drawbacks:
- Expensive
- Either computationally expensive or even more finanically expensive

Other considerations: None