# 🦠 COVID-19 Image Classification using VGG16

This project uses Transfer Learning with VGG16 to classify chest X-ray images into:

- COVID-19
- Normal
- Viral Pneumonia

## 📂 Dataset
COVID-19 Image Dataset from Kaggle

## 🧠 Model
- Pretrained VGG16 (ImageNet weights)
- GlobalAveragePooling2D
- BatchNormalization
- Dense (512, ReLU)
- Dropout (0.5)
- Output layer (Softmax)

## ⚙️ Training Details
- Optimizer: Adamax
- Loss: Categorical Crossentropy
- Image Size: 224x224
- Batch Size: 32
- EarlyStopping applied

## 📊 Results
- Training & Validation Accuracy curves
- Confusion Matrix
- Classification Report

## 📁 Files Included
- model_VGG.h5
- training_curves.png
- confusion_matrix.png
- Notebook

## 🚀 Future Improvements
- Fine-tuning VGG16 layers
- Add Grad-CAM visualization
- Deploy using Streamlit

---

👨‍💻 Developed by Kareem Hamdy
