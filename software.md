# Software Description

The system is developed in Python and runs on Raspberry Pi 5.

## Libraries Used
- OpenCV (computer vision)
- NumPy (numerical processing)
- RPi.GPIO (motor control)
- time (timing and control loops)

## Main Functions

### Vision System
- Captures real-time video stream
- Detects lane boundaries
- Identifies red and green pillars

### Control System
- Converts vision output into steering commands
- Adjusts motor speed dynamically

### Sensor Fusion
- Combines ultrasonic + IMU data
- Ensures collision avoidance and stability