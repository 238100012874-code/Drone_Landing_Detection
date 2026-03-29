# Autonomous Drone Landing Detection

## Project Overview
This project focuses on identifying and detecting safe landing zones for drones using advanced computer vision techniques. The system is designed to provide real-time landing pad detection to ensure safe autonomous missions.

## Dataset
The model was trained and evaluated using a custom dataset of drone-view images and videos. 
- **Data Source:** Custom collection of landing pad environments.
- **Size:** Over 500+ annotated images and video frames.
- **Conditions:** Tested across various altitudes, angles, and lighting conditions.

## Technical Details
- **Programming Language:** Python
- **Tools/Libraries:** OpenCV, TensorFlow, NumPy.
- **Software Environment:** Visual Studio Code (VS Code).

## Implementation Features
- Real-time circle detection using Hough Transform.
- Image preprocessing including Grayscale conversion and Gaussian Blur.
- Accuracy optimization for different drone altitudes.

## Key Results
- **Detection Accuracy:** Achieved over 90% success rate in identifying landing markers.
- **Performance:** Low latency processing suitable for real-time drone flight controllers.

## How to Run
1. Clone the repository.
2. Install dependencies:
   ```bash
   pip install opencv-python tensorflow numpy
