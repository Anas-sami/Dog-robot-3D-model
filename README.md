# Dog-robot-3D-model
Developed for Smart Methods, this Tinkercad project features an 8 DOF bio-inspired quadruped robot dog. It optimizes locomotive stability by bottom-mounting heavy components  lower the Center of Gravity. Powered by mathematically verified MG99R servos the robot utilizes a stable crawl gait sequence to maintain balance and prevent mechanical failure.


# Bio-Inspired Quadruped Robot Dog: Mechanical Design & Locomotion

An 8 DOF bio-inspired quadruped robot dog engineered to study robotic kinematics, dynamic balance, and stable locomotion gaits. Designed using Tinkercad and mathematically verified to prevent mechanical and structural failures during operation.

## Key Design Specifications
- **8 Degrees of Freedom (DOF):** 2 rotational axes per leg (Hip and Knee pitch articulation) utilizing high-torque metal-gear servo motors.
- **Optimized Center of Gravity (CoG):** Heavy power components (battery pack and toggle switch) are integrated into the lower deck of the chassis to minimize the tipping moment arm and increase static stabilization.
- **Avionics & Sensor Array:** Incorporates an ultrasonic sensor (HC-SR04) inside the head assembly for active obstacle avoidance, along with an Inertial Measurement Unit (MPU6050) for real-time balance assessment.
- **Statically Stable Crawl Gait:** Implements a single-limb stride gait sequence, ensuring that the vertical projection of the CoG remains bounded within the support polygon at all times.

## Hardware & Actuation Stack
- **Actuators:** 8 x MG996R Metal Gear Servos (Providing 11.0 kg·cm stall torque @ 6.0V).
- **Primary Sensors:** HC-SR04 Ultrasonic Distance Sensor & MPU6050 6-Axis Gyroscope/Accelerometer.
- **Power Distribution:** Dedicated bottom-mounted battery pack with integrated mechanical toggle switches.
- **Control Avionics:** Closed-loop PWM signal generation via microcontrollers (Arduino Nano / ESP32 framework).
