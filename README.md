# Facial Recognition Based Attendance Management System

**Author:** Vamsi Krishna Peeta  
**Guide:** Dr. Sibendu Samanta

---

## Requirements

Install dependencies:
```bash
pip install flask opencv-python numpy scikit-learn pandas joblib
```

Download the Haar Cascade file:
```bash
wget https://raw.githubusercontent.com/opencv/opencv/master/data/haarcascades/haarcascade_frontalface_default.xml
```

## Project Structure

```
project/
├── app.py
├── haarcascade_frontalface_default.xml
├── templates/
│   └── home.html
├── static/
│   └── faces/
│       └── <username_id>/
│           └── *.jpg
└── Attendance/
    └── Attendance-mm_dd_yy.csv
```

## How to Run

```bash
python app.py
```

Then open your browser at: `http://127.0.0.1:5000`

## Usage

1. **Add New User** — Enter name and ID, system captures 10 face images via webcam and trains the KNN model automatically.
2. **Take Attendance** — System opens webcam, detects and identifies faces, logs attendance to a CSV file with name, ID, and timestamp.

---

## How to Push to GitHub

```bash
# 1. Initialize git repo (skip if already done)
git init

# 2. Add all files
git add app.py templates/home.html README.md

# 3. Commit
git commit -m "Facial Recognition Attendance System - Vamsi Krishna Peeta"

# 4. Add your GitHub repo as remote
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git

# 5. Push
git push -u origin main
```

> Replace `YOUR_USERNAME` and `YOUR_REPO_NAME` with your actual GitHub username and repository name.
