Dual-Axis Solar Tracker – MATLAB/Simulink

📌 Project Description

This project implements a dual-axis solar tracking system developed in MATLAB/Simulink, which uses real-time solar position calculations (azimuth and elevation) along with PID control to continuously orient a solar panel toward the sun for maximum energy capture.

The system computes the sun’s position based on time, latitude, longitude, and day number, and dynamically adjusts the panel orientation along both axes.

🎯 Objectives

1. Calculate solar azimuth and elevation angles

2. Implement dual-axis tracking (horizontal & vertical movement)

3. Design PID controllers for precise angular control

4. Improve solar panel alignment and efficiency

5. Simulate real-world solar tracking behavior

🛠Tools & Technologies

MATLAB

Simulink

Control Systems (PID)

Solar Position Algorithm

⚙️ System Overview

The system consists of the following main blocks:

1. Solar Position Calculation

Inputs: time, latitude, longitude, day number

Outputs: solar elevation & azimuth angles

2. Error Calculation

Difference between desired and actual panel angles

3. PID Controllers

One PID for elevation control

One PID for azimuth control

📊 Outputs

1. Continuous tracking of solar position

2. Smooth panel movement using PID control

3. Stable elevation and azimuth response curves

🔮 Future Enhancements

AI / LSTM-based solar tracking

Real-time sensor integration 

Fault detection in actuators and sensors

Web-based monitoring dashboard
