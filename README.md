# Gesture-Controlled Presentation

This project implements a gesture-controlled presentation system using OpenCV and speech recognition. It allows users to navigate through presentation slides using hand gestures and voice commands.

## Features

- Hand detection and gesture recognition using OpenCV.
- Voice command recognition for slide navigation.
- Real-time display of presentation slides.
- Annotations on slides using hand gestures.

## Requirements

Before running the project, ensure you have the following installed:

- Python 3.x
- OpenCV
- cvzone
- SpeechRecognition
- PyAudio (for microphone input)
- NumPy

You can install the required packages using pip:


pip install opencv-python cvzone SpeechRecognition pyaudio numpy
exit

## Clone the repository to your local machine:
git clone https://github.com/raj22bh/AI-GESTURE-PRESENTATION.git
cd your-repo-name

Create a folder named Presentation in the root directory of the project.

Add your presentation images (e.g., JPG, PNG) to the Presentation folder. Ensure the images are named appropriately for proper sorting.


## Usage
Run the script:

python main.py


The application will open a window displaying the first image from the Presentation folder.

Use the following voice commands to navigate through the slides:

"next": Move to the next slide.
"previous": Go back to the previous slide.
"clear": Clear any annotations made on the slide.
Use hand gestures to annotate slides. The system detects gestures to draw lines on the slide.

To exit the application, press the 'q' key.

 ## Hand Gestures
Hand detection allows for gesture-based interactions. Implement gesture logic (such as drawing or navigation) in the specified section of the code.

  ## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
OpenCV for computer vision functionalities.
cvzone for simplifying OpenCV tasks.
SpeechRecognition for voice command capabilities.

# Contributing
Contributions are welcome! If you have suggestions for improvements or features, feel free to create a pull request or open an issue.


