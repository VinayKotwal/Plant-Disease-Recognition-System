# 🌱 Plant Disease Recognition System  

[![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)](https://www.python.org/)  
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow)](https://www.tensorflow.org/)  
[![Flask](https://img.shields.io/badge/Flask-web--framework-black?logo=flask)](https://flask.palletsprojects.com/)  

A deep learning–based system to automatically detect plant diseases from leaf images.  
This project helps farmers and researchers **identify plant health issues early** and take preventive action.  

---

## 📑 Table of Contents  
- [✨ Features](#-features)  
- [🛠️ Tech Stack](#%EF%B8%8F-tech-stack)  
- [📂 Project Structure](#-project-structure)  
- [⚙️ Installation & Setup](#%EF%B8%8F-installation--setup)  
- [📊 Dataset](#-dataset)  
- [📷 Screenshots](#-screenshots)  
- [🚀 Future Improvements](#-future-improvements)  
- [🤝 Contributing](#-contributing)  
- [👨‍💻 Author](#-author)  
- [📜 License](#-license)  

---

## ✨ Features  
- Upload a leaf image for instant analysis.  
- Automatic classification of plant diseases using a trained CNN model.  
- Supports multiple plant species and disease categories.  
- Lightweight Flask web interface for easy access.  

---

## 🛠️ Tech Stack  
- **Programming Language**: Python 3.x  
- **Deep Learning**: TensorFlow / Keras  
- **Web Framework**: Flask  
- **Image Processing**: OpenCV, NumPy  
- **Frontend**: HTML, CSS, Bootstrap  

---

## 📂 Project Structure  
```bash
Plant-Disease-Recognition-System/
│
├── app.py                  # Flask application entry point
├── models/                 # Trained ML/DL models (.keras, .h5)
├── templates/              # HTML templates
├── static/                 # CSS, JS, and image assets
├── plant_disease.json      # Disease class mappings
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
