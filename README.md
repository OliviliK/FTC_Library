# FTC_Library
Common classes used in FIRST Tech Challenge OpModes.  The OpModes are stored in another repository (FTC_OpModes).

## ArrayQueue.java
High performance **FIFO** for intra-thread buffering.  When used for inter-thread buffering, external synchronization is required.

An example of usage can be seen at 
* http://olliesworkshops.blogspot.com/2015/11/arduino-wire-library-for-i2c-sensors.html
* http://olliesworkshops.blogspot.com/2015/11/fix-in-ftc-wire-library.html

## Bno055.java
Bno055 is a 9 degree of freedom (9 DOF) sensor from Bosch. It is also known as inertial measurement unit (IMU). In addition of the three core sensors, gyroscope, accelerometer, and magnetometer.

Additional descriptions can be found at
* http://olliesworkshops.blogspot.com/2015/11/bno055-imu-sensor-with-ftc-wire-library.html
