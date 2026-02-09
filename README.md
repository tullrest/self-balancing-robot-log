# Self-Balancing Robot (Work in Progress)

This repository documents the step-by-step development of a two-wheel self-balancing robot.
The focus of this project is not only the final result, but also the engineering process:
hardware bring-up, sensor validation, motor control, and control tuning.

## Current Status (as of Feb 2026)
- ESP32 + MPU6050 pitch estimation working
- Complementary filter implemented
- PID output mapped to stepper motor speed
- Dual TMC2209 stepper drivers tested
- Motors respond correctly to tilt direction
- Mechanical chassis design in progress

## Hardware
- ESP32
- MPU6050 IMU
- NEMA17 stepper motors
- TMC2209 stepper drivers
- 2S LiPo battery (motor power)
- 3D printed chassis (WIP)

## Software Progress
- [x] I2C communication test
- [x] IMU calibration and pitch estimation
- [x] PID controller implementation
- [x] Step/Dir motor control test
- [ ] Chassis mounting and vibration reduction
- [ ] PID tuning on ground
- [ ] Safety and startup calibration

## Notes
This project is under active development.
Design decisions and code may change as the hardware evolves.
