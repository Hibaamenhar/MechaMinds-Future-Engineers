# Hardware Description

The robot is built on a 4WD aluminium chassis designed for stability and mobility.

## Components

- Raspberry Pi 5  
  Main processing unit running all AI and control algorithms.

- Camera Module 3 Wide  
  Used for lane detection and color recognition (red/green pillars).

- HC-SR04 Ultrasonic Sensor  
  Detects obstacles in front of the robot. Stops movement if distance < 20 cm.

- MPU-6050 IMU  
  Provides orientation and angle correction for precise turning.

- TB6612FNG Motor Driver  
  Controls four DC motors independently using PWM signals.

- 3S LiPo Battery (11.1V 2200mAh)  
  Powers motors and electronics via voltage regulation.