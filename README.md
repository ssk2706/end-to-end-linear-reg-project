# 🔥 Forest Fire Weather Index (FWI) Prediction

A Flask-based Machine Learning web application that predicts the **Forest Fire Weather Index (FWI)** using a trained **Ridge Regression** model (Python Notebook). Users can enter weather parameters through a simple web interface to receive instant FWI predictions.

## 🚀 Features

- Forest Fire Weather Index prediction
- Ridge Regression model
- Flask web application
- StandardScaler for data preprocessing
- HTML frontend
- AWS Elastic Beanstalk deployment
- CI/CD with AWS CodePipeline

## 🛠 Tech Stack

- Python
- Flask
- Scikit-learn
- NumPy
- Pandas
- HTML
- AWS Elastic Beanstalk
- AWS CodePipeline
- Git & GitHub

## 📁 Project Structure

```
├── application.py
├── models/
│   ├── ridge.pkl
│   └── scaler.pkl
├── templates/
│   ├── index.html
│   └── home.html
├── requirements.txt
├── README.md
└── .ebextensions/
```

## ▶️ Run Locally

```bash
git clone https://github.com/<your-username>/<repository-name>.git
cd <repository-name>

python -m venv venv

# Windows
venv\Scripts\activate

pip install -r requirements.txt
python application.py
```

Visit:

```
http://localhost:5000
```

## ☁️ Deployment

The application is deployed on **AWS Elastic Beanstalk** with automated deployment using **AWS CodePipeline**.

GitHub
   │
   ▼
AWS CodePipeline
   │
   ▼
Amazon S3
   │
   ▼
AWS Elastic Beanstalk
   │
   ▼
Live Flask Application

Link for live application: http://end-to-end-linear-reg-project-env.eba-rri34v2y.eu-north-1.elasticbeanstalk.com/predict

## 📄 License

This project is developed for educational and learning purposes.