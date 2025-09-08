# 🏡 California Housing Price Prediction

This project is part of a supervised learning assignment.  
I use the California Housing dataset to predict house prices and classify houses as above/below the median price.  

The project follows the steps shown in the tutorial and covers:
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Train-Test Split
- Data Preprocessing
- Training Models (Logistic Regression, KNN, Decision Tree, Random Forest)
- Model Evaluation
- Conclusion

---

## 📂 Steps in the Project

### 1. Upload and Load Data
- Upload the `housing.csv` dataset
- Load into a Pandas DataFrame

### 2. Import Libraries
- Pandas, NumPy for data handling  
- Matplotlib, Seaborn for visualization  
- Scikit-learn for preprocessing, training, and evaluation  

### 3. Explore Data
- Display first rows and dataset info  
- Summary statistics  

### 4. Data Cleaning
- Handle missing values in `total_bedrooms` using the median  
- Drop duplicate rows  

### 5. Exploratory Data Analysis
- Histograms for the distribution of features  
- Correlation heatmap  
- Scatter plots:  
  - Longitude vs Latitude (California map)  
  - Median Income vs Median House Value  

### 6. Feature Engineering
New features created:
- `rooms_per_household`  
- `bedrooms_per_room`  
- `population_per_household`  

### 7. Train-Test Split
- Train set: 80%  
- Test set: 20%  

### 8. Preprocessing
- Scale numerical features  
- One-hot encode categorical features  

### 9. Train Models
I train multiple supervised learning models:
- **Linear Regression**  
- **Logistic Regression** (for classification task)  
- **K-Nearest Neighbors (KNN)**  
- **Decision Tree**  
- **Random Forest**  

### 10. Model Evaluation
- **Regression metrics**: RMSE, MAE, R²  
- **Classification metrics**: Accuracy, Precision, Recall, F1-score  

### 11. Conclusion
- Random Forest performed best for regression  
- Logistic Regression was useful for classification  
- Data cleaning + feature engineering improved results  

---

## 🚀 How to Run
1. Open the notebook in Google Colab  
2. Upload `housing.csv` when prompted  
3. Run all cells step by step  

---

## 📌 Requirements
- Python 3  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

✍️ **Author:** Mazen Mohammed 
📅 **Course Assignment - Sep 2025**
