# 🎯 YOLOv8 Object Detection GUI

<div align="center">

![Python](https://img.shields.io/badge/Python-3.9.10-blue.svg)
![YOLOv8](https://img.shields.io/badge/YOLOv8-Ultralytics-green.svg)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-red.svg)
![GUI](https://img.shields.io/badge/Desktop-GUI-orange.svg)

### 🚀 Real-Time Object Detection with an Interactive Desktop Interface

Detect and visualize objects in images, videos, and live webcam streams using the power of **YOLOv8** combined with a user-friendly **Python GUI**.

</div>

---

## 📌 Project Overview

This project provides a modern graphical user interface (GUI) for performing object detection using the **YOLOv8 Deep Learning Model**. Instead of running detection through command-line scripts, users can easily upload images, select videos, or start webcam detection directly from the application.

The system leverages YOLOv8's state-of-the-art object detection capabilities to identify multiple objects in real time with high accuracy and speed.

---

## 💡 Project Idea

Traditional object detection systems often require command-line knowledge and technical expertise. This project bridges that gap by offering a simple and intuitive GUI where users can:

✅ Upload images for instant detection

✅ Analyze recorded videos

✅ Detect objects from live webcam feeds

✅ View confidence scores and bounding boxes

✅ Save processed results

The goal is to make AI-powered computer vision accessible to everyone—from students and researchers to developers and hobbyists.

---

## ✨ Features

### 🖼️ Image Detection

* Upload image files
* Detect multiple objects
* Display confidence scores
* Save detection results

### 🎥 Video Detection

* Process local video files
* Frame-by-frame object tracking
* Real-time visualization

### 📷 Live Webcam Detection

* Real-time object detection
* Instant bounding box rendering
* Low-latency performance

### 🖥️ User-Friendly GUI

* Easy navigation
* Interactive controls
* No command-line interaction required

### ⚡ High Performance

* Powered by YOLOv8
* Optimized inference speed
* Supports CPU and GPU execution

---

## 🛠️ Technologies Used

| Technology     | Purpose                   |
| -------------- | ------------------------- |
| Python 3.9.10  | Core Programming Language |
| YOLOv8         | Object Detection Model    |
| OpenCV         | Image & Video Processing  |
| Tkinter / PyQt | GUI Development           |
| NumPy          | Numerical Computation     |
| Ultralytics    | YOLOv8 Framework          |

---

## 📂 Project Structure

```bash
YOLOv8-Object-Detection-GUI/
│
├── models/
│   └── yolov8n.pt
│
├── images/
│
├── videos/
│
├── output/
│
├── gui.py
├── detector.py
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/YOLOv8-Object-Detection-GUI.git

cd YOLOv8-Object-Detection-GUI
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
```

### 3️⃣ Activate Environment

**Windows**

```bash
venv\Scripts\activate
```

**Linux / Mac**

```bash
source venv/bin/activate
```

### 4️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run Application

```bash
python gui.py
```

The GUI window will launch, allowing you to:

* Select Images
* Open Videos
* Start Webcam Detection
* Save Detection Outputs

---

## 🧠 YOLOv8 Detection Workflow

```text
Input Image/Video/Webcam
          │
          ▼
   YOLOv8 Model
          │
          ▼
 Object Detection
          │
          ▼
 Bounding Boxes
 Confidence Scores
          │
          ▼
   GUI Visualization
```

---

## 📊 Applications

* Smart Surveillance Systems
* Traffic Monitoring
* Security Analytics
* Industrial Automation
* Educational AI Projects
* Retail Inventory Tracking
* Wildlife Monitoring

---

## 📸 Sample Output

```text
Person      98%
Car         95%
Dog         92%
Bottle      88%
```

Detected objects are highlighted with colored bounding boxes and confidence scores.

---

## 🚀 Future Enhancements

* Multi-object Tracking
* Face Detection Module
* Custom Model Training Support
* Dark Mode GUI
* Cloud Deployment
* Object Counting Analytics
* Export Detection Reports

---

## 🤝 Contribution

Contributions are welcome!

1. Fork the repository
2. Create a feature branch
3. Commit changes
4. Push updates
5. Open a Pull Request

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

Developed using **YOLOv8**, **OpenCV**, and **Python 3.9.10** to make real-time object detection simple, efficient, and accessible through a modern GUI interface.

⭐ If you found this project useful, don't forget to star the repository!
