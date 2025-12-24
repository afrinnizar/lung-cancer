# lung-cancer

# 🫁 Lung Cancer Survival Prediction using Machine Learning

## 📘 Project Overview

Lung cancer is one of the leading causes of cancer-related deaths worldwide. Early prediction of patient survival can support better treatment planning and healthcare decisions.
This project applies **machine learning techniques** to predict lung cancer survival outcomes using clinical, lifestyle, and demographic patient data.

The model analyzes key health indicators such as age, smoking habits, BMI, cancer stage, and treatment type to estimate the likelihood of patient surviva

## 🎯 Objective

To develop a **supervised machine learning model** that predicts whether a lung cancer patient is likely to survive based on medical and lifestyle attributes.


## 📊 Dataset Information

* **File Name:** `dataset_med.csv`
* **Source:** Custom dataset derived from clinical data samples
* **Target Variable:** `survived` (Yes / No)


## 🧩 Features Description

| Feature            | Description                                   |
| ------------------ | --------------------------------------------- |
| id                 | Unique patient identifier                     |
| age                | Age at diagnosis                              |
| gender             | Male / Female                                 |
| country            | Country or region of residence                |
| diagnosis_date     | Date of lung cancer diagnosis                 |
| cancer_stage       | Cancer stage (I–IV)                           |
| family_history     | Family history of cancer (Yes/No)             |
| smoking_status     | Current / Former / Never / Passive smoker     |
| bmi                | Body Mass Index                               |
| cholesterol_level  | Cholesterol measurement                       |
| hypertension       | High blood pressure (Yes/No)                  |
| asthma             | Presence of asthma (Yes/No)                   |
| cirrhosis          | Liver cirrhosis (Yes/No)                      |
| other_cancer       | History of other cancers (Yes/No)             |
| treatment_type     | Surgery / Chemotherapy / Radiation / Combined |
| end_treatment_date | Treatment completion date                     |
| survived           | Survival outcome (Target variable)            |

---

## ⚙️ Project Workflow

### 1️⃣ Data Preprocessing

* Handling missing and inconsistent values
* Encoding categorical variables
* Feature scaling and normalization

### 2️⃣ Exploratory Data Analysis (EDA)

* Distribution analysis of numerical features
* Correlation analysis
* Impact of smoking status, cancer stage, and treatment type on survival

### 3️⃣ Model Development

* Train-test data split
* Model training using:

  * Logistic Regression
  * Random Forest
  * Support Vector Machine (SVM)
* Hyperparameter tuning

### 4️⃣ Model Evaluation

* Accuracy, Precision, Recall, F1-score
* Confusion Matrix
* ROC-AUC Curve
* Feature importance visualization


## 🧠 Technologies Used

* **Python 3.x**
* **Jupyter Notebook**
* **Libraries:**

  * pandas
  * numpy
  * matplotlib
  * seaborn
  * scikit-learn
  * xgboost *(optional)*


## 🚀 How to Run the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/<your-username>/Lung-Cancer-Prediction.git
cd Lung-Cancer-Prediction
```

### Step 2: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 3: Launch Jupyter Notebook

```bash
jupyter notebook
```

### Step 4: Open and Run

```
Lung_Cancer_Prediction.ipynb
```


## 📈 Results

* **Model Accuracy:** X% *(replace with actual result)*
* **Key Predictive Features:**

  * Cancer Stage
  * Smoking Status
  * Age
  * Treatment Type

The results demonstrate that machine learning models can effectively identify survival patterns in lung cancer patients and highlight critical factors influencing outcomes.


## 📌 Conclusion

This project showcases the practical application of machine learning in healthcare analytics. By analyzing patient data, the model provides valuable insights that can assist medical professionals in understanding survival trends and improving decision-making.



