# 🌾 Crop Recommendation and Yield Prediction System

A complete machine learning-based solution to empower farmers and agricultural stakeholders. This project recommends the most suitable crops to plant based on environmental and soil parameters and predicts the expected crop yield using historical data.

This project demonstrates the practical application of machine learning in the agriculture domain by delivering two intelligent solutions: crop recommendation and yield prediction. By analyzing soil nutrients, weather conditions, and past agricultural data, we can assist farmers in making data-driven decisions that increase productivity and reduce resource wastage. The models performed exceptionally well, particularly Random Forest and Naive Bayes, and offer a foundation for building scalable, real-time agricultural advisory systems.


## 📌 Project Overview

This repository includes two major systems:

1. **Crop Recommendation System**: Predicts the best crop based on soil nutrients (N, P, K), temperature, humidity, pH, and rainfall.
2. **Crop Yield Prediction Model**: Predicts the yield (production) based on past agricultural records like crop area, year, crop type, and region.

## 🧠 Machine Learning Models Used

### ✅ Classification (Crop Recommendation)
- Decision Tree
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Support Vector Machine (SVM)

### 📈 Regression (Crop Yield Prediction)
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

## 🗂️ Dataset Sources

- [Crop Recommendation Dataset on Kaggle](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset)
- Government of India’s agricultural statistics for yield prediction (cleaned & preprocessed)

## 🔍 Features

### Crop Recommendation Inputs:
- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature
- Humidity
- pH level
- Rainfall

### Crop Yield Prediction Inputs:
- State Name
- District Name
- Crop Year
- Season
- Crop Type
- Area under Cultivation

## 📊 Performance Summary

### Crop Recommendation Accuracy:
| Model         | Accuracy (%) |
|---------------|--------------|
| Naive Bayes   | 97.28        |
| Decision Tree | 95.45        |
| KNN           | 95.00        |
| SVM           | 93.18        |

### Crop Yield Prediction Metrics:
| Model            | R² Score | RMSE  | MAE   | MSE   |
|------------------|----------|-------|-------|-------|
| Random Forest    | 97.3%    | 0.163 | 0.083 | 0.026 |
| Decision Tree    | 94.9%    | 0.227 | 0.105 | 0.051 |
| Linear Regression| 89.3%    | 0.328 | 0.199 | 0.107 |

## 🧪 Steps to Run

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/crop-recommendation-and-yield-prediction.git
cd crop-recommendation-and-yield-prediction
