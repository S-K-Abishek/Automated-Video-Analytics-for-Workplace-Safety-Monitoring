# Automated Video Analytics for Workplace Safety Monitoring

This script is a video processing tool that uses the YOLOv5 object detection model to detect specified objects in a video. It allows the user to define a polygonal region of interest (ROI) and detects if a person is inside it. If a person is detected, an alarm sound is played and photos of the detected image are saved. The script also displays the video feed with the detected objects and their labels. This tool can be used for security purposes. The script requires the installation of OpenCV, Pygame, and PyTorch libraries.

## 📦 Features
- Polygonal ROI creation via mouse click
- Real-time person detection using pretrained YOLOv5s model
- Alarm sound on person detection inside ROI
- Snapshot saving of detected persons
- Console log alerts and visual overlays

## 🖱️ How to Interact with the ROI Tool

- 🟢 **Left-Click** – Add a point to define the polygonal **Region of Interest (ROI)** on the video frame.  
- 🔴 **Right-Click** – **Reset** the polygon selection and start over.  
- ❌ **Press `Q`** – Exit the video display and stop the detection process.

> ⚠️ **Note:** Define at least **4 points** to complete the polygon and activate detection inside the ROI.


## 🧠 Model

The model used: `yolov5s.pt`  
[YOLOv5 GitHub Repository](https://github.com/ultralytics/yolov5)

## 📜 Research

This implementation is based on the following research paper:

**[Published research paper](https://ijarsct.co.in/Paper19901.pdf)**

## 🎥 Project Presentation

A detailed visual presentation of this project is available here:

[📊 Workplace Safety Monitoring - Project Slides](Presentation.pptx)

## ⚠️ Important Notes

> Do not forget to change the paths of the alarm sound, detected photos, and test videos depending on how you store the script.

---

Made with 🛡️ for workplace safety monitoring.
