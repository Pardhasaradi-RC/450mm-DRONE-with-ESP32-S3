The DIY Flight Controller
To keep things modular, I built the flight controller from scratch on a standard 36x36mm perfboard. The brain of the operation is an ESP32-S3 SuperMini, paired up with an MPU6500 gyroscope to keep the flight dynamics smooth.

for firmware , i am using RClopaz github repo to upload bin file that lets me use betaflight configarator to set PID perameters and set modes and also calibrate the gyro. very usefull. thanks to RClopaz 


components : 

esp32 s3 supermini: brain of the drone - 450rs 

mpu6500 : to stablize the drone and use it as angle mode - 350rs 

PDB: matek power distribution board is used to distribute 12v to every esc
cost - 500rs 

Motors: I'm running classic A2212 1000kv brushless motors - 400rs - each 
total = 400x4 = 1200rs

ESC: Simonk 30A esc - 450rs - each
total = 450x4 = 1400rs

Propellers: 1045 propellers are the best props for this 1000kv motors. they are the most effiecient with 1000kv motor

RADIO CONTROLLER : 
FlySky FS-i6 transmitter on PWM protocol - 4600rs 

f450 drone Frame - 650rs

battery : 
you can only go for a battery that has rated over 35c . and capacity is your choice, 

5200mah battery : 5200rs

Additional: ( not optional )

 1. soldering machines - 2 - heavy and normalw
 2. perf board - use green one, i used red becuase of unavailability
 3. header pins if you want to reuse the components.
 4. connecting wires
 5. multi meter(you'll need it)
 6. zip ties
 7. insulation tape 

