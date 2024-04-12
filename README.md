# FacialiZe
Redefining Attendance System with Facial Recognition
## Table of Contents

- [Introduction]
- [Requirements]
- [Installation]
- [Usage]
- [Contributing]
- [License]

## Introduction

This is a Flask web application that uses OpenCV and scikit-learn libraries to recognize students' faces in real-time and record their attendance automatically. The system works in the following way:

1. The system captures the video stream from the webcam connected to the computer.
2. The system extracts faces from the video stream using the Haar Cascade classifier.
3. The system uses a pre-trained K-Nearest Neighbor classifier to recognize the faces in the video stream.
4. The system records the attendance of the recognized faces in a CSV file.

## Requirements

To run this application, you need the following libraries:

- Flask
- OpenCV
- scikit-learn
- Pandas

You also need to download the pre-trained Haar Cascade classifier and save it in the project directory.

## Installation

To install the required libraries, run the following command:

```
pip install -r requirements.txt
```

## Usage

To start the web application, run the following command:

```
python app.py
```

This will start the Flask server on port 5000. Open your web browser and go to your localhost to access the web application.
On the home page, you will see a list of students who have attended the class today. To start the face recognition system, click on the "Take Attendance" button.
You can add new students to the system by clicking on the "Add Student" button. You need to provide the student's name and ID number, and upload a photo of the student's face.
You can also view a list of all registered students by clicking on the "List Students" button. From here, you can delete a student's record from the system.
## Contributing

Contributions are always welcome! If you find any bugs or have any suggestions, please create an issue or a pull request.
