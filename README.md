# Student Performance Prediction Model

Predicts final student grades (G3) using demographic, academic, and lifestyle factors. This project compares multiple machine learning models to identify the best predictor.

## 📌 Key Features
- **Data Analysis**: EDA with visualizations (correlation heatmaps, boxplots).
- **Feature Engineering**: Created interaction terms (e.g., `studytime * G2`).
- **Model Comparison**: Linear Regression, Random Forest, Gradient Boosting, and Bagging.
- **Best Model**: **Random Forest (RMSE: 1.277)** outperformed others.

## 📊 Results Summary
| Model               | RMSE   |
|---------------------|--------|
| Linear Regression   | 1.447  |
| **Random Forest**   | **1.277** |
| Gradient Boosting   | 1.318  |
| Bagging             | 1.288  |

![RMSE Comparison](https://i.imgur.com/5x5tF9B.png)

## 🛠️ Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/student-performance-prediction.git
   cd student-performance-prediction
