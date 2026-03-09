# 🚗 Real-Time Adaptive Lane Detection for Indian Roads

🎓 **Final Capstone Project**

A Computer Vision based lane detection system designed specifically for the **complex and diverse conditions of Indian roads**.  
The system processes image and video frames to detect road lane markings in real time, improving driving safety and supporting **Autonomous Driving Systems and ADAS (Advanced Driver Assistance Systems).**

---

## 👥 Team Members

| Name | Hall Ticket No |
|-----|-----|
| Kanchu Kushi Raj | 2203A52030 |
| Kolluri Aniritha | 2203A52032 |
| Nalla Jeshwanth Kumar | 2203A52043 |
| Ranga Vihasith | 2203A52049 |

---

## 🛠 Languages & Technologies

![Python](https://img.shields.io/badge/Python-Programming-blue?style=for-the-badge&logo=python)
![OpenCV](https://img.shields.io/badge/OpenCV-ComputerVision-green?style=for-the-badge&logo=opencv)
![NumPy](https://img.shields.io/badge/NumPy-NumericalComputing-purple?style=for-the-badge&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange?style=for-the-badge&logo=plotly)
![Jupyter](https://img.shields.io/badge/JupyterNotebook-Development-yellow?style=for-the-badge&logo=jupyter)

---

# 📌 Project Overview

Lane detection plays a crucial role in **autonomous driving and advanced driver assistance systems (ADAS)**.  
It enables vehicles to recognize road boundaries and maintain proper lane discipline.

However, **Indian road conditions present unique challenges**, including:

- Faded or missing lane markings
- Irregular lane structures
- Diverse traffic environments
- Varying lighting conditions
- Curved and broken lanes

To address these challenges, this project proposes a **Real-Time Adaptive Lane Detection System** using computer vision techniques that can effectively detect lane lines under complex road conditions.

---

# ⚙️ System Pipeline

The lane detection system follows a structured pipeline:

### 1️⃣ Image Preprocessing
- Convert input image/video frame to **grayscale**
- Apply **Gaussian blur** to reduce noise

### 2️⃣ Edge Detection
- Use **Canny Edge Detection** to identify strong edges representing lane boundaries.

### 3️⃣ Region of Interest (ROI)
- Mask unnecessary regions to focus only on the **road area**.

### 4️⃣ Lane Line Detection
- Apply **Hough Transform** to detect lane lines from edges.

### 5️⃣ Lane Overlay
- Detected lane lines are **drawn on the original frame** for visualization.

---

# ✨ Key Features

✔ Real-time lane detection from video frames  
✔ Handles **noise and lighting variations**  
✔ Works with **curved road lanes**  
✔ Designed specifically for **Indian road environments**  
✔ Uses efficient **computer vision algorithms**  
✔ Visual lane overlay on original video frames

---

# 🧠 Technical Skills Demonstrated

This project demonstrates practical implementation of:

- Computer Vision
- Image Processing
- Edge Detection Algorithms
- Hough Transform
- Video Frame Processing
- Data Visualization
- Autonomous Driving Concepts

---

