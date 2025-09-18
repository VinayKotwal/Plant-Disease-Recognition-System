Plant Disease Recognition System

A machine learning–based system that detects plant diseases from leaf images. The project leverages deep learning (CNNs) to classify plant health conditions and can help farmers, researchers, and agriculture experts identify crop issues early.

📌 Features

Upload leaf images for analysis.

Automatic disease detection using a trained CNN model.

Predicts multiple plant diseases with high accuracy.

Simple and user-friendly web interface (Flask).

🛠️ Tech Stack

Python 3.x

TensorFlow / Keras (for deep learning model)

Flask (for web app)

OpenCV & NumPy (for image preprocessing)

HTML / CSS / Bootstrap (for frontend)

📂 Project Structure
Plant-Disease-Recognition-System/
│
├── app.py                 # Flask app entry point
├── models/                # Trained ML/DL models (.keras, .h5)
├── templates/             # HTML files
├── static/                # CSS, JS, images
├── plant_disease.json     # Disease class mappings
└── requirements.txt       # Dependencies

🚀 How to Run

Clone the repository:

git clone https://github.com/VinayKotwal/Plant-Disease-Recognition-System.git
cd Plant-Disease-Recognition-System


Create and activate a virtual environment:

python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows


Install dependencies:

pip install -r requirements.txt


Run the Flask app:

python app.py


Open in browser:

http://127.0.0.1:5000/

📊 Dataset

Dataset used: PlantVillage Dataset (Kaggle)

Includes thousands of leaf images across multiple crops & disease categories.
