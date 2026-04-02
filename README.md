#  AI-Based Dental Radiograph Analysis System

An AI-powered system that analyzes panoramic dental X-ray images (OPG) to automatically detect, segment, and classify teeth and dental conditions using deep learning techniques.

---

##  Features

-  Automatic tooth segmentation from OPG images  
-  Tooth numbering using FDI system (1–32)  
-  Detection of missing, impacted, and extra teeth  
-  Classification of dental conditions:
  - Normal  
  - Cavity  
  - Fillings  
  - Impacted Tooth  
  - Implant  
-  Anomaly detection (bone loss, peri-implantitis)  
-  Interactive dashboard for visualization  
-  Downloadable diagnostic reports  

---

##  System Overview

The system follows a complete pipeline:

1. Upload dental X-ray (OPG image)  
2. Tooth segmentation using deep learning  
3. Assign FDI tooth numbers  
4. Detect missing or impacted teeth  
5. Classify dental conditions  
6. Detect anomalies (bone loss, infections)  
7. Display results in dashboard  

---

##  Models Used

- **Segmentation:** Segment Anything Model (SAM) / U-Net  
- **Classification:** ResNet-50 (pretrained)  
- **Object Detection:** YOLOv8 / Faster R-CNN (optional)  
- **Anomaly Detection:** Autoencoders  

---

## Tech Stack

- Python  
- TensorFlow / Keras  
- PyTorch  
- OpenCV  
- NumPy  
- Matplotlib  
- Gradio  
- ReportLab  

---



 
