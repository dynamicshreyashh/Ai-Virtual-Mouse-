AI Virtual Mouse
AI Virtual Mouse is an innovative project that allows users to control their computer's mouse cursor using hand gestures, leveraging computer vision and machine learning algorithms. The project uses a webcam feed to detect hand movements and translate them into real-time cursor movements and actions such as clicking or scrolling.

The application combines OpenCV for gesture recognition and TensorFlow for machine learning to create an intuitive and hands-free mouse control system.

Features
Hand Gesture Recognition: Uses a webcam to track and detect hand gestures, controlling the mouse cursor accordingly.
Cursor Movement: Move the cursor based on hand gestures and position.
Mouse Click & Scroll: Simulate mouse clicks and scrolls using specific gestures (e.g., fist for click).
Customizable Sensitivity: Adjust cursor speed and sensitivity based on user preferences.
Real-time Interaction: Enjoy smooth, responsive control in real-time with minimal latency.
Tech Stack
Python: The main programming language for building the project.
OpenCV: Used for real-time image processing and hand gesture detection.
TensorFlow: Machine learning framework used for gesture recognition.
Tkinter: Provides the graphical user interface (GUI) for settings and sensitivity adjustments.
pyautogui: Used for controlling mouse and keyboard actions based on detected gestures.
Installation
Follow the steps below to set up the project on your local machine:

Clone the repository:

bash
Copy
Edit
git clone https://github.com/dynamicshreyashh/Ai-Virtual-Mouse.git
Navigate into the project directory:

bash
Copy
Edit
cd Ai-Virtual-Mouse
Install required dependencies:

You can install the necessary libraries via pip:

bash
Copy
Edit
pip install -r requirements.txt
Run the application:

To launch the virtual mouse application, simply run:

bash
Copy
Edit
python virtual_mouse.py
This will start the webcam and the virtual mouse system. You can then control the cursor with your hand gestures.# Ai-Virtual-Mouse-
