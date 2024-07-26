#Pose Estimation and Exercise Tracking with OpenCV and MediaPipe

This Python project leverages OpenCV and MediaPipe to detect human poses in real-time from a webcam stream. It then analyzes the body posture to determine if the user is performing squats or pushups correctly, providing visual feedback.

#Key Features:

1)Real-time Pose Detection: Utilizing MediaPipe's Pose solution, the script accurately tracks 33 human body landmarks.
Exercise Recognition: Built-in support for squats and pushups. Customize the exercises dictionary to add more exercises.
Posture Feedback: Visually indicates whether the user's posture aligns with proper exercise form.
Video Recording (Optional): Saves the exercise session to an output video file (configurable).
Installation:

Prerequisites: Ensure you have Python 3 and OpenCV (pip install opencv-python) installed.
MediaPipe: Follow the official installation instructions at [invalid URL removed].
Usage:

Clone the Repository: Use git clone https://github.com/harsharajkumar/personal-trainer-using-cv.git
Run the Script: Execute python main.py (replace main.py with your script's filename if different).
Webcam Access: The script will automatically access your webcam for pose detection. Press q to quit.
Configuration (Optional):

exercises Dictionary: Modify this dictionary in the script to define custom exercises with their corresponding landmark ranges for posture verification.
Video Recording: To enable video recording, uncomment the lines related to fourcc and out in the script.
Expected Output:

Real-time video feed displaying detected body landmarks.
Textual feedback indicating "Correct posture" or "Incorrect posture" based on the exercise being performed.
(Optional) Recorded video file (output.avi) containing the exercise session.
Contributing:

We welcome contributions to improve this project! Feel free to submit pull requests to enhance functionality or add more exercises.

Disclaimer:

This project is intended for educational and fitness-tracking purposes. It is not a substitute for professional medical advice. Always consult with a healthcare professional before starting any new exercise program.   

