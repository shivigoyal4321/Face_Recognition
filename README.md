# 🧍‍♂️ Face Recognition Attendance System

A Python-based real-time application that automates attendance using facial recognition via a webcam feed. Built using OpenCV and the `face_recognition` library, the system detects and identifies individuals from a preloaded image dataset and logs their names with timestamps into dated CSV files.

## 🚀 Features
- 📷 Real-time face detection and recognition from webcam
- 🧾 Automatic attendance logging with names and timestamps
- 📊 CSV-based daily logs for easy tracking
- 🔍 Displays names or “Unknown” on screen in real time

## 🛠️ Technologies Used
- Python  
- OpenCV  
- face_recognition  
- NumPy  
- CSV  

## 📦 Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/shivigoyal4321/Face_Recognition.git
   cd Face_Recognition
Install dependencies:

bash
Copy
Edit
pip install opencv-python face_recognition numpy
## ▶️ How to Run
Place reference images of known individuals inside the Images/ directory. The file name (e.g., Harry.jpg) is used as the person's name.

Run the script or notebook:

bash
Copy
Edit
python face_recognition_attendance.py
(Or open and run the notebook if using .ipynb)

Press q to stop the webcam and save the attendance log.

## 📂 Project Structure

Face_Recognition/
├── Images/                  # Folder with known faces (e.g., Harry.jpg, Larry.jpg)
├── Attendance/              # Folder for saved attendance logs (CSV format)
├── face_recognition_attendance.ipynb or .py
├── README.md
📌 How It Works
Loads known face encodings from images in the Images/ directory.

Starts webcam and processes each video frame in real time.

Detects faces in the frame using face_recognition.

Matches detected faces with known encodings.

If a match is found, displays the person's name and logs it to Attendance/YYYY-MM-DD.csv.

If no match is found, displays "Unknown".


## 📄 License
This project is licensed under the MIT License.

## 🙋‍♂️ Author
Shivi Goyal
📧 shivigoyal4321@gmail.com
🔗 LinkedIn

