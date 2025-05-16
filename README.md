# 🔍 Image-Based Object Detection with YOLOv3-tiny and OpenCV

This project demonstrates object detection in static images using **YOLOv3-tiny** and **OpenCV** in Python. The model detects and labels multiple objects with bounding boxes, using pretrained weights trained on the COCO dataset.

## 📷 Example Output

![Detected Output](Image/img1.jpg)
![Detected Output](Image/img7.jpg)

------
## 📷 Example Output

### 🖼️ Example 1  
<img src="Image/img1.jpg" width="400" style="margin-right: 20px;"/>

---

### 🖼️ Example 2  
<img src="Image/img7.jpg" width="400"/>

---

## 📷 Example Output

<p float="left">
  <div align="center">
    <img src="Image/img1.jpg" width="400"/>
    <p><strong>Example 1</strong></p>
  </div>
  &nbsp;&nbsp;&nbsp;
  <div align="center">
    <img src="Image/img7.jpg" width="400"/>
    <p><strong>Example 2</strong></p>
  </div>
</p>

-----------------
## 📷 Example Output

<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="Image/img1.jpg" width="100%">
        <p><strong>Example 1</strong></p>
      </td>
      <td style="width: 40px;"></td> <!-- spacing -->
      <td align="center">
        <img src="Image/img7.jpg" width="100%">
        <p><strong>Example 2</strong></p>
      </td>
    </tr>
  </table>
</div>

-----------------
## ✅ Features

- Object detection using **YOLOv3-tiny**
- Pre-trained on the **COCO dataset**
- Filter detections by **confidence threshold**
- **Non-Maximum Suppression (NMS)** to remove duplicate boxes
- Display object **labels and confidence scores**
- Output saved with bounding boxes and annotations

---

## 🧰 Technologies Used

- Python
- OpenCV
- Matplotlib
- YOLOv3-tiny
- COCO Dataset

---

## 📁 Folder Structure

YOLO_Object_Detection/
│
├── yolov3-tiny.cfg
├── yolov3-tiny.weights
├── coco.names
├── Image/
│ ├── Image1.jpeg # Input image
│ └── img.jpg # Output image with detection
├── object_detection.ipynb # Main code file
└── README.md # This file
