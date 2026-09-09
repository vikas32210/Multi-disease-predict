# 🩺 Multiple Disease Prediction System WebApp

A machine learning-powered **Multiple Disease Prediction System** built with **Python, Streamlit, Scikit-learn, and XGBoost**. The application provides prediction systems for four different diseases using trained machine learning models and processed clinical/medical datasets.

## 🚀 Live Demo

👉 **[Open the Streamlit App](https://multi-disease-predict-r6stcvnkcrrjvuuje5v5s6.streamlit.app/)**

---

## 🧠 Diseases Covered

The application includes four independent disease prediction systems:

1. 🩸 **Diabetes Prediction**
2. ❤️ **Heart Disease Prediction**
3. 🧠 **Parkinson's Disease Prediction**
4. 🎗️ **Breast Cancer Prediction**

Users can select a disease from the application and enter the required medical features to generate a prediction.

---

## 📊 Dataset Description

### 1. Diabetes Prediction

* **Samples:** 768
* **Features:** 8
* **Examples:** Glucose level, blood pressure, insulin, BMI, age, etc.

### 2. Heart Disease Prediction

* **Samples:** 1025
* **Features:** 14
* **Examples:** Age, sex, chest pain type, resting blood pressure, cholesterol, maximum heart rate, etc.

### 3. Parkinson's Disease Prediction

* **Samples:** 195
* **Features:** 22
* **Examples:** Vocal frequency measurements, jitter, shimmer, RPDE, DFA, PPE, etc.

### 4. Breast Cancer Prediction

* **Samples:** 569
* **Features:** 30
* **Examples:** Radius, texture, perimeter, area, smoothness, compactness, concavity, etc.

---

## ⚙️ Machine Learning Workflow

Each disease prediction system follows a structured machine learning workflow:

```text
Data Collection
      ↓
Exploratory Data Analysis (EDA)
      ↓
Data Preprocessing
      ↓
Feature Engineering / Encoding
      ↓
Feature Scaling
      ↓
Model Selection
      ↓
Cross-Validation
      ↓
Feature Selection using RFE
      ↓
Hyperparameter Tuning using GridSearchCV
      ↓
Final Model
      ↓
Model Evaluation
      ↓
Deployment with Streamlit
```

### Data Preprocessing

The project includes:

* Missing-value handling
* Outlier handling
* Label encoding
* One-hot encoding
* Feature standardization/scaling

### Model Selection

Five commonly used classification algorithms were evaluated for each disease.

The top-performing models were selected using **cross-validation scores**.

### Feature Selection

**Recursive Feature Elimination (RFE)** was used to identify important features and reduce unnecessary input variables.

### Hyperparameter Optimization

**GridSearchCV** was used to tune the selected models and identify suitable hyperparameters.

### Model Evaluation

The final models were evaluated using classification reports and accuracy scores.

---

## 🤖 Models Used

### 🩸 Diabetes

* Support Vector Classifier (SVC)
* Logistic Regression
* Random Forest Classifier

### ❤️ Heart Disease

* XGBoost
* Random Forest Classifier
* Logistic Regression

### 🧠 Parkinson's Disease

* K-Nearest Neighbours (KNN)
* XGBoost
* Random Forest Classifier

### 🎗️ Breast Cancer

* Logistic Regression
* XGBoost
* K-Nearest Neighbours (KNN)

---

## 📈 Model Evaluation

| Disease       | Model                     |    Accuracy |
| ------------- | ------------------------- | ----------: |
| Diabetes      | Support Vector Classifier |     69.480% |
| Diabetes      | Logistic Regression       |     70.129% |
| Diabetes      | Random Forest             | **75.324%** |
| Heart Disease | XGBoost                   |    **100%** |
| Heart Disease | Random Forest             |    **100%** |
| Heart Disease | Logistic Regression       |     88.311% |
| Parkinson's   | KNN                       |    **100%** |
| Parkinson's   | XGBoost                   |     92.307% |
| Parkinson's   | Random Forest             |     94.871% |
| Breast Cancer | Logistic Regression       | **97.368%** |
| Breast Cancer | XGBoost                   | **97.368%** |
| Breast Cancer | KNN                       |     96.491% |

> **Note:** These are the evaluation results reported for the models in this project. They should not be interpreted as clinical diagnostic accuracy.

---

## 🛠️ Technologies Used

### Programming

* Python

### Web Application

* Streamlit
* Streamlit Option Menu

### Machine Learning

* Scikit-learn
* XGBoost

### Data Processing

* Pandas
* NumPy

### Data Visualization

* Matplotlib
* Seaborn

### Model Persistence

* Pickle
* JSON

---

## 📁 Project Structure

```text
Multiple-Disease-Prediction-System/
│
├── Datasets/
│
├── Models/
│
├── Preprocessing Files/
│
├── Best Features/
│
├── Notebooks/
│
├── Multiple_Disease_Prediction.py
├── requirements.txt
└── README.md
```

---

## 💻 Installation

### 1. Clone the repository

```bash
git clone https://github.com/prachet283/ML-Project-20-Multiple-Disease-Prediction-System-WebApp.git
```

### 2. Navigate to the project directory

```bash
cd ML-Project-20-Multiple-Disease-Prediction-System-WebApp
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the application

```bash
streamlit run Multiple_Disease_Prediction.py
```

The application will open in your browser.

---

## 🌐 Deployment

The application is deployed using **Streamlit Cloud**.

👉 **[Live Application](https://multi-disease-predict-r6stcvnkcrrjvuuje5v5s6.streamlit.app/)**

---

## ⚠️ Disclaimer

This application is intended for **educational and demonstration purposes only**.

The predictions generated by the machine learning models should **not be considered a medical diagnosis or a substitute for professional medical advice**. Users should consult a qualified healthcare professional for medical evaluation and treatment decisions.

---

## 🔮 Future Improvements

Possible improvements include:

* Probability/confidence visualization
* More advanced ensemble models
* Explainable AI using SHAP
* Improved model validation
* Additional medical datasets
* Patient prediction history
* Interactive model-performance dashboards
* Better error handling and input validation

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

If you find an issue or have an idea for improvement, feel free to create an issue or submit a pull request.

---

## 👨‍💻 Author

**Vikas yadav**

If you have any questions or suggestions regarding the project, feel free to get in touch.
