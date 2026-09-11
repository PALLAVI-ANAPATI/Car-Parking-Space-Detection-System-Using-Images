# 🚗 Car Parking Space Detection
## 📌Description
A Deep Learning-based Smart Parking Slot Detection System that uses RT-DETR and YOLOv8 to detect and classify parking slots as Occupied or Vacant.The system processes parking images and provides visual detection results and automated slot counts through a Streamlit web application.

----
## 📂 Dataset
**PKLot Dataset** - [🔗 Kaggle Source](https://www.kaggle.com/cashutosh/gender-classification-dataset)

----
## 🛠️ Dependencies
•  Python \
•  Ultralytics \
•  RT-DETR \
•  YOLOv8 \
•  OpenCV \
•  NumPy \
•  Pillow \
•  Streamlit 

### 📥 Install Dependencies:
```sh
pip install streamlit ultralytics opencv-python-headless numpy pillow
```
----
## 🏗️ Model Architectures
•  RT-DETR: Transformer-based real-time object detection architecture for detecting parking slots. \
•  YOLOv8: CNN-based object detection model used for fast parking-slot detection and classification. \
•  The trained model generates bounding boxes and class predictions for each parking slot.

----
## ⚙️ Working
1.	Collect parking images and XML annotations. 
2.	Convert XML → COCO JSON → YOLO labels. 
3.	Create a YAML configuration containing dataset paths and class names. 
4.	Train the RT-DETR/YOLOv8 detection model. 
5.	Upload a parking image through the Streamlit application. 
6.	Detect and classify parking slots as Occupied or Vacant. 
7.	Display bounding boxes and calculate free, occupied, and total slots.

----
## 🚀 Future Enhancements
•	Real-time CCTV/video-based parking detection \
•	Live webcam monitoring \
•	Cloud deployment and database integration

----
## Model Demo

