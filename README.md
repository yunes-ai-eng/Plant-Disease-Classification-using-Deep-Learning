# 🌿 Plant Disease Classification using Deep Learning

An end-to-end Deep Learning system for automated plant leaf disease classification using Convolutional Neural Networks (CNNs). The project leverages TensorFlow and Keras to accurately identify **38 different plant diseases** from leaf images, providing an intelligent solution for early crop disease diagnosis and precision agriculture.

---

# 📌 Project Overview

Early detection of plant diseases is essential for improving crop productivity and reducing agricultural losses. Manual diagnosis requires expert knowledge and is often time-consuming, making automated disease recognition an important application of Artificial Intelligence.

This project implements a complete Deep Learning pipeline that automatically classifies plant leaf diseases using image processing and Convolutional Neural Networks (CNNs). The system was trained on a large-scale public dataset and optimized using data augmentation, early stopping, and model checkpointing techniques to achieve reliable performance.

---

# 🎯 Objectives

- Automatically classify plant leaf diseases using Deep Learning.
- Improve early disease detection for precision agriculture.
- Train a robust CNN model on large-scale image datasets.
- Reduce overfitting using data augmentation and regularization.
- Build a scalable model suitable for future deployment.

---

# 📊 Dataset

The project uses the **PlantVillage Dataset**, containing healthy and diseased plant leaf images collected under controlled conditions.

### Dataset Statistics

| Item | Value |
|------|-------|
| Training Images | **70,295** |
| Validation Images | **17,572** |
| Total Images | **87,867** |
| Number of Classes | **38 Plant Diseases** |

The dataset includes diseases affecting multiple crop species, including:

- Apple
- Corn (Maize)
- Grape
- Peach
- Pepper
- Potato
- Tomato
- Strawberry
- Soybean
- Cherry

---

# 🔄 Project Workflow

```text
Leaf Images
      │
      ▼
Image Preprocessing
      │
      ▼
Data Augmentation
      │
      ▼
CNN Training
      │
      ▼
Validation
      │
      ▼
Performance Evaluation
      │
      ▼
Model Checkpoint
      │
      ▼
Final Trained Model
```

---

# 🧠 Deep Learning Model

A custom Convolutional Neural Network (CNN) was developed using TensorFlow/Keras.

### Model Components

- Convolutional Layers
- Max Pooling Layers
- ReLU Activation
- Dropout Regularization
- Fully Connected Layers
- Softmax Output Layer

The training process includes:

- Image Augmentation
- EarlyStopping
- ModelCheckpoint
- Best Weight Restoration

---

# 📈 Model Performance

The final model achieved strong classification performance on unseen validation data.

| Metric | Result |
|--------|---------|
| Validation Accuracy | **90.5%** |
| Classes | **38** |
| Total Images | **87,867** |

The model demonstrated strong generalization capability across multiple crop diseases.

---

# 🚀 Key Features

- Automated Plant Disease Classification
- Deep Learning-based Image Recognition
- CNN Architecture
- Data Augmentation
- EarlyStopping
- Model Checkpointing
- Large-Scale Dataset Training
- High Classification Accuracy

---

# 🛠 Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Google Colab

---

# 📂 Project Structure

```text
Plant-Disease-Classification/
│
├── data/
├── notebooks/
├── models/
├── training/
├── figures/
├── requirements.txt
└── README.md
```

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yunes-ai-eng/Plant-Disease-Classification.git
```

Navigate to the project

```bash
cd Plant-Disease-Classification
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the training script

```bash
python train.py
```

---

# 🌱 Applications

This project can be extended for:

- Smart Agriculture
- Precision Farming
- Mobile Crop Disease Detection
- Edge AI Applications
- Agricultural Decision Support Systems

---

# 📈 Future Improvements

Potential future enhancements include:

- Transfer Learning using EfficientNet or ResNet
- Streamlit Web Application
- Mobile Application
- Explainable AI (Grad-CAM)
- Cloud Deployment
- REST API
- Real-Time Disease Detection
- Edge Device Optimization

---

# 📚 References

- TensorFlow Documentation
- Keras Documentation
- PlantVillage Dataset

---

# 👨‍💻 Author

**Yunes Abdulghani Mohammed Ghaleb**

**AI & Machine Learning Engineer**

📧 **Email:** alshameeri.ai.eng@gmail.com

---

# ⭐ License

This project is intended for educational, research, and portfolio purposes.

If you found this project useful, consider giving it a ⭐ on GitHub.
