
markdown
Copy code
# Vigil Eye - Drowsiness Detection System

**Vigil Eye** is a Python-based drowsiness detection application designed to monitor eye movements and alert users when signs of fatigue are detected. The app uses facial landmarks and the eye aspect ratio (EAR) to monitor eye closure in real-time. If the system detects prolonged eye closure, it triggers an alert with a sound.

## 📋 Features
- **Real-Time Monitoring**: Monitors users' eye movements and calculates the eye aspect ratio.
- **Fatigue Detection**: Alerts the user when eye closure exceeds a certain threshold.
- **Audio Alerts**: Plays a sound when drowsiness is detected.
- **User-Friendly Interface**: Simple Tkinter interface to start and stop detection.

## ⚙️ Prerequisites
Before running the application, ensure you have the following installed:
- **Python 3.x** (recommended version: 3.7+)
- **OpenCV** for computer vision tasks.
- **dlib** for facial landmark detection.
- **imutils** for image processing functions.
- **pygame** for audio playback.

Install dependencies using pip:
```bash
pip install opencv-python dlib imutils pygame
📦 Setup Instructions
Step 1: Clone the Repository
bash
Copy code
git clone https://github.com/your-username/VigilEye.git
cd VigilEye
Step 2: Prepare the shape_predictor_68_face_landmarks.dat File
Download the shape_predictor_68_face_landmarks.dat file from the dlib model repository.
Place the file in the project folder.
Step 3: Run the Application
Open a terminal or command prompt and navigate to the project directory.
Run the following command to start the application:
bash
Copy code
python vigil_eye.py
Step 4: Interface Instructions
Start Detection: Click the "START DETECTION" button to begin monitoring eye movements.
Stop Detection: Click the "STOP DETECTION" button to stop the system and stop the alert sound.
🎮 Usage
Login: No login required for this application.
Eye Monitoring: The system will start monitoring your eyes once detection begins.
Alert: If your eyes are closed for too long, an alert will be triggered with an audio cue.
📁 Project Structure
bash
Copy code
VigilEye/
├── vigil_eye.py              # Main Python script
├── shape_predictor_68_face_landmarks.dat  # Facial landmark model file
└── README.md                 # Project documentation
📚 Dependencies
OpenCV: For real-time video capture and image processing.
dlib: For detecting facial landmarks and calculating the eye aspect ratio.
imutils: For image resizing and handling.
pygame: For playing the alert sound.
🚀 Future Enhancements
Mobile App Version: Create a mobile version for drowsiness detection on phones.
Multi-user Support: Add user profiles to track drowsiness history.
Advanced Alerting: Implement vibration or push notifications for greater alertness.
