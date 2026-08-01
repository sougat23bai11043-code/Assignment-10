#  Heart Disease Prediction using Machine Learning

## Assignment 10
### End-to-End Machine Learning Model Deployment using GitHub and Render

---

##  Project Overview

This project demonstrates an end-to-end machine learning workflow for predicting the likelihood of heart disease using patient clinical data. The dataset is preprocessed, split into training and testing sets, and a Logistic Regression model is trained to classify whether a patient is at risk of heart disease. The trained model is saved using Joblib and integrated into a Flask REST API. The complete project is hosted on GitHub and is designed for deployment on Render as a publicly accessible web service.

---

##  Objectives

- Load and preprocess the Heart Disease dataset.
- Identify numerical features and the target variable.
- Train a Machine Learning classification model.
- Evaluate model performance using Accuracy Score.
- Save the trained model using Joblib.
- Develop a REST API using Flask.
- Publish the project on GitHub.
- Deploy the application on Render.

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Flask
- Joblib
- GitHub
- Render

---

##  Repository Structure

```
HeartDiseaseDeployment/
│
├── app.py
├── model.pkl
├── requirements.txt
├── README.md
├── train_model.py
├── heart.csv
├── templates/
│   └── index.html (Optional)
└── static/ (Optional)
```

---

##  Dataset

Dataset: **Heart Disease Prediction Dataset**

The dataset contains patient medical information used to predict the presence or absence of heart disease.

---

##  Machine Learning Model

**Algorithm Used:**
- Logistic Regression

**Evaluation Metric:**
- Accuracy Score

---

##  Flask REST API

The Flask application:

- Loads the trained model (`model.pkl`)
- Accepts patient details as input
- Returns the prediction result in JSON format

Example Response:

```json
{
  "prediction": "Heart Disease Detected"
}
```

---

##  Deployment

The project is deployed using **Render**.

### Build Command

```bash
pip install -r requirements.txt
```

### Start Command

```bash
gunicorn app:app
```

### Live Application

**Render URL:**

```
https://assignment-10-lnmd.onrender.com
```

---

##  How to Run

Install dependencies:

```bash
pip install -r requirements.txt
```

Train the model:

```bash
python train_model.py
```

Run the Flask application:

```bash
python app.py
```

Open:

```
http://127.0.0.1:5000
```

---

##  Files Included

- app.py
- train_model.py
- heart.csv
- model.pkl
- requirements.txt
- README.md

---

##  Conclusion

This project demonstrates the complete workflow of deploying a machine learning model for heart disease prediction. A Logistic Regression model was trained, evaluated using accuracy score, and saved using Joblib. The trained model was integrated with a Flask REST API and prepared for deployment using Render. During deployment, challenges such as dependency management, application configuration, and cloud deployment settings were addressed. This assignment highlights the importance of MLOps practices, including version control with GitHub, model packaging, API development, and cloud deployment. These practices help make machine learning models reliable, reusable, and accessible for real-world applications.

---

##  Author

**NAME** - **Sougat Das**
**APPLICATION NUMBER** - **IN26010889**
**REGISTRATION NUMBER** - **23BAI11043**
**BATCH** - **1(A)**



B.Tech –  (Artificial Intelligence & Machine Learning)

---

##  License

This project is created for educational purposes as part of **Assignment 10**.
