<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

<h1>👀 Vigil Eye - Drowsiness Detection System 🚨</h1>
<p>Vigil Eye is a Python-based drowsiness detection system that monitors eye movements and alerts users when signs of fatigue are detected. Using facial landmark detection and the eye aspect ratio (EAR), the app triggers an alert with sound when prolonged eye closure is detected.</p>

<h2>📋 Features</h2>
<ul>
  <li><strong>Real-Time Monitoring</strong>: Monitors users' eye movements using webcam input.</li>
  <li><strong>Fatigue Detection</strong>: Detects prolonged eye closure and triggers an alert.</li>
  <li><strong>Audio Alerts</strong>: Plays an alert sound when drowsiness is detected.</li>
  <li><strong>User-Friendly Interface</strong>: Simple Tkinter-based interface to start and stop detection.</li>
</ul>

<h2>⚙️ Prerequisites</h2>
<p>Before running the application, make sure you have:</p>
<ul>
  <li><strong>Python 3.x</strong> (recommended version: 3.7+)</li>
  <li><strong>OpenCV</strong> for real-time video capture and processing.</li>
  <li><strong>dlib</strong> for facial landmark detection.</li>
  <li><strong>imutils</strong> for image resizing and handling.</li>
  <li><strong>pygame</strong> for playing alert sounds.</li>
  <li><strong>scipy</strong> for calculating distances and Eye Aspect Ratio (EAR).</li>
  <li><strong>Pillow</strong> for image handling (used for GUI with Tkinter).</li>
  <li><strong>tkinter</strong> for building the GUI (pre-installed with Python).</li>
</ul>


<p>Install dependencies using pip:</p>
<pre><code>pip install opencv-python dlib imutils pygame scipy pillow</code></pre>

<h2>📦 Setup Instructions</h2>

<h3>Step 1: Clone the Repository</h3>
<pre><code>git clone https://github.com/your-username/Vigil-Eye.git
cd VigilEye
</code></pre>

<h3>Step 2: Download the Facial Landmark Model</h3>
<p>Download the <strong>shape_predictor_68_face_landmarks.dat</strong> file from <a href="https://github.com/italojs/facial-landmarks-recognition/blob/master/shape_predictor_68_face_landmarks.dat" target="_blank">here</a>.</p>
<p>Place the file in the project directory.</p>

<h3>Step 3: Run the Application</h3>
<pre><code>python vigil_eye.py</code></pre>

<h3>Step 4: Interface Instructions</h3>
<ul>
  <li><strong>Start Detection</strong>: Click the "START DETECTION" button to begin monitoring eye movements.</li>
  <li><strong>Stop Detection</strong>: Click the "STOP DETECTION" button to stop the system and stop the alert sound.</li>
</ul>

<h2>🎮 Usage</h2>
<ol>
  <li><strong>Login</strong>: No login required for this application.</li>
  <li><strong>Eye Monitoring</strong>: The system will monitor your eye movements when detection is started.</li>
  <li><strong>Alert</strong>: If prolonged eye closure is detected, an audio alert will sound.</li>
</ol>

<h2>📁 Project Structure</h2>
<pre><code>VigilEye/
├── vigil_eye.py               # Main Python script
├── shape_predictor_68_face_landmarks.dat  # Facial landmark model file
└── README.md                  # Project documentation
</code></pre>

<h2>📚 Dependencies</h2>
<ul>
  <li><strong>OpenCV</strong> for real-time video capture and image processing.</li>
  <li><strong>dlib</strong> for detecting facial landmarks and calculating the eye aspect ratio.</li>
  <li><strong>imutils</strong> for resizing images and handling video frames.</li>
  <li><strong>pygame</strong> for playing alert sounds.</li>
</ul>

<h2>🚀 Future Enhancements</h2>
<ul>
  <li><strong>Mobile App Version</strong>: Create a mobile version of the drowsiness detection system for use on smartphones.</li>
  <li><strong>Multi-User Support</strong>: Add user profiles to track drowsiness history for different users.</li>
  <li><strong>Advanced Alerting</strong>: Implement vibration or push notifications for enhanced alertness.</li>
</ul>

</body>
</html>
