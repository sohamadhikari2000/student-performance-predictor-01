# 📊 Student Performance Predictor

![Python](https://img.shields.io/badge/Python-3.9-blue?logo=python)
![Flask](https://img.shields.io/badge/Flask-WebApp-black?logo=flask)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![AWS](https://img.shields.io/badge/AWS-Elastic%20Beanstalk-yellow?logo=amazonaws)
![Status](https://img.shields.io/badge/Status-Deployed-success)

A production-ready **Machine Learning web application** that predicts student academic performance using demographic and educational features. Built with **Flask** and deployed on **AWS Elastic Beanstalk**.

---

## 🚀 Live Application

👉 http://student-performance-env.eba-53ppwiqr.eu-north-1.elasticbeanstalk.com/

---

## 🧠 Key Features

* End-to-end ML pipeline (training → preprocessing → prediction)
* Real-time prediction via web interface
* Handles categorical + numerical features
* Cloud deployment with scalable infrastructure
* Optimized for production (fast inference)

---

## 🏗️ Tech Stack

* **Programming:** Python
* **Backend:** Flask
* **ML Libraries:** Scikit-learn, XGBoost, CatBoost
* **Data Processing:** Pandas, NumPy
* **Deployment:** AWS Elastic Beanstalk
* **Model Serialization:** Pickle / Dill

---

## 📂 Project Architecture

```
.
├── application.py          # Flask app entry point
├── artifacts/              # Trained model & preprocessor
├── src/
│   ├── pipeline/           # Prediction pipeline
│   ├── utils.py            # Utility functions
│   └── exception.py        # Custom exception handling
├── templates/              # HTML frontend
├── requirements.txt
└── README.md
```

---

## ⚙️ How It Works

1. User inputs data through web form
2. Data is converted into a DataFrame
3. Preprocessing pipeline transforms inputs
4. Trained model generates prediction
5. Result displayed on UI

---

## ☁️ Deployment (AWS)

Deployed using AWS Elastic Beanstalk:

* Automated environment provisioning
* Load-balanced application hosting
* Production-ready configuration

---

## 🧪 Model Pipeline

* Feature engineering + preprocessing pipeline
* Model trained using regression algorithms
* Serialized using `pickle` for fast inference

---

## 📌 Future Enhancements

* REST API integration
* Docker containerization
* CI/CD pipeline (GitHub Actions)
* Model monitoring & logging

---

## 👨‍💻 Author

**Your Name**
GitHub: https://github.com/your-username

---

## ⭐ Support

If you found this useful, consider giving a ⭐ to the repo!
