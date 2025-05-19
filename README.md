# 🚦 Real-Time Traffic Light Detection using OpenCV

This project detects **traffic lights** (Red, Yellow, Green) from **static images** and **videos** using **OpenCV** and **HSV color masking**. Based on the detected color, the system displays the corresponding **action** (e.g., STOP, WAIT, START).

---

## 📌 Features

- 🎯 Detects traffic signal lights from both images and videos.
- 🎨 Uses HSV color space for accurate color detection.
- 🪞 Draws bounding boxes and displays action labels on detected lights.
- 🎬 Real-time video detection with keyboard exit.

---

## 🧪 Color Detection

Uses predefined HSV ranges for:
- 🔴 **Red** → `STOP`
- 🟡 **Yellow** → `WAIT`
- 🟢 **Green** → `START`

These ranges can be fine-tuned for different lighting conditions.

---

## 📂 File Structure

```bash
.
├── trafficsignal.jpeg       # Sample traffic light image
├── trafficsignal.mp4        # Sample traffic light video
├── traffic_light_detect.py  # Main Python script
🛠️ Requirements
Python 3.x

OpenCV

NumPy

Install dependencies:
pip install opencv-python numpy
