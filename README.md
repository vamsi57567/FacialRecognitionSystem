# Facial Recognition Based Attendance Management System

**Author:** Vamsi Krishna Peeta  
**Guide:** Dr. Sibendu Samanta  
**Course:** Digital Image Processing

---

## About
A web-based attendance system that uses face recognition to automatically detect and record student attendance using webcam in real-time.

## Technologies Used
- Python
- Flask (Web Framework)
- OpenCV (Face Detection)
- KNN Algorithm (Face Recognition)
- Pandas (CSV Attendance Records)
- scikit-learn

## How to Run

### 1. Install dependencies
pip install flask opencv-python numpy scikit-learn pandas joblib

### 2. Run the app
python app.py

### 3. Open browser
http://127.0.0.1:5000

## Usage
1. **Add New User** — Enter name and ID, webcam captures face images and trains the model
2. **Take Attendance** — Webcam detects face, records name, ID and time into CSV

## Project Structure
project/
├── app.py
├── haarcascade_frontalface_default.xml
├── README.md
└── templates/
    └── home.html
