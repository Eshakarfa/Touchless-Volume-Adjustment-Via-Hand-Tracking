
# 🎚️ Hand Gesture-Based Volume Control System

Control your system volume with just your fingers using real-time hand tracking and gesture recognition!  
This project leverages **MediaPipe**, **OpenCV**, and **pycaw** to adjust your PC volume by simply changing the distance between your thumb and index finger — **no physical contact required**.

---

## 🔧 Features

- 🔍 Real-time hand detection using **MediaPipe**
- 🎯 Accurate fingertip tracking (Thumb & Index)
- 🔄 Dynamic volume adjustment via hand gesture
- 📊 Volume percentage & bar overlay on live feed
- 🧠 Smooth GUI with FPS display
- ✅ Touchless and intuitive interaction

---

## 🧰 Technologies Used

- [Python](https://www.python.org/)
- [OpenCV](https://opencv.org/) — Image Processing
- [MediaPipe](https://mediapipe.dev/) — Hand Landmark Detection
- [pycaw](https://github.com/AndreMiras/pycaw) — Audio Control for Windows
- [NumPy](https://numpy.org/) — Interpolation & Math Operations

---

## 🚀 Getting Started

### 📦 Prerequisites

Install the required Python packages:

```bash
pip install opencv-python mediapipe pycaw comtypes numpy
