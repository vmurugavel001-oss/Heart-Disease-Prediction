# Heart Disease Prediction 🫀

A machine learning project that predicts the presence of heart disease in patients based on medical attributes. This project employs multiple ML algorithms to assist in early diagnosis and clinical decision-making.

## 📋 Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Models Used](#models-used)
- [Results](#results)
- [Key Findings](#key-findings)
- [Recommendations](#recommendations)
- [Contributing](#contributing)
- [License](#license)

## 🎯 Overview

Heart disease is one of the leading causes of death worldwide. Early detection can help hospitals take preventive actions and reduce mortality. This project analyzes patient health data and builds machine learning models to predict the presence of heart disease with high accuracy.

**Domain:** Healthcare

## 📊 Dataset

The dataset contains medical attributes of patients, including:

- **Age:** Patient's age in years
- **Sex:** Gender of the patient
- **Chest Pain Type:** Type of chest pain experienced
- **Resting Blood Pressure:** Blood pressure at rest (mm Hg)
- **Serum Cholesterol:** Cholesterol level (mg/dl)
- **Fasting Blood Sugar:** Whether fasting blood sugar > 120 mg/dl
- **Resting ECG Results:** Electrocardiographic results at rest
- **Max Heart Rate Achieved:** Maximum heart rate during exercise
- **Exercise Induced Angina:** Chest pain induced by exercise
- **Oldpeak (ST Depression):** ST depression induced by exercise
- **Slope of Peak Exercise ST Segment:** Slope of the peak exercise ST segment
- **Number of Major Vessels:** Number of major vessels colored by fluoroscopy (0-3)
- **Thal:** Thalassemia (normal, fixed defect, reversible defect)
- **Heart Disease Present:** Target variable (0 = No, 1 = Yes)

## ✨ Features

- **Comprehensive EDA:** Extensive exploratory data analysis with visualizations
- **Data Preprocessing:** Handling missing values, encoding categorical variables, feature scaling
- **Multiple ML Models:** Implementation of 5 different algorithms
- **Model Evaluation:** Detailed performance metrics including accuracy, precision, recall, F1-score, and ROC-AUC
- **Feature Importance Analysis:** Understanding which features contribute most to predictions
- **Visualizations:** Correlation heatmaps, distribution plots, and feature importance charts

## 🚀 Installation

### Prerequisites
- Python 3.7+
- Jupyter Notebook

### Required Libraries
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

### Clone the Repository
```bash
git clone https://github.com/yourusername/heart-disease-prediction.git
cd heart-disease-prediction
```

## 💻 Usage

1. Open the Jupyter Notebook:
```bash
jupyter notebook Heart_Disease.ipynb
```

2. Run all cells sequentially to:
   - Load and explore the dataset
   - Perform data preprocessing
   - Train multiple ML models
   - Evaluate and compare model performance
   - Analyze feature importance

## 🤖 Models Used

The project implements and compares the following machine learning algorithms:

1. **Logistic Regression**
2. **Decision Tree Classifier**
3. **Random Forest Classifier**
4. **Support Vector Machine (SVM)**
5. **Gradient Boosting Classifier**

## 📈 Results

### Model Performance Comparison

The models were evaluated using the following metrics:
- **Accuracy:** Overall correctness of predictions
- **Precision:** Accuracy of positive predictions
- **Recall:** Ability to identify all positive cases
- **F1-Score:** Harmonic mean of precision and recall
- **ROC-AUC:** Area under the ROC curve

### Best Performing Model

**Random Forest Classifier** achieved the best overall performance with:
- Highest accuracy
- Perfect recall (crucial for healthcare applications)
- Strong precision and F1-score
- Excellent ROC-AUC score

High recall ensures that patients with heart disease are not missed, making this model particularly suitable for medical diagnosis.

## 🔍 Key Findings

### Most Important Features for Prediction:

1. **Thal (Thalassemia)** - Most influential feature
2. **Chest Pain Type** - Strong predictor
3. **Maximum Heart Rate Achieved** - Significant indicator
4. **ST Depression (Oldpeak)** - Important ECG metric
5. **Age** - Moderate influence
6. **Number of Major Vessels** - Moderate influence
7. **Serum Cholesterol** - Moderate influence

### Least Important Features:
- Fasting Blood Sugar
- Resting ECG Results

These findings align with established medical knowledge, validating the dataset quality and model reliability.

## 💡 Recommendations

Based on the analysis, the following recommendations are made to hospitals:

1. **Implement Early Screening:** Use ML predictions for early heart disease detection
2. **Monitor High-Risk Patients:** Prioritize patients identified as high-risk by the model
3. **Encourage Lifestyle Interventions:** Focus on preventive care for at-risk individuals
4. **Reduce Emergency Cardiac Events:** Proactive monitoring to prevent critical incidents
5. **Focus on Key Indicators:** Pay special attention to thalassemia results, chest pain type, and exercise-related metrics

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📧 Contact

For questions or feedback, please open an issue in the repository.

---

⭐ If you find this project helpful, please consider giving it a star!
