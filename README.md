# 🧠 MRI TumorSift
### AI-Powered Brain Tumor Classification using DenseNet121 Transfer Learning

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/TensorFlow-2.x-FF6F00?style=for-the-badge&logo=tensorflow">
  <img src="https://img.shields.io/badge/Keras-Deep%20Learning-D00000?style=for-the-badge&logo=keras">
  <img src="https://img.shields.io/badge/OpenCV-Image%20Processing-5C3EE8?style=for-the-badge&logo=opencv">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge">
</p>

---

## 📖 Overview

**MRI TumorSift** is an AI-powered medical imaging application designed to classify brain MRI scans into different tumor categories using **Transfer Learning** with **DenseNet121**.

The model automatically extracts high-level features from MRI scans and predicts the corresponding tumor class, providing an intelligent decision-support system for early diagnosis and medical research.

---

## ✨ Key Features

- 🧠 Brain MRI Tumor Classification
- 🚀 DenseNet121 Transfer Learning
- 📈 Image Data Augmentation
- ⚡ High Accuracy Deep Learning Model
- 📊 Automated Model Evaluation
- 💾 Save & Reload Trained Models
- 🔍 Predict Tumor Type from New MRI Images
- 🌐 Streamlit-based Interactive Web Application

---

# 🏗️ System Workflow

```text
              Brain MRI Image
                     │
                     ▼
         Image Preprocessing
                     │
                     ▼
        Data Augmentation Pipeline
                     │
                     ▼
      DenseNet121 Feature Extractor
                     │
                     ▼
      Custom CNN Classification Head
                     │
                     ▼
         Softmax Probability Layer
                     │
                     ▼
        Brain Tumor Classification
```

---

# 🧠 Model Architecture

The project leverages **Transfer Learning** using **DenseNet121** pretrained on ImageNet.

The architecture consists of:

- DenseNet121 Backbone
- Fine-Tuning Layers
- Additional Convolution Layers
- Global Average Pooling
- Dropout Layer
- Fully Connected Dense Layer
- Softmax Output Layer

---

# 📂 Project Structure

```
MRI_TumorSift
│
├── Dataset
│   ├── Training
│   └── Testing
│
├── Model_Building.py
├── Streamlit_Deployment.py
└── README.md
```

---

# 🛠️ Tech Stack

| Category | Technologies |
|----------|--------------|
| Language | Python |
| Deep Learning | TensorFlow, Keras |
| CNN Architecture | DenseNet121 |
| Image Processing | OpenCV, PIL |
| Numerical Computing | NumPy |
| Data Augmentation | ImageDataGenerator |
| Deployment | Streamlit |

---

# 📊 Dataset Structure

```
Dataset
│
├── Training
│   ├── Glioma
│   ├── Meningioma
│   ├── Pituitary
│   └── No Tumor
│
└── Testing
    ├── Glioma
    ├── Meningioma
    ├── Pituitary
    └── No Tumor
```

---

# ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/AVarshini05/MRI_TumorSift.git
```

### Navigate

```bash
cd MRI_TumorSift
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate

Windows

```bash
venv\Scripts\activate
```

Linux/Mac

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

# 🚀 Train the Model

```bash
python Model_Building.py
```

During training the model:

- Loads MRI Dataset
- Performs Data Augmentation
- Fine Tunes DenseNet121
- Evaluates Test Accuracy
- Saves Trained Model

---

# 🔬 Predict New MRI Images

```python
from tensorflow.keras.models import load_model

model = load_model("MODEL.h5")

prediction = model.predict(image)
```

The output represents the predicted brain tumor category.

---

# 📈 Future Enhancements

- ✅ Grad-CAM Explainable AI
- ✅ Brain Tumor Segmentation
- ✅ Faster Inference
- ✅ FastAPI Backend
- ✅ Docker Deployment
- ✅ Cloud Deployment
- ✅ Mobile Application
- ✅ Medical Report Generation using AI

---

# 💡 Applications

- Clinical Decision Support
- Medical Imaging Research
- Computer-Aided Diagnosis (CAD)
- Healthcare AI Systems
- Educational Demonstrations
- Medical AI Research

---

# 📚 Technologies Used

- Python
- TensorFlow
- Keras
- DenseNet121
- NumPy
- OpenCV
- PIL
- Streamlit

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

# 📜 License

This project is licensed under the MIT License.

---

# 👩‍💻 Author

**Varshini Anupolu**



---

## ⭐ If you found this project useful...

Give this repository a **⭐ Star** and consider **Forking** it to support future development.
