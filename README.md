# BostonHousePricing

### Software And Tools Requirements

1. [Github Account](https://github.com)
2. [HerokuAccount](https://heroku.com)
3. [VSCodeIDE](https://code.visualstudio.com/)
4. [GitCLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)

Create a new environment

```
conda create -p venv python==3.7 -y
```

# 🏠 Boston House Price Prediction

A machine learning web application that predicts house prices using Linear Regression on the Boston Housing dataset.

## 📌 Overview
Predicts the median value of owner-occupied homes based on various features like crime rate, number of rooms, accessibility to highways, and more.

## 🚀 Features
- End-to-end ML pipeline from EDA to deployment
- Trained Linear Regression model with StandardScaler
- Flask web app with clean UI
- Dockerized for easy deployment

## 🛠️ Tech Stack
- Python, Scikit-Learn, Pandas, NumPy
- Flask (Web Framework)
- Docker
- HTML/CSS (Frontend)

## ⚙️ How to Run

### Without Docker
```bash
git clone https://github.com/vasanthi200221/BostonHousePricing.git
cd BostonHousePricing
pip install -r requirements.txt
python app.py
```

### With Docker
```bash
docker build -t bostonhousepricing .
docker run -p 5000:5000 bostonhousepricing
```
Open your browser and go to `http://localhost:5000`

## 📊 Model
- Algorithm: Linear Regression with Ridge
- Preprocessing: Standard Scaling
- Dataset: Boston Housing Dataset
