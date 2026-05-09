# Air Quality Index Prediction

A Machine Learning based project for predicting and classifying Air Quality Index (AQI) using historical pollutant data and supervised learning models.

## 📌 Project Overview

Air pollution is a major environmental and public health concern. This project focuses on building a predictive system that classifies air quality into understandable categories such as:

- Good
- Moderate
- Poor
- Severe

The model uses historical multivariate pollutant data including:

- CO
- NOx
- PM2.5
- Temperature
- Other environmental attributes

The project applies data preprocessing, feature engineering, machine learning classification, and visualization techniques to generate accurate AQI predictions.

---

## 🚀 Features

- Data Cleaning and Preprocessing
- Handling Missing Values (`-200` replacement)
- AQI Category Classification
- Supervised Machine Learning Models
- Model Evaluation using Classification Metrics
- Feature Importance Analysis
- Data Visualization and Insights

---

## 🛠️ Technologies Used

### Programming Language
- Python

### Libraries & Frameworks
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📂 Project Structure

```bash
AirQualityIndexPredictionMiniProject/
│
├── Air_Quality_Index_Prediction.ipynb
├── README.md
└── dataset/
```

---

## ⚙️ Methodology

### 1. Data Ingestion
- Load AQI dataset using Pandas
- Analyze pollutant attributes

### 2. Data Cleaning
- Replace invalid values (`-200`)
- Handle missing data
- Normalize and prepare features

### 3. Feature Engineering
- Convert continuous AQI values into categorical labels

### 4. Model Training
Machine learning classification models used:
- Random Forest Classifier
- Decision Tree Classifier

### 5. Evaluation
Performance measured using:
- Accuracy Score
- Precision
- Recall
- Confusion Matrix

### 6. Visualization
- Feature Importance Charts
- Classification Reports
- Data Distribution Graphs

---

## 📊 Objective

The main objective of this project is to create an automated system capable of predicting and classifying air quality conditions from environmental sensor data.

This can help:
- Environmental monitoring systems
- Public health awareness
- Pollution analysis
- Smart city applications

---

## 📈 Future Improvements

- Real-time AQI prediction
- Web dashboard integration
- Deep learning implementation
- IoT sensor integration
- Deployment using Flask/Streamlit

---

## 👨‍💻 Author

**Devanarayan CS**  
B.Tech - Computer and Communication Engineering  
Manipal University Jaipur

---

## 📚 References

- UCI Machine Learning Repository
- Scikit-learn Documentation
- EPA AQI Standards

---

## 📜 License

This project is developed for educational and academic purposes.
