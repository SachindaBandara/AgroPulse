# AgroPulse 🌱

**Empowering Farmers with Smart Pest Management**

AgroPulse is an innovative web-based platform designed to assist farmers in identifying and managing agricultural pests efficiently using machine learning. By leveraging AI-driven pest detection, AgroPulse helps farmers take proactive measures to protect their crops and enhance agricultural productivity.

---

## 🌍 Why AgroPulse Matters

Pests are a major threat to agriculture, causing significant losses in crop yield and quality. Traditional pest control methods often rely on chemical pesticides, which can be harmful to both the environment and human health. AgroPulse aims to:
- **Reduce Crop Losses**: Early pest detection minimizes damage to crops.
- **Promote Sustainable Farming**: Encourages eco-friendly pest management techniques.
- **Empower Farmers**: Provides data-driven decision-making tools.
- **Enhance Food Security**: Contributes to a more sustainable and productive agricultural sector.

## Table of Contents 📚
- [Features](#features)
- [Tech-Stack](#techstack)
- [Installation Guide](#installation)
- [Usage](#usage)


## 🚀 Features

- **Multilingual Support**: AgroPulse supports Sinhala, Tamil, and English, making it accessible to a diverse range of farmers.
- **Pest Identification**: Uses Convolutional Neural Networks (CNNs) to detect and classify pests from images.
- **Smart Pest Management**: Provides data-driven insights and recommendations for pest control.
- **User-Friendly Interface**: Intuitive UI designed for farmers with easy navigation.
- **Secure Database**: Stores and retrieves users information securely using MongoDB.
- **Weather Forecasting**: Understanding weather conditions is crucial for effective farming. AgroPulse integrates weather forecasting features to provide:
    - **Real-time weather updates**
    - **Rainfall predictions**
    - **Temperature and humidity levels**

These insights help farmers make well-informed decisions regarding irrigation, pest control measures, and harvesting schedules.

---

## 🛠️ Tech Stack

### Frontend
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

### Backend
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)

### Database
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

### Machine Learning
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white)
![Convolutional Neural Networks](https://img.shields.io/badge/CNN-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)

---

## ⚙️ Installation Guide

### Prerequisites
Ensure you have the following installed:
- **Node.js & npm**
- **Python 3.x**
- **MongoDB**

### Backend Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/SachindaBandara/AgroPulse.git
   cd AgroPulse/backend
   ```
2. reate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Flask server:
   ```bash
   python server.py
   ```

### Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   cd ../frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. ▶️ Start the development server:
   ```bash
   npm run dev
   ```

## 🎯 Usage
1. Upload an image of the pest.
2. The system identifies the pest using CNNs.
3. Receive management recommendations.

##
<div align="center">
 ---
✨ *AgroPulse – Revolutionizing Agriculture with Smart Pest Management!* ✨
</div>
