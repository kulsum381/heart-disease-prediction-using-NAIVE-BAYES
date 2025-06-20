# 🫀 Heart Disease Prediction using Naive Bayes

This project uses a machine learning approach to predict whether a patient is likely to have heart disease. It utilizes the **Naive Bayes algorithm** on a cleaned dataset containing various medical attributes.

---

## 📌 Project Overview

- Predicts heart disease based on 11 key features such as age, sex, chest pain type, cholesterol, and ECG results.
- Uses **Gaussian Naive Bayes** from `scikit-learn`.
- Converts categorical variables to numeric using `map()`.
- Accepts **user input** and provides a prediction.
- Evaluates model performance with accuracy score.

---

## 🧠 Algorithm Used

- **Naive Bayes Classifier (GaussianNB)**
  - Assumes features follow a normal distribution.
  - Simple and fast, works well for small to medium-sized datasets.

---

## 📂 Files in This Repository

- `heart.csv` – The dataset used for training and testing.
- `heart_disease_prediction_naivebayes.py` – The main Python script.
- `README.md` – This documentation file.

---

## 📊 Features in Dataset

| Feature            | Description                                   |
|--------------------|-----------------------------------------------|
| Age                | Age of the patient                            |
| Sex                | 1 = Male, 0 = Female                           |
| ChestPainType      | 0 = ATA, 1 = NAP, 2 = ASY, 3 = TA              |
| RestingBP          | Resting blood pressure                        |
| Cholesterol        | Serum cholesterol (mg/dl)                     |
| FastingBS          | Fasting blood sugar > 120 mg/dl (1 = True)    |
| RestingECG         | 0 = Normal, 1 = ST, 2 = LVH                    |
| MaxHR              | Maximum heart rate achieved                   |
| ExerciseAngina     | 0 = No, 1 = Yes                                |
| Oldpeak            | ST depression induced by exercise             |
| ST_Slope           | 0 = Up, 1 = Flat, 2 = Down                     |
| HeartDisease       | Target variable (1 = Yes, 0 = No)             |

---

## 🚀 How to Run

1. Clone this repository or download the files.
2. Install required libraries:
   ```bash
   pip install pandas numpy scikit-learn
