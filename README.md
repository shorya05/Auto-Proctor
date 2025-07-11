# Auto-Proctor

# 🛡️ Auto Proctor – AI-Powered Online Exam Surveillance

**Auto Proctor** is a real-time webcam-based proctoring tool designed for online exams. It continuously monitors candidates using computer vision techniques and automatically detects suspicious activities such as face mismatch, multiple faces, or absence from frame.

Built with **Python** and **OpenCV**, the system uses **Haar Cascades** for face detection and a **Local Binary Patterns Histogram (LBPH)** classifier for face recognition, ensuring quick and accurate validation.

---

## 🎯 Features

- 🎥 Real-time webcam video stream processing
- 🧑‍💻 Face detection using HaarCascade classifier
- 🧠 Face recognition using LBPH (Local Binary Pattern Histogram)
- 🔔 Warning alerts for:
  - Face not matching with registered face
  - Multiple faces detected
  - No face detected (user leaves frame)
- 📝 Logs every suspicious event with timestamp
- 📁 Stores training images and models for future recognition
- 💻 Lightweight and easy to run on most machines

---

## 🛠️ Tech Stack

| Component        | Technology            |
|------------------|------------------------|
| Language         | Python 3.x             |
| Computer Vision  | OpenCV                 |
| Face Detection   | Haar Cascades          |
| Face Recognition | LBPH (OpenCV built-in) |
| UI (Optional)    | Tkinter / CLI          |

---


