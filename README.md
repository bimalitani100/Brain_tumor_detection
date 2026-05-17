# 🧠 Brain Tumor Detection using Deep Learning (VGG16)

A deep learning-based medical imaging system that detects brain tumors from MRI scans using Convolutional Neural Networks (CNNs) with transfer learning (VGG16). This project demonstrates an end-to-end AI pipeline for medical image classification.

---

## 🚀 Project Overview

Brain tumor detection is a critical task in medical imaging. This project uses deep learning to classify MRI scans into **tumor** and **no tumor** categories.

The system applies image preprocessing, data augmentation, and transfer learning to improve accuracy and generalization.

This project was built to explore how AI can support early-stage medical diagnosis and assist radiologists in decision-making.

---

## 🎯 Objectives

- Build an automated brain tumor detection system using MRI images  
- Apply transfer learning using VGG16 architecture  
- Improve classification accuracy using image preprocessing and augmentation  
- Evaluate model performance using standard ML metrics  
- Visualize training performance and predictions  

---

## 🧠 Model Architecture

- Base Model: **VGG16 (Pretrained on ImageNet)**
- Custom Layers: Fully Connected Dense Layers
- Activation Functions: ReLU, Softmax
- Optimizer: Adam
- Loss Function: Categorical Crossentropy

---

## 🧰 Tech Stack

- Python  
- TensorFlow / Keras  
- NumPy  
- OpenCV  
- Matplotlib  
- scikit-learn  

---

## 📊 Dataset

- MRI brain scan images  
- Classes:
  - Tumor
  - No Tumor  

Images were preprocessed by:
- Resizing to uniform dimensions  
- Normalization  
- Data augmentation (rotation, flipping, zooming)  

---

## ⚙️ Workflow

1. Load MRI dataset  
2. Preprocess images (resize, normalize)  
3. Apply data augmentation  
4. Load pretrained VGG16 model  
5. Fine-tune model with custom layers  
6. Train and validate model  
7. Evaluate performance  
8. Make predictions on unseen images  

---

## 📈 Model Performance

- Validation Accuracy: ~90%  
- Test Accuracy: ~98–100% (varies based on dataset split)

### Evaluation Metrics:
- Accuracy  
- Precision  
- Recall  
- F1 Score  
- Confusion Matrix  

---

## 📊 Results Visualization

The model includes:
- Training vs Validation Accuracy plots  
- Loss curves  
- Confusion matrix  
- Sample MRI predictions  

---

## 🧪 Project Structure

brain-tumor-detection/
│
├── dataset/
│ ├── tumor/
│ ├── no_tumor/
│
├── models/
│ ├── vgg16_model.h5
│
├── src/
│ ├── preprocess.py
│ ├── train.py
│ ├── predict.py
│
├── notebooks/
│ ├── training.ipynb
│
├── requirements.txt
├── README.md

---


---

## 👨‍💻 My Contributions

- Designed and implemented CNN-based classification pipeline  
- Built image preprocessing and augmentation system  
- Fine-tuned VGG16 for medical image classification  
- Evaluated model using multiple ML metrics  
- Visualized training performance and results  
- Optimized model performance for higher accuracy  

---

## 🔮 Future Improvements

- Upgrade to advanced architectures (ResNet, EfficientNet, Vision Transformers)  
- Deploy as a web application (Flask / Streamlit)  
- Expand dataset for multi-class tumor classification  
- Integrate explainable AI (Grad-CAM visualizations)  
- Improve real-world generalization using clinical datasets  

---

## ⚠️ Disclaimer

This project is for **educational and research purposes only**.  
It is not intended for real medical diagnosis or clinical use.

---

## 📫 Connect

- GitHub: https://github.com/bimalitani100  
- Portfolio: https://bimalitani100.github.io/  
- LinkedIn: https://www.linkedin.com/in/bimal-itani100/?skipRedirect=true
