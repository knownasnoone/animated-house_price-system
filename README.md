# 🏠 House Price Prediction: ML vs. Deep Learning

## 📌 Project Overview
This project compares **Traditional Machine Learning** (Random Forest) and **Deep Learning** (Deep Neural Networks) to estimate house prices based on features like location, size, and amenities.

## 📂 Files
- **`Price_Prediction_ML.ipynb`**: Machine Learning implementation (Scikit-Learn, Random Forest).
- **`House_Price_Prediction_DL.ipynb`**: Deep Learning implementation (TensorFlow/Keras, DNN).
- **`cleaned_data.csv`**: Dataset required for training and testing.

## 🛠️ Technologies
![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat-square)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?style=flat-square)
![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-Latest-yellow?style=flat-square)
![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-green?style=flat-square)

## 🧠 Methodologies
### 1. Machine Learning (Random Forest)
- **Preprocessing:** Imputation, Standard Scaling, One-Hot Encoding.
- **Model:** Random Forest Regressor.

### 2. Deep Learning (DNN)
- **Feature Engineering:** Log transformations, location clustering, feature interactions.
- **Architecture:** Deep Dense Network (512 -> 64 nodes) with Dropout & L1/L2 regularization.
- **Optimization:** Adam optimizer, Huber Loss.

## 📈 Results
| Metric | Random Forest | Deep Learning |
| :--- | :--- | :--- |
| **RMSE (Log)** | ~0.38 | **~0.20** |
| **R² Score** | ~0.77 | **~0.90** |

## 🚀 How to Run
1.  **Clone the repo:**
    ```bash
    git clone [https://github.com/yourusername/house-price-prediction.git](https://github.com/yourusername/house-price-prediction.git)
    ```
2.  **Install dependencies:**
    ```bash
    pip install pandas numpy scikit-learn tensorflow matplotlib seaborn category_encoders xgboost
    ```
3.  **Run Notebooks:** Execute `House_Price_Prediction_DL.ipynb` for the best results.
