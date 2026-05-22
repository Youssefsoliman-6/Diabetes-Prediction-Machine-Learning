# 🩺 Diabetes Prediction Machine Learning Project

A complete Machine Learning project focused on predicting diabetes using patient health data and multiple classification algorithms.

This project explores data preprocessing, feature engineering, model training, evaluation, optimization, and performance comparison using Python and Scikit-learn.

---

# 📌 Project Overview

The objective of this project is to build an intelligent machine learning system capable of predicting whether a patient is diabetic based on medical attributes such as:

- Age
- BMI
- Blood Glucose Level
- HbA1c Level
- Hypertension
- Heart Disease
- Smoking History

The project compares multiple Machine Learning models and evaluates their performance using standard classification metrics.

---

# 🎯 Objectives

- Perform data preprocessing and cleaning
- Handle categorical and numerical features
- Train multiple ML classification models
- Compare model performance
- Improve prediction accuracy
- Evaluate models using real ML metrics

---

# 📂 Project Structure

```bash
ML-Project/
│
├── diabetes_prediction_dataset.csv
├── ML Project.ipynb
├── README.md
├── requirements.txt
│
├── Images/
│   ├── correlation_matrix.png
│   ├── confusion_matrix.png
│   ├── model_accuracy.png
│   └── dataset_preview.png
│
└── Models/
    └── saved_models/
```

---

# 📊 Dataset Information

The dataset contains medical and health-related features used for diabetes prediction.

## Features Used

| Feature | Description |
|------|------|
| `gender` | Male/Female |
| `age` | Patient age |
| `hypertension` | Hypertension status |
| `heart_disease` | Heart disease status |
| `smoking_history` | Smoking behavior |
| `bmi` | Body Mass Index |
| `HbA1c_level` | Hemoglobin A1c level |
| `blood_glucose_level` | Blood glucose level |
| `diabetes` | Target variable |

---

# 🧠 Machine Learning Models

The following classification algorithms were implemented and tested:

## Models Used
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Naive Bayes
- XGBoost
- Multi-Layer Perceptron (MLP Neural Network)

---

# ⚙️ Technologies Used

## Programming Language
- Python

## Libraries & Frameworks
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost
- Seaborn
- Jupyter Notebook

---

# 🔄 Machine Learning Workflow

## 1️⃣ Data Collection
- Imported diabetes dataset
- Explored dataset structure

## 2️⃣ Data Preprocessing
- Handled missing values
- Encoded categorical variables
- Feature scaling using StandardScaler

## 3️⃣ Exploratory Data Analysis (EDA)
- Correlation analysis
- Feature distribution visualization
- Class balance inspection

## 4️⃣ Model Training
- Trained multiple classifiers
- Compared model performance

## 5️⃣ Hyperparameter Tuning
- GridSearchCV optimization
- Parameter tuning for SVM and other models

## 6️⃣ Evaluation
Models evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

# 📈 Model Evaluation

The project compares model performance to identify the best classifier for diabetes prediction.

## Evaluation Metrics

| Metric | Purpose |
|------|------|
| Accuracy | Overall prediction correctness |
| Precision | Correct positive predictions |
| Recall | Ability to detect diabetic cases |
| F1 Score | Balance between precision & recall |

---

# 📸 Visualizations

## Dataset Preview
![Dataset](Images/dataset_preview.png)

## Correlation Matrix
![Correlation](Images/correlation_matrix.png)

## Confusion Matrix
![Confusion](Images/confusion_matrix.png)

## Model Accuracy Comparison
![Accuracy](Images/model_accuracy.png)

---

# 🚀 Installation & Usage

# 1️⃣ Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/Diabetes-Prediction-ML-Project.git
```

---

# 2️⃣ Install Requirements

```bash
pip install -r requirements.txt
```

---

# 3️⃣ Run Jupyter Notebook

```bash
jupyter notebook
```

Open:

```bash
ML Project.ipynb
```

---

# 📦 Requirements

Example `requirements.txt`

```txt
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
jupyter
```

---

# 🧪 Example Workflow

```python
# Train model
model.fit(X_train, y_train)

# Predict
predictions = model.predict(X_test)

# Evaluate
accuracy_score(y_test, predictions)
```

---

# 📊 Key Learning Outcomes

This project demonstrates:

- Machine Learning Fundamentals
- Classification Algorithms
- Data Preprocessing
- Feature Engineering
- Hyperparameter Tuning
- Model Evaluation
- Data Visualization
- Medical Data Analysis

---

# 🔮 Future Improvements

- Deep Learning Integration
- Web Deployment using Flask/Django
- Real-Time Prediction System
- Streamlit Dashboard
- Feature Importance Analysis
- Model Explainability (SHAP/LIME)
- Cloud Deployment

---

# 👨‍💻 Author

## Youssef Ahmed

Machine Learning & Data Science Enthusiast

---

# 📄 License

This project is licensed under the MIT License.

---

# ⭐ Support

If you found this project useful:
- Star the repository
- Fork the project
- Share it with others

---

# 📬 Contact

Feel free to contribute or connect regarding Machine Learning and AI projects.
