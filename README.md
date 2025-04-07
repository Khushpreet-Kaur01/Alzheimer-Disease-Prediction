
# 🧠 Alzheimer’s Disease Prediction

This project aims to predict Alzheimer’s Disease using a Logistic Regression model based on patient clinical data. It demonstrates key concepts such as data preprocessing, model training, evaluation, and interpretation. Additionally, the model is exposed via RESTful web services for easy access.

## 📂 Project Overview

- Perform exploratory data analysis (EDA)
- Clean and preprocess medical data
- Train a Logistic Regression model for classification
- Evaluate the model based on accuracy and performance metrics
- Expose the model through RESTful web services for prediction
- Use confusion matrix and classification report for analysis

## 🧪 Dataset Information

The dataset used includes the following fields:

- `Age`: Age of the patient in years.
- `Gender`: Gender of the patient (0 = Male, 1 = Female).
- `BMI`: Body Mass Index (BMI), calculated from the patient’s height and weight.
- `AlcoholConsumption`: Average alcohol consumption in units per week.
- `PhysicalActivity`: Average physical activity in hours per week.
- `FamilyHistoryAlzheimers`: Family history of Alzheimer’s disease (0 = No, 1 = Yes).
- `Diabetes`: Whether the patient has diabetes (0 = No, 1 = Yes).
- `Depression`: Whether the patient has depression (0 = No, 1 = Yes).
- `HeadInjury`: History of head injury (0 = No, 1 = Yes).
- `Hypertension`: Presence of hypertension (high blood pressure) (0 = No, 1 = Yes).
- `CholesterolTotal`: Total cholesterol level (mg/dL).
- `MMSE`: Mini-Mental State Examination (MMSE) score for cognitive function.
- `FunctionalAssessment`: Functional assessment score to evaluate daily activities.
- `MemoryComplaints`: Whether the patient has memory complaints (0 = No, 1 = Yes).
- `BehavioralProblems`: Behavioral issues like aggression or irritability (0 = No, 1 = Yes).
- `ADL`: Activities of Daily Living (ADL) score measuring independence in daily activities.
- `Confusion`: Whether the patient shows confusion (0 = No, 1 = Yes).
- `Disorientation`: Whether the patient is disoriented (0 = No, 1 = Yes).
- `PersonalityChanges`: Presence of personality changes (0 = No, 1 = Yes).
- `Forgetfulness`: Whether the patient is experiencing forgetfulness (0 = No, 1 = Yes).
- `Diagnosis`: Diagnosis of Alzheimer’s disease (0 = No Alzheimer’s, 1 = Alzheimer’s).

> **Note:** The target variable is the `Diagnosis` field, which identifies whether a subject is diagnosed with Alzheimer’s (1 = Alzheimer’s, 0 = No Alzheimer’s).

## 📌 Tools & Technologies

- Python 3.x
- Pandas
- NumPy
- Scikit-learn (for Logistic Regression model)
- Matplotlib, Seaborn
- Flask (for RESTful Web Services)
- Jupyter Notebook

## 📦 Installation & Setup

1. **Clone the repository**:

```bash
git clone https://github.com/Khushpreet-Kaur01/alzheimer-disease-prediction.git
cd alzheimer-disease-prediction
```

2. **Install dependencies**:

```bash
pip install -r requirements.txt
```

3. **Run the Jupyter Notebook**:

```bash
jupyter notebook
```

4. **To use the RESTful Web Service**:
   - Start the Flask server:
   
   ```bash
   python app.py
   ```
   
   - The server will expose a REST API that can be used for predictions. Send a POST request to the `/predict` endpoint with the appropriate data.

## 📝 Key Steps in the Project

1. **Data Preprocessing**:
   - Handling missing values
   - Feature encoding (if necessary)
   - Feature scaling

2. **Model Training**:
   - Train the Logistic Regression model for classification

3. **Model Evaluation**:
   - Evaluate the model using accuracy, confusion matrix, and classification report

4. **Expose the Model via RESTful Web Services**:
   - Expose the trained Logistic Regression model through a Flask-based RESTful API.
   - Users can send patient data to the `/predict` endpoint and receive a prediction.

5. **Model Interpretation**:
   - Interpret model results and understand which features are most important for predicting Alzheimer's disease.

## 📊 Results

The final model should help predict whether a patient has Alzheimer’s disease or not based on the clinical data provided.

## 💡 Conclusion

By building and evaluating a Logistic Regression model, this project aims to create a predictive tool for Alzheimer's disease diagnosis. The model is exposed via RESTful web services, making it easy to integrate into clinical applications and assist healthcare providers in making informed decisions.
