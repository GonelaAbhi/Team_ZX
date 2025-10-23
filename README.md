# Team_ZX_Project

# Idea 1


## 🐾 AI-Powered Veterinary Disease Prediction System

# 📘 Overview

- This project is an AI automation system for veterinary clinics designed to assist veterinarians in diagnosing animal diseases efficiently.

- It predicts potential diseases based on the symptoms and breed of the animal, then automatically assigns a suitable doctor.

- If a doctor is available, the system confirms the appointment.




# 🚀 Key Features

## 🧠 AI-based Disease Prediction
- Built using a Random Forest Classifier from scikit-learn, chosen for its high accuracy, ability to handle categorical symptom data, and robustness against overfitting in disease prediction.

- The core model is trained on animal symptoms, breed, and historical disease data to predict the most probable disease.

- The full model development, preprocessing, and evaluation can be found in the notebook file
  
- Techniques like feature encoding, data normalization, and model accuracy evaluation are implemented for optimal performance.

- **Ensemble Approach for Higher Accuracy:** By combining multiple machine learning models, the system leverages the strengths of each model to improve overall disease prediction accuracy.

## 👨‍⚕️ Doctor Assignment System

- After predicting the disease, the system matches the result with a doctor’s specialization.

- Uses a simple rule-based logic or mapping table to assign the most relevant available veterinarian.

- Ensures each patient gets an expert for their condition.

## ⏰ Automated Scheduling (Future Scope)

 - Once a doctor is identified, the system checks availability and automates scheduling when possible.

 - Future updates will include calendar integration and real-time availability checking.





# 🧩 Tech Stack

| Category                 | Technologies                                 |
| ------------------------ | -------------------------------------------- |
| **Language**             | Python                                       |
| **Machine Learning**     | scikit-learn  / pandas / numpy               |
| **Notebook Development** | Jupyter Notebook (.ipynb)                    |



# 🧠 How It Works

**Input**: User enters symptoms and selects the animal’s breed.

**Prediction**: The ML model processes inputs and predicts the probable disease.

**Doctor Matching**: Based on the predicted disease, the system finds the most suitable available doctor.

**Scheduling**: If the doctor is free, the appointment is booked automatically.

# 🧪 Model Pipeline

**Input: Breed + Symptoms**

      ↓
**Data Preprocessing**

      ↓
**Feature Encoding: LabelEncoder / OneHotEncoder**

      ↓
**Model Training: RandomForestClassifier**

      ↓
**Prediction: Most Probable Disease**


**Another idea is in idea2.md**
[idea2.md](https://github.com/GonelaAbhi/Team_ZX/blob/main/Idea2.md)












## Team Members
- **Koshika Mani (ID: B201603)**  
- **Gaddam Purushotham (ID: B201058)**  
- **Legisheeti Naveen (ID: B200696)**  
- **Gonela Abhilash (ID: B200232)**
















