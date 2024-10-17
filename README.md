# **BodySpeak**
This project uses Mediapipe and OpenCV to capture video input from a webcam, process the video to 
detect landmarks on the face and body, and classify body language based on the detected landmarks.
The classification results are displayed in real-time on the video feed.

## Overview
This project leverages the powerful Mediapipe framework to detect and track body and face landmarks in real-time. By using OpenCV for video capture and display, the system overlays the detected landmarks and classification results onto the live video feed from a webcam. A pre-trained machine learning model (e.g., a scikit-learn classifier) is used to classify the body language based on the extracted landmarks. This setup can be used for various applications, including gesture recognition, human-computer interaction, and more.

### Key Features
**Real-time video processing:** Capture and process video input from a webcam in real-time.
Landmark detection: Use Mediapipe to detect and track facial and body landmarks.
Body language classification: Classify body language using a pre-trained machine learning model.
Overlay results: Display the detected landmarks and classification results directly on the video
feed.


