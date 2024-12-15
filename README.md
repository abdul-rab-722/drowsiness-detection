# Drowsiness Detection System 🛌👁️🚨
## Overview
This Drowsiness Detection System is a computer vision-based application that monitors a person’s eyes using a webcam. It detects signs of drowsiness by analyzing eye closure and plays an alarm to prevent the individual from falling asleep. This project is especially useful for drivers or individuals working in critical environments requiring alertness.

## Key Features
- ### Real-Time Detection:

  - Continuously monitors the user’s eyes via a webcam.
  - Detects when the eyes are closed for prolonged periods.
- ### Alert System:

  - Triggers an audible alarm if drowsiness is detected.
  - Ensures the user is alerted to regain focus.
- ### Lightweight and Efficient:

  - Optimized for real-time performance using OpenCV and Dlib.
## Technologies Used
- #### Programming Language: Python
- #### Libraries and Tools:
  - **OpenCV:** For video capture and image processing.
  - **Dlib:** For face detection and facial landmark recognition.
  - **NumPy:** For numerical computations.
  - **Pygame:** For playing the alarm sound.
 
## How It Works
- ### Face and Eye Detection:

  - Uses Dlib's pre-trained face detection and facial landmark recognition model to identify facial features.
  - Extracts regions of interest (ROIs) for the eyes.
- ### Eye Aspect Ratio (EAR):

  - Calculates the EAR to measure the openness of the eyes.
  - If the EAR value falls below a predefined threshold for a certain duration, it is considered drowsiness.
- ### Alarm Trigger:

  - Plays an alarm sound using the Pygame library when drowsiness is detected.
  - The alarm continues until the system detects the user is awake.

## Future Enhancements
- Add head pose estimation to detect nodding off.
- Integrate with wearable devices for additional monitoring (e.g., heart rate).
- Deploy as a mobile or desktop application for wider usability.
- Support multiple users in a single frame.
