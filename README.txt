DETERMINATION OF PULSE RATE, BREATHING RATE, OXYGEN SATURATION LEVEL, AND AGING INDEX USING A SMARTPHONE CAMERA

This repository provides MATLAB code for determining key cardiovascular health parameters—Pulse Rate, Breathing Rate, Oxygen Saturation (SpO2), and Aging Index—using a smartphone camera. The technique leverages photoplethysmography (PPG) from a fingertip video to extract health data.

Features
Pulse Rate Detection: Utilizes a moving average filter to detect pulse peaks in the red channel of a fingertip video.
Breathing Rate Detection: Applies a Butterworth filter to extract the breathing rate from low-frequency signal components.
Oxygen Saturation (SpO2): Calculates SpO2 using the red and blue channel intensities from the video.
Aging Index Calculation: Estimates the aging index through second-derivative peak analysis.

Files
Main Code (Pulse_Rate_Breathing_Rate_Oxygen_Saturation_Level.m & AGING_INDEX.m): Computes all health parameters.
Function Definitions: Includes utility functions for signal normalization, filtering, and peak identification.

Usage
Record a well-lit video of the fingertip with the flashlight on. Make sure the fingertip is in good contact with the camera lens
Update the .mp4 file path in the code.
Run the MATLAB script to view calculated health parameters and plots.
This method provides an accessible, non-invasive tool for monitoring cardiovascular health, potentially aiding in preventive healthcare.
