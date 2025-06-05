# Pump it Up: Data Mining the Water Table

A machine learning project for classifying water pump functionality in Tanzania using various classification algorithms. This project was part of the CC519 Data Mining Course at the AASTMT.

## 🏆 Competition
This project was developed for the "Pump it Up: Data Mining the Water Table" competition on DrivenData, focusing on improving water access through predictive analytics.

## Project Overview

This project tackles the challenge of predicting the operational status of water pumps in Tanzania using machine learning techniques. The goal is to classify pumps into three categories:
- **Functional**: Working properly
- **Functional needs repair**: Working but requires maintenance
- **Non-functional**: Not working

## Results

We achieved **80.98% accuracy** with our best-performing model, demonstrating the potential for machine learning in predictive maintenance of water infrastructure.

### Model Performance Comparison

| Model | Accuracy | Best For |
|-------|----------|----------|
| **Random Forest** | **81%** | Overall best performance with balanced metrics |
| XGBoost | 80% | Good overall performance |
| CatBoost | 80% | Highest precision for "needs repair" category |
| Decision Tree | 74% | Baseline model |

## Technical Approach

### Models Implemented
- **Decision Tree**: Simple baseline model
- **Random Forest**: Ensemble method with best overall performance
- **XGBoost**: Gradient boosting algorithm
- **CatBoost**: Advanced gradient boosting for categorical features

### Dataset
- **Source**: Taarifa water pump dataset from DrivenData competition
- **Size**: 59,000+ water points in Tanzania
- **Features**: Geographic location, construction year, water quality, pump type, operational status
- **Split**: 80% training, 20% testing

### Evaluation Metrics
- Accuracy
- Precision, Recall, and F1-Score for each class
- Balanced performance across all three categories

## Key Findings

1. **Random Forest emerged as the top performer** with 81% accuracy and balanced metrics across all categories
2. **Challenge identified**: All models struggled with the "functional needs repair" category, indicating class imbalance issues
3. **Practical impact**: The model can help prioritize maintenance efforts and resource allocation

## Tech Stack
- **Primary Language:** Python
- **Environment:** Jupyter Notebook
- **ML Libraries:** Scikit-learn, XGBoost, CatBoost
- **Data Processing:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn

## collaborators

- **Jasmine Elmahalawy** 
- **Khloud Maged** 
