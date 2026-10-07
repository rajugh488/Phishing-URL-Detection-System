# Phishing URL Detection System

## 📌 Project Overview

The Phishing URL Detection System is a machine learning-based cybersecurity application designed to identify whether a given URL is potentially **phishing** or **legitimate**.

The system extracts important URL-based features and uses a **Random Forest Classifier** to classify URLs.

## 🎯 Objectives

- Detect potentially malicious phishing URLs.
- Extract meaningful features from URLs.
- Classify URLs as legitimate or phishing.
- Provide a confidence score for the prediction.
- Explain possible reasons why a URL is considered suspicious.
- Provide a simple web interface for real-time URL analysis.

## 🛠️ Technologies Used

- Python
- Flask
- Pandas
- Scikit-learn
- Joblib
- HTML/CSS
- Machine Learning

## 🤖 Machine Learning Model

The system uses a **Random Forest Classifier**.

### URL Features

The following features are extracted:

- URL length
- Number of dots
- HTTPS availability
- IP address presence
- `@` symbol presence
- Number of hyphens
- Suspicious keyword count
- Number of subdomains
- Path depth
- Number of digits
- Query parameter count

## 📂 Project Structure

```text
Phishing-URL-Detection-System/
│
├── data/
├── models/
│   └── phishing_model.pkl
├── reports/
├── screenshots/
├── src/
│   ├── templates/
│   ├── app.py
│   ├── features.py
│   ├── train_model.py
│   └── requirements.txt
├── tests/
│
└── url_dataset.csv
