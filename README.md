# TitanicLifePredict
 Machine learning project predicting Titanic passenger survival using Logistic Regression. Features an interactive Tkinter GUI with dropdown inputs and real-time color-coded predictions.

# Titanic Life Predictor (GUI + ML)

A machine learning project to predict passenger survival on the Titanic using **Logistic Regression**.  
The project includes a **Tkinter GUI** where users can input passenger details and instantly see if they would survive or not, based on trained model predictions.

---

## **Dataset**
The dataset used is from Kaggle:

[Titanic Dataset - Kaggle](https://www.kaggle.com/datasets/heptapod/titanic)

---

## **Features**
- Predict Titanic survival based on passenger details:
  - Passenger Class (Pclass)
  - Gender (Sex)
  - Age
  - Siblings/Spouses aboard (SibSp)
  - Parents/Children aboard (Parch)
  - Fare
  - Port of Embarkation (Embarked)
- Cleaned and preprocessed data (missing values handled).
- Interactive GUI built with **Tkinter**:
  - Dropdown menus for categorical fields.
  - Color-coded prediction result (Green = Survived, Red = Not Survived).
- Logistic Regression model with ~80% accuracy.

---

## **Technologies Used**
- **Python 3**
- **Pandas**
- **Scikit-learn**
- **Tkinter (GUI)**

---

## **Installation**

1. Clone this repository:
```bash
git clone https://github.com/your-username/TitanicSurvivalPredictor.git
cd TitanicSurvivalPredictor
