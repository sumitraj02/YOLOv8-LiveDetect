# YOLOv8-LiveDetect

# 🧠 YOLOv8 Live Object Detection using Flask & IP Webcam

This is a real-time object detection web application built with **YOLOv8**, **Flask**, and **OpenCV**, using an **IP Webcam** stream as video input. The web app highlights detected objects on the live feed and provides a styled user interface with animated elements and social links.

## 🚀 Features

- 🔍 Real-time object detection with YOLOv8 (Ultralytics)
- 📱 IP Webcam support
- 🎨 Animated web interface with CSS
- 🖼️ Live video stream rendered via `<img>` tag
- 📌 Social media footer
- 🖥️ Responsive UI with custom header and logo

---

## 🛠️ Tech Stack

- Python
- Flask
- OpenCV
- Ultralytics YOLOv8
- HTML5 / Inline CSS
- IP Webcam (Android App)

---

## 📸 Project Screenshots

Here are a few screenshots of the running project:

### 🔹 Live Camera Feed & UI

<img src="YOLOv8-LiveDetect/Screenshots/Screenshot 2025-05-03 152508.png" width="400"/>
<img src="YOLOv8-LiveDetect/Screenshots/Screenshot 2025-05-03 152641.png" width="400"/>

<img src="YOLOv8-LiveDetect/Screenshots/Screenshot 2025-05-03 152758.png" width="400"/>
<img src="YOLOv8-LiveDetect/Screenshots/Screenshot 2025-05-03 153024.png" width="400"/>

---

## 🔧 How to Run the Project

### 1. Clone the Repository

git clone https://github.com/sumitraj02/YOLOv8-LiveDetect.git
cd yolov8-live-detection
### 2. Install Dependencies
pip install -r requirement.txt


### 3. Connect ip webcam
Connect Your Phone's IP Webcam
Use the IP Webcam Android app
Start the stream and note the video URL (e.g., http://192.168.1.x:8080/video)
Update the camera_url in app.py accordingly.

### 4. Run the Flask App
puthon app.py

### 5. 🌐 Access the Web App
http://localhost:5000
---
## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

