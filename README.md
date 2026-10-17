# Voice-Controlled Colour Sorting Robotic Arm

## Overview
This project implements a voice-controlled robotic arm that detects coloured objects using a camera and sorts them using pick-and-place movements. It combines computer vision, speech recognition, and robotic arm control.

**Technologies Used**
- Python
- OpenCV
- NumPy
- Computer Vision
- Vosk Speech Recognition
- Jupyter Notebook
- Robotic Arm Control Library

**Features**
- **Colour Detection:** Identifies coloured objects using HSV colour ranges.
- **Voice Control:** Accepts voice commands for colours and robotic arm operations.
- **Pick and Place:** Performs robotic arm movements to pick and move objects.
- **Inverse Kinematics:** Calculates robotic arm joint positions for movement.
- **Camera Integration:** Uses a camera for live object detection.
- **Interactive Interface:** Displays camera feed and system status.

**Working Principle**
1. The camera captures the objects in the workspace.
2. OpenCV processes the images to detect colours.
3. The voice recognition system identifies spoken commands.
4. The robotic arm performs the required pick-and-place movements.
5. The system uses predefined positions and inverse kinematics to control the arm.


**Learning Outcomes**
- Learned the basics of computer vision and HSV colour detection.
- Explored voice recognition using the Vosk library.
- Understood inverse kinematics and robotic arm movement.
- Gained practical exposure to Python-based robotics integration.

**Applications**
- Automated object sorting
- Industrial automation
- Robotics education
- Voice-controlled robotic systems

