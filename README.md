🏥 Health Assist AI – LLM-Based Medical Chatbot

An AI-powered healthcare assistant designed to provide personalized patient education, disease prediction, prescription analysis, and real-time healthcare support using Large Language Models (LLMs), Machine Learning, Natural Language Processing (NLP), and Optical Character Recognition (OCR).

📌 Project Overview

Health Assist AI is a smart healthcare platform that helps users:

Predict possible diseases based on symptoms
Analyze medical prescriptions using OCR
Chat with an intelligent AI healthcare assistant
Find nearby hospitals and pharmacies
Book doctor appointments
Connect with healthcare providers through chat/video consultation

The system is designed to improve healthcare accessibility, especially for users in remote areas.

✨ Features
🤖 AI Medical Chatbot
Intelligent chatbot powered by NLP and LLM concepts
Provides real-time medical guidance
Personalized healthcare responses
🩺 Disease Prediction
Predicts diseases based on symptoms
Uses Machine Learning models:
Random Forest
Support Vector Machine (SVM)
📄 Prescription Analysis
Upload prescriptions as images
OCR extracts:
Medicine names
Dosage instructions
Side effects
📍 Nearby Healthcare Services
Locate:
Hospitals
Clinics
Pharmacies
Integrated with Google Maps API
📞 Doctor Consultation
WhatsApp consultation
Video call support
Appointment booking system
👤 Patient Profile Management
Store:
Medical history
Symptoms
Lifestyle details
Insurance information
⭐ Feedback System
User feedback and bug reporting
Star rating support
🛠️ Technologies Used
Frontend
HTML
CSS
JavaScript
React.js
Vite
Backend
Flask
PHP
Machine Learning & NLP
TensorFlow
Keras
Scikit-learn
NLTK
spaCy
OCR & Image Processing
OpenCV
Tesseract OCR
Database
PostgreSQL
SQL Database
APIs
Google Maps API
WebRTC / Zoom API

🧠 Machine Learning Models

The system mainly uses Random Forest for disease prediction.

Why Random Forest?
High prediction accuracy
Handles complex medical datasets
Reduces overfitting
Provides confidence scores
Achievements
~92% training accuracy
Real-time symptom analysis
Top probable disease prediction

🏗️ System Architecture

The system integrates:

User Interface
NLP-based Chatbot
Disease Prediction Module
OCR Prescription Module
Database
Healthcare APIs

This creates a complete digital healthcare ecosystem.

📂 Project Modules
├── frontend/
│   ├── index.html
│   ├── login.html
│   ├── appointment.html
│   ├── feedback.html
│   ├── profile.html
│   └── styles.css
│
├── backend/
│   ├── connect.php
│   ├── register.php
│   ├── feedback_handler.php
│   ├── save_profile.php
│   └── store_appointment.php
│
├── ml_models/
│   ├── disease_prediction_model.pkl
│   ├── symptom_dataset.csv
│   └── training_notebook.ipynb
│
├── ocr/
│   └── prescription_scanner.py
│
├── pharmacy/
│   └── pharmacy.js
│
└── README.md
⚙️ Installation
1️⃣ Clone Repository
git clone https://github.com/your-username/health-assist-ai.git
cd health-assist-ai
2️⃣ Install Python Dependencies
pip install -r requirements.txt
3️⃣ Run Flask Backend
python app.py
4️⃣ Start Frontend

If using Vite + React:

npm install
npm run dev
💻 System Requirements
Hardware
Intel Core i5 or higher
8GB RAM
50GB Storage
Software
Python 3.x
Windows / Linux / macOS
VS Code / Jupyter Notebook

🔒 Security Features
User authentication
Secure data handling
Protected medical records
Input validation
Secure database storage

🧪 Testing

The system was tested using:

Unit Testing
Disease prediction accuracy
OCR extraction validation
API response validation
Integration Testing
Frontend ↔ Backend communication
OCR ↔ NLP ↔ ML workflow
Functional Testing
Symptom prediction
Prescription upload
Chatbot responses
Appointment booking

📈 Future Enhancements
Multi-language chatbot support
Voice assistant integration
Deep learning disease diagnosis
Cloud deployment
Electronic Health Record (EHR) integration
Mobile application support
📜 License

This project is developed for academic and educational purposes.

