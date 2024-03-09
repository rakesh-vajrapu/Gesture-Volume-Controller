# Gesture Volume Controller

## Overview
The Gesture Volume Controller is a Python-based project that allows users to control the system's audio volume using hand gestures captured by a webcam. The application utilizes computer vision libraries for hand gesture recognition and audio control libraries to adjust the volume based on the detected gestures.

## Tech Stack
- **Python Programming Language:**
  - The project is written in Python, known for its simplicity and readability.

- **Computer Vision Libraries:**
  - **OpenCV (Open Source Computer Vision Library):**
    - Used for capturing video frames, image processing, and displaying real-time output.
  - **Mediapipe:**
    - Utilized for hand gesture recognition through a pre-trained hand landmark model.

- **Audio Control Libraries:**
  - **pycaw (Python Core Audio Windows Library):**
    - Used to interface with the Windows Core Audio API, controlling audio settings based on hand gestures.

- **Additional Libraries:**
  - **NumPy:**
    - Used for numerical operations and array handling, particularly in interpolating values based on hand gesture distances.
  - **ctypes and comtypes:**
    - Employed for interfacing with the Windows Core Audio API.

- **Webcam Setup:**
  - The project utilizes the webcam for capturing video frames, with configuration set using OpenCV.

- **Development Environment:**
  - The code is developed and executed in a Python environment, utilizing text editors or integrated development environments (IDEs).

## Features
- Real-time hand gesture recognition for controlling system audio volume.
- Visual feedback through dynamic circles, lines, and a responsive volume bar.
- Integration of computer vision and audio processing technologies.
- Cross-disciplinary skills showcased in bridging hardware and software components.

## Usage
1. Install the required libraries:
   pip install opencv-python mediapipe comtypes

2. Run the `gesture_volume_controller.py` script:
   python gesture_volume_controller.py

3. Use thumb and index finger gestures to control the volume.

## Contributions
Contributions and feedback are welcome! Feel free to submit bug reports, feature requests, or enhancements.
