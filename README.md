# Diabetes-Prediction

This project shows a supervised machine learning model that uses a **Decision Tree Classifier** to predict diabetes in patients. The model relies on the **PIMA Indian Diabetes Dataset**, which has undergone preprocessing to train and test.

## What's in the Repository

- `Diabetes_DecisionTreeClassifier.ipynb`: Jupyter Notebook with the complete process—from loading data to training, testing, and making predictions on new data.
- `pima_dataset.csv`: Preprocessed PIMA Indian Diabetes dataset that trains the model.
- `README.md`: This guide file.

## Project Overview

### Objective:
Predict how likely a patient has diabetes using medical diagnostic features from the PIMA dataset.

### Methodology:
- **Learning Type:** Supervised Learning
- **Algorithm:** Decision Tree Classifier
- **Steps:**
  1. Load and examine preprocessed data
  2. Divide the data into `X_train`, `X_test`, `y_train`, `y_test`
  3. Build a Decision Tree Classifier model
  4. Check the model's performance using accuracy and other measures
  5. Forecast outcome for a **new data point**

## 📊 Dataset Description

The dataset has these features:

- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age
- Outcome (Target: 1 = diabetic, 0 = non-diabetic)

## 🚀 Getting Started

### Prerequisites
Install the required Python packages:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
