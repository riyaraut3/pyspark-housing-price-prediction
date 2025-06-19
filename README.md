# C Housing Price Prediction Using PySpark

This project predicts median house values in California districts using the PySpark MLlib pipeline. It involves data preprocessing, feature engineering, and the training of a linear regression model with performance evaluation using `RegressionMetrics`.

## 📊 Dataset
The dataset includes features such as:
- Longitude, Latitude
- Housing median age
- Total rooms, Total bedrooms
- Population, Households
- Median income
- Ocean proximity (categorical)

## ⚡ Why Spark?
Apache Spark was used to build a **scalable and efficient machine learning pipeline** for housing price prediction. Spark's ability to process large datasets in parallel, combined with its integrated DataFrame and MLlib APIs, made it ideal for performing **data preprocessing, feature engineering, model training, and evaluation**—all within a distributed computing framework.

## 🔧 Tools & Technologies
- Apache Spark (PySpark)
- Spark MLlib (Linear Regression, OneHotEncoder, StringIndexer, VectorAssembler)
- Spark DataFrame & RDD APIs
- RegressionMetrics (RMSE, MAE, R²)

## 🔁 Pipeline Overview
1. **Data Cleaning**: Null value imputation and filtering
2. **Categorical Encoding**: StringIndexer + OneHotEncoder
3. **Feature Vectorization**: Using VectorAssembler
4. **Model Training**: LinearRegression from Spark MLlib
5. **Evaluation**: RDD conversion and metric calculation with RegressionMetrics

## ✅ Results
- Root Mean Squared Error (RMSE): _your_value_
- R² (Coefficient of Determination): _your_value_
- Mean Absolute Error (MAE): _your_value_

## 📁 Structure
