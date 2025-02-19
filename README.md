# House Price Prediction using Scikit-Learn & Pandas

## 📌 Project Overview
This project predicts house prices using the Boston Housing dataset. It applies machine learning techniques, including data preprocessing, feature engineering, and hyperparameter tuning.

## 🛠 Technologies Used
- Python
- Pandas, NumPy (Data Processing)
- Matplotlib, Seaborn (Data Visualization)
- Scikit-Learn (Machine Learning)
- Joblib (Model Deployment)

## 📂 Dataset
- **Source**: [Boston Housing Dataset](https://raw.githubusercontent.com/selva86/datasets/master/BostonHousing.csv)
- **Target Variable**: `medv` (Median house price)

## 🔍 Features Used
- CRIM: Per capita crime rate
- RM: Average number of rooms per dwelling
- AGE: Proportion of owner-occupied units built before 1940
- TAX: Property tax rate per $10,000
- Others (full list in the script)

## 🚀 Steps in the Project
1. **Exploratory Data Analysis (EDA)**
   - Correlation heatmap
   - Distribution plots
2. **Data Preprocessing**
   - Handling missing values
   - Feature encoding & scaling
3. **Model Training & Tuning**
   - Random Forest Regressor
   - Hyperparameter tuning using GridSearchCV
4. **Model Evaluation**
   - MAE, MSE, RMSE, R² Score
   - Feature importance analysis
5. **Results & Visualization**
   - Scatter plot (Actual vs Predicted Prices)
   - Feature importance bar chart
6. **Model Deployment**
   - Save & load model using `joblib`
   - Export predictions to `predictions.csv`

## 📈 Results & Performance
- **MAE:** [Value]
- **MSE:** [Value]
- **RMSE:** [Value]
- **R² Score:** [Value]

## 📌 How to Run the Project
1. Install dependencies:  
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn joblib
   ```
2. Run the script:  
   ```bash
   python house_price_prediction.py
   ```
3. View predictions in `predictions.csv`
4. Load trained model for new predictions:
   ```python
   import joblib
   model = joblib.load("house_price_model.pkl")
   ```

## 📩 Contact & Portfolio
Want to hire me for similar projects? Reach out on Upwork! 🚀

