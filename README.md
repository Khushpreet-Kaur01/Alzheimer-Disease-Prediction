# 🧠 Alzheimer’s Disease Prediction

This project aims to predict Alzheimer’s Disease using machine learning techniques based on patient clinical data. It was built as part of a data science assignment and demonstrates key concepts such as data preprocessing, model training, evaluation, and interpretation.

## 📂 Project Overview

- Perform exploratory data analysis (EDA)
- Clean and preprocess medical data
- Train multiple classification models
- Evaluate models based on accuracy and performance metrics
- Use of confusion matrix and classification report for analysis

## 🧪 Dataset Information

The dataset used includes the following fields:

- `Subject ID`
- `MRI ID`
- `Visit`
- `MR Delay`
- `Gender`
- `Age`
- `Hand`
- `Educ` (Years of education)
- `SES` (Socioeconomic Status)
- `MMSE` (Mini-Mental State Exam score)
- `CDR` (Clinical Dementia Rating)
- `eTIV` (Estimated total intracranial volume)
- `nWBV` (Normalized whole-brain volume)
- `ASF` (Atlas scaling factor)
- `Group` (Diagnosis: e.g., Demented, Nondemented)

> **Note:** The target variable is the `Group` field which identifies whether a subject is diagnosed as *Demented* or *Nondemented*.

## 📌 Tools & Technologies

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## 📈 Models Used

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier

Each model was trained, tested, and evaluated for classification performance using:

- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

## 🚀 Getting Started

To run this project locally:

1. **Clone the repository**:

```bash
git clone https://github.com/yourusername/alzheimer-disease-prediction.git
cd alzheimer-disease-prediction
