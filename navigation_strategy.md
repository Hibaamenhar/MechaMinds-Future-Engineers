# Navigation Strategy

The robot follows a structured autonomous navigation system:

## 1. Lane Detection
The camera detects lane boundaries using image processing techniques.

## 2. Path Following
The robot stays centered between detected lanes using proportional control.

## 3. Object Detection
- Red pillars: indicate stop or warning zones
- Green pillars: indicate allowed direction

## 4. Obstacle Avoidance
The ultrasonic sensor stops the robot when an obstacle is detected within 20 cm.

## 5. Stability Control
The IMU ensures accurate turning and prevents drift during movement.