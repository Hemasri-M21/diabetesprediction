# Diabetes Prediction System (Machine Learning + Flask)

A beginner-friendly **Machine Learning web application** that predicts diabetes risk based on patient health parameters.
This project combines **Data Science, Backend Development, and Frontend UI** to demonstrate how ML models can be deployed into real-world applications.

## project Overview

This application allows users to enter medical details such as glucose level, BMI, age, and blood pressure.
The system processes the input using a trained Machine Learning model and returns a prediction indicating diabetes risk.

The goal of this project is to:

* Show how ML models move from **training → deployment**
* Build a simple **healthcare prediction interface**
* Demonstrate **Flask API integration** with a frontend


## Features

* Clean and responsive user interface
* Real-time diabetes risk prediction
* Flask backend with trained ML model
* Beginner-friendly project structure
* End-to-end ML workflow

## Machine Learning Workflow

1. Data preprocessing and cleaning
2. Feature selection
3. Model training using Scikit-learn
4. Model serialization (pickle file)
5. Deployment using Flask API


## Tech Stack

**Programming:** Python
**Machine Learning:** Scikit-learn, NumPy, Pandas
**Backend:** Flask
**Frontend:** HTML, CSS
**Visualization:** Matplotlib

## Project Structure

Diabetes-Prediction/
│
├── app.py              # Flask application
├── model.pkl           # Trained ML model
├── templates/
│   └── index.html      # Frontend UI
├── static/             # CSS or assets (optional)
└── README.md

## Installation & Setup

### 1️. Clone the repository


git clone <repo>
cd Diabetes-Prediction


### 2️. Install dependencies

pip install -r requirements.txt

### 3️. Run the Flask app

python app.py

Open your browser and go to:

http://127.0.0.1:5000/


## Input Parameters

The model uses the following health attributes:

* Number of Pregnancies
* Glucose Concentration
* Blood Pressure
* Insulin Level
* BMI
* Diabetes Pedigree Function
* Age
* Skin Thickness

## Why This Project Matters

This project demonstrates important real-world skills:

* Deploying Machine Learning models
* Building APIs with Flask
* Designing user-friendly interfaces
* Integrating frontend with backend logic

It is designed to be simple enough for beginners while still showing practical deployment experience that recruiters value.


## Future Improvements

* Add input validation and error handling
* Improve UI with dashboard layout
* Deploy using Render or AWS
* Add model comparison and accuracy metrics


## Author

Hemasri M

