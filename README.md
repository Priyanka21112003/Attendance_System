# 🎓 Face Recognition Attendance System

This is a Python-based Face Recognition Attendance System designed to automate the process of taking attendance. It uses real-time webcam input or group photos to identify and record faces with high accuracy. Attendance is saved per lecture session and stored date-wise to maintain clean, organized records.

> 🔒 **Note:** For privacy reasons, the original student images have been replaced with images of characters from the *Friends* TV show in the demo.

---

## 🛠️ Features

- ✅ Real-time face detection using webcam
- 🖼️ Attendance from uploaded group photos
- 📂 Auto-creation of daily attendance folders
- 🔒 Filters out 'Unknown', 'HOD', and 'Principal'
- 🧠 Stores attendance per lecture with a maximum of 5 sessions/day
- 💻 User-friendly GUI built with Tkinter

---

## 📦 Tech Stack

- Python
- OpenCV
- face_recognition
- Tkinter
- NumPy

---

## 🚀 How It Works

1. Face encodings are generated from images stored in the `Images/` folder.
2. Real-time video feed or group photos are processed to match faces.
3. Attendance is marked in a `.csv` file inside the `Records/<date>/` folder.
4. Duplicate attendance is avoided for each lecture session.
5. GUI provides buttons to start video, load photo, and begin new lectures.

---



