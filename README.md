# 🐔 Poultry Disease Classification Using Deep Learning

This project is a deep learning-based web application that classifies poultry diseases from chicken images. It leverages **Transfer Learning** using the **VGG16** architecture with image data sourced from Kaggle, and integrates the model into a web application using **Flask**. The system allows users to upload an image of a chicken, and returns a prediction of the disease class in real-time.

---



## ✨ Features

- 🧠 VGG16-based transfer learning model
- 📸 Accepts image uploads (JPG, PNG)
- 🚥 Predicts one of multiple poultry diseases
- 📊 Integrated prediction through web UI
- 🛠️ Easy to deploy using Flask on localhost or cloud
- 📁 Modular folder structure for maintainability

---

## 🧰 Tech Stack

| Layer       | Tools Used                        |
|-------------|-----------------------------------|
| Language    | Python 3.9+                       |
| Framework   | Flask                             |
| ML Framework| TensorFlow / Keras                |
| Frontend    | HTML5, CSS3                       |
| Deployment  | Localhost, Render, or Replit      |
| IDEs        | Google Colab, Jupyter Notebook    |

---

## 📦 Dataset

- **Name**: [Poultry Diseases Image Dataset](https://www.kaggle.com/datasets/chandrashekarnatesh/poultry-diseases)
- **Size**: 2.7 GB+
- **Classes**: Coccidiosis, Salmonella, Newcastle Disease, Healthy
- **License**: MIT License (Free to use)

---

## 📁 Project Structure
│
├── app.py # Flask web application
├── templates/
│ └── index.html # HTML file for image upload & UI
├── static/uploads/ # Folder to store uploaded images
├── model/
│ ├── poultry_model.ipynb # Jupyter Notebook (VGG16 training)
│ └── predict_model.py # Python script to load/predict from model
├── data/ # Sample images or preprocessed data
├── documents/ # Project planning, DFDs, Sprint docs, etc.
├── requirements.txt # Python dependencies
└── README.md # You're reading it!


A project that to work with  smartinternz!! to upskill!
