# Face Detection using OpenCV DNN 🎯

This project uses OpenCV's Deep Neural Network (DNN) module to detect faces in images.  
It loads a pre-trained Caffe model and draws bounding boxes around faces with confidence scores.

---

## 📂 What’s Inside

- `face_detection.py`: Main Python script for detecting faces using a pre-trained DNN model.
- `deploy.prototxt.txt`: Model architecture file.
- `res10_300x300_ssd_iter_140000.caffemodel`: Pre-trained weights from the ResNet SSD model.
- `example.jpg`: Example input image.
- `output.jpg`: Image with detected faces and labels drawn on it.

---

## 🧠 How It Works

1. Loads a pre-trained deep learning model (ResNet SSD) using OpenCV.
2. Converts the input image into a **blob**.
3. Runs forward pass through the DNN to get face detections.
4. Filters out detections below a confidence threshold (default 50%).
5. Draws bounding boxes and confidence scores on the image.

---

## 🔧 Requirements

- Python 3.x
- OpenCV (version 4.x recommended)
