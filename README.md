# salary-prediction-app
Salary prediction web app using Streamlit
# 💼 Salary Prediction Web Application

## 📌 Project Overview
This project is a **Salary Prediction Web Application** built using **Machine Learning** and **Streamlit**.  
The application predicts an employee’s salary based on **Years of Experience**.

The trained machine learning model is deployed **live on the internet** using **Streamlit Community Cloud**.

---

## 🚀 Live Demo
🔗 https://salary-prediction-app-kokvawuqt3y3jkwivjdmwc.streamlit.app/

---

## 🧠 Problem Statement
To predict the salary of an employee based on their years of experience using a regression-based machine learning model.

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Streamlit  
- Joblib  
- GitHub  

---

## 📊 Dataset Information
The dataset contains employee-related information such as:
- Age  
- Gender  
- Education Level  
- Job Title  
- Years of Experience  
- Salary  

### Data Cleaning Performed
- Removed missing values  
- Removed duplicate records  

---

## 🤖 Machine Learning Model
- **Algorithm Used:** Linear Regression  
- **Evaluation Metric:** R² Score  
- **Model Accuracy:** ~85% (R² ≈ 0.85)

---

## 🖥️ Web Application Features
- Simple and beginner-friendly UI  
- Takes **Years of Experience** as input  
- Predicts salary instantly  
- Fully deployed online  

---

## 📁 Project Structure
salary-prediction-app/
│
├── app.py
├── salary_prediction_model.pkl
├── requirements.txt
└── README.md


---

## ▶️ How to Run the Project Locally

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/salary-prediction-app.git

2️⃣ Navigate to Project Folder
cd salary-prediction-app

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Run the Web App
streamlit run app.py

📈 Sample Prediction

Input:
Years of Experience = 12

Output:
Predicted Salary ≈ 113,379
