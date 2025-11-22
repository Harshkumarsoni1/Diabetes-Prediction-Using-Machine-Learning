<img width="319" height="483" alt="image" src="https://github.com/user-attachments/assets/97d34868-3af9-4513-b646-f747fc7bcdb3" />
<img width="369" height="167" alt="image" src="https://github.com/user-attachments/assets/067af0d3-8e31-4255-b1e5-1fd0c05374e1" />


🌡️ Diabetes Prediction Using Machine Learning (Flask App)

This is a Machine Learning + Flask Web App that predicts whether a person is Diabetic or Non-Diabetic based on medical input parameters.

✔ Built using Python, Flask, Scikit-Learn, Pickle models
✔ Clean and simple web interface
✔ Uses trained ML model + StandardScaler

🚀 Features

User-friendly web form

Takes input parameters:

Pregnancies

Glucose

Blood Pressure

Skin Thickness

Insulin

BMI

Diabetes Pedigree Function

Age

Predicts:

Diabetic

Non-Diabetic

📂 Project Structure
├── app.py
├── model
│   ├── standardScaler.pkl
│   └── modelForPrediction.pkl
├── templates
│   ├── index.html
│   ├── home.html
│   └── single_prediction.html
└── Dataset

🛠️ Technologies Used

Python

Flask

NumPy

Pandas

Scikit-Learn

Pickle

▶️ How to Run Locally
1️⃣ Install dependencies
pip install -r req.txt

2️⃣ Run the application
python app.py

3️⃣ Open in browser
http://127.0.0.1:5000/
