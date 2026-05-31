# 🌿 GreenScan: Intelligent Plant Disease Classification

## 📌 Project Overview

GreenScan is an AI-powered plant disease detection system designed to automate the identification and classification of plant leaf diseases using advanced Deep Learning techniques.

The project utilizes a Vision Transformer (ViT) architecture combined with hyperspectral-inspired image enhancement to accurately classify plant diseases from leaf images. The system is deployed as a web-based application, allowing users to upload plant leaf images and receive instant disease predictions with confidence scores.

This project was developed as part of a research study focused on improving disease management in agriculture through intelligent image analysis and precision farming technologies.

---

## 🎯 Objective

The primary objectives of this project are:

* Detect plant diseases automatically from leaf images
* Improve classification accuracy using Vision Transformers (ViT)
* Enhance disease detection through hyperspectral-inspired feature extraction
* Reduce dependency on manual disease inspection
* Provide a user-friendly web interface for real-time disease analysis
* Support precision agriculture and sustainable farming practices

---

## 🛠️ Tech Stack

### Programming Languages

* Python

### Deep Learning & AI

* Vision Transformer (ViT)
* TensorFlow / PyTorch
* Transformers Library

### Image Processing

* OpenCV
* PIL

### Web Development

* Flask / FastAPI
* HTML
* CSS
* JavaScript

### Development Environment

* Google Colab
* Jupyter Notebook

---

## 🧠 Methodology

The proposed system follows the workflow:

**Input Image → Preprocessing → Hyperspectral Feature Enhancement → Vision Transformer (ViT) → Disease Classification → Prediction**

### Data Preprocessing

* Image Resizing (224 × 224)
* Normalization
* Noise Reduction
* Data Augmentation

  * Rotation
  * Flipping
  * Scaling
  * Brightness Adjustment

### Feature Extraction

* Patch Embedding
* Positional Encoding
* Multi-Head Self Attention
* Transformer Encoder Layers

### Classification

The extracted features are processed through a Vision Transformer architecture to classify healthy and diseased plant leaves across multiple categories.

---

## 📂 Dataset

The project utilizes the **PlantVillage Dataset**, containing thousands of labeled images of healthy and diseased plant leaves across multiple crop species.

Dataset characteristics:

* Multi-class classification problem
* RGB leaf images
* Healthy and diseased samples
* Training and testing split
* Data augmentation applied for improved generalization

---

## ✨ Features

### ✅ Plant Disease Detection

* Automatic disease classification
* Multi-class prediction support

### ✅ Vision Transformer Based Learning

* Global contextual feature extraction
* Self-attention mechanism

### ✅ Hyperspectral-Inspired Enhancement

* Improved disease pattern detection
* Enhanced feature representation

### ✅ Web-Based Interface

* Easy image upload
* Real-time predictions
* Confidence score display

### ✅ Agricultural Decision Support

* Early disease identification
* Reduced crop loss
* Improved farm management

---

## 📊 Model Performance

| Metric    | Score  |
| --------- | ------ |
| Accuracy  | 98.7%  |
| Precision | 98.80% |
| Recall    | 98.68% |
| F1-Score  | 98.68% |

The proposed Vision Transformer-based approach outperformed several traditional CNN and hybrid deep learning models in plant disease classification tasks.

---

## 🌐 Web Application Workflow

1. User uploads a plant leaf image
2. Image preprocessing is performed
3. Vision Transformer analyzes the image
4. Disease prediction is generated
5. Confidence score is displayed
6. Results are presented through the web interface

---

## 📈 Experimental Results

Key findings from the project:

* High classification accuracy across multiple disease classes
* Strong generalization capability through augmentation techniques
* Effective disease recognition under varying image conditions
* Improved performance through hyperspectral-inspired feature enhancement
* Successful deployment as a real-time web application

---

## 🚀 Future Improvements

* Mobile application deployment
* IoT sensor integration
* Drone-based crop monitoring
* Edge AI implementation
* Lightweight Vision Transformer optimization
* Real-time field disease detection
* Large-scale agricultural monitoring systems

---

## 📄 Research Contribution

This project contributes to the field of Precision Agriculture through:

* Vision Transformer-based disease classification
* Hyperspectral-inspired feature enhancement
* Automated plant disease diagnosis
* Real-time web deployment for agricultural applications

---

## 👩‍💻 Authors

**Divya R. Pichika**,
**Saniya Ansari**,
**Nandini Bandekar**

## 👩‍💻 Faculty Mentor

**Prof. Priyanka Shingane**

Department of Information Technology
Ramrao Adik Institute of Technology (RAIT)
D. Y. Patil Deemed to be University

