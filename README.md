# 🏠 New York House Price Prediction

This project predicts house prices in New York using machine learning based on property features and location.

## 📊 Features Used
- `PROPERTYSQFT` – Property square footage  
- `BEDS` – Number of bedrooms  
- `BATH` – Number of bathrooms  
- `TYPE` – Type of property (e.g., Condo, House)  
- `SUBLOCALITY` – Area or neighborhood  
- `PRICE` – Target variable (House price)

## 🛠️ Preprocessing
- Removed missing/invalid values  
- Dropped outliers (e.g., repeated float value in `BATH`)  
- Applied log transformation to `PRICE` and `PROPERTYSQFT`  
- Encoded `TYPE` and `SUBLOCALITY`  
- Standardized features for regression

## 🤖 Models Used
- Linear Regression  
- Random Forest Regressor  

## 📈 Evaluation Metrics
- **Linear Regression (Log-Transformed)**: R² ≈ 0.45  
- **Random Forest Regressor**: R² ≈ 0.30  

## 📌 Visualizations
- Square Footage vs Price scatter plots  
- Log-transformed regression plots  
- Residual distributions  

## 🚀 How to Run

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

