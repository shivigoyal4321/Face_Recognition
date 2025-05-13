
# Face Recognition Attendance System
# ABOUT THIS PROJECT:
Face Recognition Attendance System is a Python-based real-time application that uses a webcam to recognize known faces and automatically record attendance. 
Built with OpenCV and face_recognition, it detects and identifies individuals from a preloaded set of images, then logs their names and timestamps into a dated CSV file.
This project demonstrates practical use of computer vision and facial recognition for automation in classrooms, offices, or access control systems.

## Features
- Detects and recognizes faces.
- Logs attendance with name and timestamp.
- Displays a real-time feed of the webcam with attendance info.

## Demo
Watch the demo

## How to Run
1. Install dependencies:
2. Run the notebook or script.
3. Press `q` to stop the webcam and save the attendance.

## Technologies Used
- OpenCV
- face_recognition
- Python

## License
MIT License


# WORKING EXPLAINED IN DETAIL:
Loads 2 known faces: for example i used pictures with name = Harry and Larry

Starts the webcam on execution, show those known faces

Recognizes those faces in real-time

Displays their names on screen and

Marks attendance by writing their names and timestamps into a CSV file

If unknown face is shown, it displays 

Unknwon

