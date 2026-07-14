# 🫁 Lung Cancer Prediction using Multiple ML Models

An AI-powered lung cancer detection system that classifies lung CT / histopathology images into **Benign**, **Malignant**, and **Normal** categories using multiple machine learning models with an interactive full-stack web application.

---

## 📌 Overview

This project demonstrates an end-to-end machine learning workflow for automated lung cancer classification using the **IQ-OTH/NCCD Lung Cancer Dataset**. It combines deep learning and classical machine learning techniques to compare model performance while providing an intuitive web interface for real-time image prediction.

As part of this repository, I contributed to enhancing the application with a **Flask backend**, an interactive **HTML/CSS/JavaScript frontend**, model integration, documentation, and deployment workflow, allowing users to upload medical images and obtain predictions from multiple trained models through a unified interface.

---

## 🤖 Machine Learning Models

| Model | Accuracy | Precision | Recall | F1 Score |
|--------|---------:|----------:|--------:|---------:|
| **VGG16 (Transfer Learning)** | 97% | 97% | 97% | 97% |
| **KNN** | 98% | 98% | 98% | 98% |
| **SVM** | 98% | 98% | 98% | 98% |
| **Hybrid CNN-SVM** | **99%** | **99%** | **99%** | **99%** |

The models classify CT/histopathology images into:

- 🟢 Normal
- 🟡 Benign
- 🔴 Malignant

---

## ✨ Features

- Multi-model lung cancer prediction
- Interactive image upload interface
- Flask REST API for inference
- Performance comparison across all models
- Accuracy, Precision, Recall & F1 visualizations
- Responsive dark-themed UI
- Comparative analytics dashboard

---

## 🛠️ Technology Stack

**Machine Learning**
- TensorFlow
- Scikit-learn
- NumPy

**Backend**
- Flask
- Flask-CORS

**Frontend**
- HTML5
- CSS3
- JavaScript

**Libraries**
- Pillow

---

## 📂 Project Structure

```text
backend/
 ├── app.py
 ├── requirements.txt
 └── export_models_guide.py

frontend/
 ├── index.html
 ├── style.css
 └── app.js

ML Notebooks/
 ├── VGG16
 ├── KNN
 ├── SVM
 └── Hybrid CNN-SVM
```

---

## 🚀 Running the Project

### Clone Repository

```bash
git clone https://github.com/mrigankisingh123/Lung-Cancer-Prediction-using-multiple-ML-models.git
cd Lung-Cancer-Prediction-using-multiple-ML-models
```

### Start Backend

```bash
cd backend
pip install -r requirements.txt
python app.py
```

### Start Frontend

```bash
cd frontend
python -m http.server 8080
```

Open:

```
http://localhost:8080
```

---

## 🔌 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/health` | API health check |
| POST | `/predict` | Predict lung cancer class |
| GET | `/metrics` | Retrieve model performance metrics |

---

## 📊 Dataset

**IQ-OTH/NCCD Lung Cancer Dataset**

- CT scan images
- Three-class classification
- Benign, Malignant, and Normal
- Train/Test split with augmentation

---

## ⚠️ Disclaimer

This project is intended for **educational and research purposes only** and should not be used as a substitute for professional medical diagnosis.

---

# 👨‍💻 Contributor

**Mriganki Singh**

- GitHub: https://github.com/mrigankisingh123
- LinkedIn: https://www.linkedin.com/in/mriganki-singh

⭐ If you found this project useful, consider giving it a Star.
