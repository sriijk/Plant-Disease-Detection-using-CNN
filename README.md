# 🌿 Plant Disease Recognition System

A web-based deep learning application that helps identify diseases in plant leaves. Built using **Streamlit**, **TensorFlow**, and a custom-trained CNN model, this project enables quick and accurate disease recognition to support farmers, agriculturists, and researchers.

---

## 📌 Overview

This system takes an image of a plant leaf as input and classifies it into one of 38 categories (including healthy). It utilizes a pre-trained TensorFlow model and a user-friendly interface created with Streamlit.

---

## 🧠 Key Features

- 🖼️ Upload plant leaf images
- 🤖 Disease prediction using CNN model
- 🔍 Classifies into 38 different disease types
- 🟢 Identifies healthy leaves too
- 🌐 Simple and clean web interface using Streamlit

---

## 🧰 Tech Stack

- **Frontend**: Streamlit
- **Backend**: Python, TensorFlow
- **Libraries**: NumPy, TensorFlow, Streamlit

---

## 📊 Dataset Details

- Total: ~87,000 RGB images
- 38 classes (diseased + healthy)
- Training set: 80%
- Validation set: 20%
- Test set: 33 images
- Dataset recreated with offline augmentation

---

## 🗃️ Project Structure

plant-disease-app/ │ ├── main.py # Streamlit app code ├── plant_disease_model.keras # Pre-trained CNN model ├── home_page.jpeg # Landing page image (banner) ├── requirements.txt # List of dependencies └── README.md # Project documentation

## Install dependencies
pip install -r requirements.txt


## Run the app
streamlit run main.py
