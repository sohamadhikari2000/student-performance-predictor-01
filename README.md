# 📊 Student Performance Predictor

![Python](https://img.shields.io/badge/Python-3.9-blue?logo=python)
![Flask](https://img.shields.io/badge/Flask-WebApp-black?logo=flask)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![AWS](https://img.shields.io/badge/AWS-Elastic%20Beanstalk-yellow?logo=amazonaws)
![Status](https://img.shields.io/badge/Status-Live-success)

A production-ready **Machine Learning web application** that predicts student performance using demographic and academic features. This project demonstrates an **end-to-end ML pipeline** with real-time predictions deployed on AWS.

---

## 🚀 Live Demo

👉 http://student-performance-env.eba-53ppwiqr.eu-north-1.elasticbeanstalk.com/

---

## 🧠 Problem Statement

Predict student performance based on various factors such as:

* Demographics (gender, ethnicity)
* Parental education level
* Lunch type
* Test preparation course
* Reading & Writing scores

---

## ⚡ Key Highlights

* ✅ End-to-end ML pipeline (data → preprocessing → prediction)
* ✅ Real-time inference via Flask web app
* ✅ Production deployment using AWS Elastic Beanstalk
* ✅ Handles categorical + numerical features
* ✅ Modular and scalable code structure

---

## 🏗️ Tech Stack

* **Language:** Python
* **Backend:** Flask
* **ML:** Scikit-learn, XGBoost, CatBoost
* **Data:** Pandas, NumPy
* **Deployment:** AWS Elastic Beanstalk
* **Serialization:** Pickle / Dill

---

## 📂 Project Structure

```id="z6yxvn"
student-performance-predictor-01/
│
├── application.py              # Flask entry point
├── artifacts/                 # Saved model & preprocessor
├── src/
│   ├── pipeline/
│   │   └── predict_pipeline.py
│   ├── utils.py
│   └── exception.py
├── templates/
│   ├── index.html
│   └── home.html
├── requirements.txt
└── README.md
```

---

## ⚙️ Application Workflow

1. User inputs data via web form
2. Data is converted into a Pandas DataFrame
3. Preprocessing pipeline transforms features
4. Trained ML model generates prediction
5. Output is displayed on the UI

---

## ☁️ Deployment (AWS)

This application is deployed using **AWS Elastic Beanstalk**, enabling:

* Scalable cloud infrastructure
* Managed deployment
* Production-ready hosting

---

## 🧪 ML Pipeline

* Feature preprocessing using pipeline
* Model training using regression algorithms
* Model serialization using `pickle`
* Efficient prediction pipeline for real-time inference

---

## 📌 Future Improvements

* Add REST API support
* Dockerize application
* CI/CD pipeline (GitHub Actions)
* Model monitoring and logging

---

## 👨‍💻 Author

**Soham Adhikari**
GitHub: https://github.com/sohamadhikari2000

---

## ⭐ Support

If you found this useful, give it a ⭐ on GitHub!
