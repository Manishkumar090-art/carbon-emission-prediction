# 🚗 Carbon Emission Prediction System

A Machine Learning-based web application that predicts **CO₂ emissions of vehicles** using various input features such as engine size, fuel type, cylinders, and fuel consumption.

---

## 📌 Project Overview

This project estimates vehicle carbon emissions using a trained ML model. It helps:

- 🚘 Users understand environmental impact  
- 🏭 Manufacturers analyze vehicle efficiency  
- 🌍 Promote eco-friendly decisions  

---

## ⚙️ Tech Stack

- **Frontend:** HTML, CSS  
- **Backend:** Flask (Python)  
- **Machine Learning:** Scikit-learn (Random Forest Regressor)  
- **Libraries:** Pandas, NumPy, Joblib, Matplotlib  
- **Version Control:** Git & GitHub  

---

## 🧠 Machine Learning Details

- Model Used: **Random Forest Regressor**
- Input Features:
  - Make
  - Model
  - Fuel Type
  - Engine Size
  - Cylinders
  - Fuel Consumption
- Output:
  - Predicted CO₂ emission (g/km)

---

## 📊 Features

- 📌 Predict CO₂ emissions instantly  
- 📌 User-friendly web interface  
- 📌 Fleet average comparison  
- 📌 Error handling and validation  
- 📌 Integrated ML pipeline with Flask  

---


## Project Structure
carbon-emission-project/
│── data/
│── ml/
│   ├── train_model.py
│   ├── utils.py
│   ├── metadata.json
│   └── model.pkl (ignored)
│── static/
│── app.py
│── requirements.txt
│── .gitignore
│── README.md

---

🧠 Challenges Faced : 
* Model version compatibility issues (NumPy, scikit-learn)
* Errors while loading saved model (joblib issues)
* Virtual environment path mismatch

📈 Future Improvements : 
* Improve UI/UX design
* Deploy the project on cloud (Render / AWS)
* Add real-time dataset updates

---
👨‍💻 Author

Manish kumar
B.Tech CSE 
