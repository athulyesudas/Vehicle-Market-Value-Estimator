### Link to the app: https://carrpred.herokuapp.com/

# Vehicle Market Value Estimator 🚗💰

### 📌 Project Overview
The used car market often suffers from information asymmetry, leading to unfair pricing for buyers and sellers. This project is a **Machine Learning-powered pricing engine** designed to estimate the fair market value of used vehicles based on key parameters like depreciation, fuel type, and transmission.

It serves as a decision-support tool for:
- **Sellers:** To set competitive market prices.
- **Buyers:** To evaluate if a listing is overpriced.
 
### 🛠️ Tech Stack
- **Core Logic:** Python, Scikit-Learn (Random Forest Regression)
- **Data Processing:** Pandas, NumPy
- **Web Framework:** Flask (for model deployment)
- **Frontend:** HTML/CSS

### 📊 Model Logic & Key Insights
The model was trained on historical transaction data (`car data.csv`). During the Exploratory Data Analysis (EDA) phase, several key valuation drivers were identified:
1.  **Depreciation Curve:** The vehicle's age is the strongest predictor of price, following a non-linear decay.
2.  **Seller Type Impact:** 'Dealer' listings consistently show a 15-20% premium over 'Individual' sellers due to perceived trust/warranty.
3.  **Fuel Efficacy:** Diesel vehicles retained value differently than Petrol vehicles based on odometer readings.

*The model utilizes a Random Forest Regressor to capture these non-linear relationships, achieving higher accuracy than standard Linear Regression.*

### 📂 Repository Structure

### App Interface

![alt text](https://github.com/athulyesudas/Car-Price-Prediction/blob/main/readme_assets/app_interface.png?raw=true)  

