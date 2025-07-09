# AI-Smart-Health-Card-System
A centralized AI-powered health record system using QR codes and ML/DL models for disease prediction, patient risk analysis, and real-time public health monitoring for doctors and government authorities.

------------------------------------------------------------------------------------------------------------------------------------------
AI Smart Health Card System

A centralized AI-powered health record platform using QR codes and ML/DL models for disease prediction, patient risk analysis, and real-time public health monitoring. Designed for use by doctors, patients, and government health departments.

---

 🧠 Key Features

- 🔐 QR-based Unique Health ID for every patient  
- 🩺 Doctor Portal to record diagnosis, prescription, and symptoms  
- 🧾 Digital Health Card for tracking complete medical history  
- 🤖 AI/ML Prediction Modules:  
  - Symptom-to-Disease (NLP + BERT)  
  - Risk Score Predictor (DNN)  
  - Image-based Diagnosis (CNN on X-ray, skin, etc.)  
  - Outbreak Forecasting (LSTM)  
- 📊 Government Dashboard for regional disease analysis and health intelligence  

---

 🚀 Tech Stack

- Frontend: React.js / Flutter / Streamlit  
- Backend: Flask / Node.js  
- ML/DL Models: BERT, CNN, DNN, LSTM (TensorFlow / PyTorch)  
- Database: MongoDB / PostgreSQL  
- Others: OpenCV, Transformers, scikit-learn, QR Code Generator  

---

 📁 Folder Structure


smart-health-ai-system/
├── qr_module/                #Generate & scan QR code linked to patient ID
├── patient_interface/        #View health history, upload symptoms/images
├── doctor_portal/            #Input diagnosis, prescriptions, symptoms
├── ml_models/                #AI/ML models (BERT, CNN, DNN)
│   ├── disease_predictor_bert.pt
│   ├── cnn_skin_model.h5
│   └── diabetes_risk_dnn.pkl
├── chatbot/                  #Medical assistant chatbot (optional)
├── analytics_dashboard/      #Government dashboard with disease stats
├── api/                      #Backend APIs for frontend integration
└── README.md



---

 📊 Government Dashboard Features

- View disease trends by city/district/state  
- Real-time case count and severity map  
- Predict outbreak risk with time-series analysis  
- Filter by age, gender, disease type  

---

 🛠 Setup Instructions

1. Clone the repository:

git clone https://github.com/24MCA003/AI-Smart-Health-Card-System.git
cd AI-Smart-Health-Card-System


2. Install dependencies:

pip install -r requirements.txt


3. Run the backend server:

python app.py


4. Run Streamlit dashboard (optional):

streamlit run dashboard/app.py


---

 📌 Future Scope

 Integration with Ayushman Bharat / Government e-Health APIs
 Add wearable/IoT device health tracking (heart rate, BP, glucose)
 Prescription scanning using OCR + NLP
 Role-based mobile app for doctors, patients, and health officers

---

 👨‍💻 Developed by

Nikesh Barodiya
MCA Student | Software Developer | AI & HealthTech Enthusiast

---

 📜 License

This project is licensed under the MIT License. See `LICENSE` file for more info.

---
