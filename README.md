# BioMolecular-Robotics-Example

We have chosen an Arduino microcontroller to be the **"brain" of our robot.**

For the robot we have made, we will create code to have it move around (left, right, forward, reverse), move the two servos (pan/tilt) and communicate with the distance sensor. We chose Arduino because of the large user community, abundance of sample code and ease of integration with other products.

We used,

**Distance sensor ->** Fortunately in the Arduino code, there is an example for getting values from an analog sensor.For this, we go to File -> Examples -> Analog -> AnalogInOutSerial (so we can see the values)

**Pan/Tilt Again ->** btpCode have sample code to operate servos from an Arduino. File -> Examples ->  Servo -> Sweep
