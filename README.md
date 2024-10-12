Eye Mouse Project

This project demonstrates an eye-tracking system that allows users to control a mouse pointer using their eye movements. It leverages computer vision techniques to detect eye movement and translates that into mouse pointer movement.

Features

	•	Eye Tracking: Detects eye movement in real-time.
	•	Mouse Control: Moves the mouse pointer based on where the user is looking.
	•	Click Events: Simulates mouse clicks using eye blinks or gaze fixation.

Technologies Used

	•	Python
	•	OpenCV (for image processing and eye detection)
	•	Dlib (for facial landmark detection)
	•	PyAutoGUI (for mouse control)

Setup Instructions

	1.	Clone the repository:

git clone https://github.com/your-username/eye-mouse-project.git


	2.	Install the required packages:

pip install -r requirements.txt


	3.	Run the project:

python eye_mouse.py



How It Works

	1.	Face and Eye Detection: The system detects the user’s face and eyes using OpenCV and Dlib.
	2.	Eye Movement Tracking: It tracks the movement of the eyes and maps this to the screen coordinates.
	3.	Mouse Pointer Movement: The mouse pointer moves according to the detected gaze direction.
	4.	Click Simulation: Eye blinks or prolonged gaze on a specific area can simulate mouse clicks.

Future Improvements

	•	Increase the accuracy of eye-tracking.
	•	Add support for drag-and-drop functionality.
	•	Improve click simulation with more reliable blink detection.

License

This project is licensed under the MIT License.

