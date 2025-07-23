# ✉️ Spam Detection System

A machine learning-powered spam detection system that classifies SMS or email messages as **Spam** or **Not Spam** using natural language processing techniques. This project combines an SVM classifier with TF-IDF vectorization and is deployed via a simple Flask web app.

---

## 📑 Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Results](#results)
- [License](#license)
- [Author](#author)
- [Acknowledgements](#acknowledgements)

---

## 🧠 Overview

This prototype demonstrates a text classification model that accurately identifies spam messages using natural language processing and machine learning. It includes model training, evaluation, and deployment through a Flask interface for real-time predictions.

---

## 📊 Dataset

- **Source**: [Kaggle - SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
- **Attributes**: Label (`spam` or `ham`), Message Text

---

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- Flask
- Scikit-learn
- Pandas & NumPy
- TF-IDF Vectorization
- HTML (for frontend)

---

## 🧰 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/spam-detection-system.git
   cd spam-detection-system
2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
2. **Run the Flask app**
   ```bash
   python app.py
   
## 🚀 Usage

- Enter an SMS or email message in the form.

- Click the Predict button.

- The system will classify the message as Spam or Not Spam.

## ⭐ Features

- Pre-trained SVM classifier with TF-IDF vectorization

- Web interface using Flask

- Real-time spam prediction

- Clean and modular codebase

## 📈 Results

- Achieved high precision and recall on validation data

- Suitable for integration into SMS/email platforms

- Fast and efficient prediction using saved models

## 📄 License

This project is licensed under the MIT License.

## 👨‍💻 Author
**Nitin Gutpa**

## 🙏 Acknowledgements

Kaggle Dataset by UCI ML Repository

Scikit-learn Documentation

Flask Web Framework
