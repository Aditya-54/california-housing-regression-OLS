# 🏡 California Housing Price Prediction (OLS Regression)

## 📌 Overview  
This project applies **Ordinary Least Squares (OLS) regression** to predict housing prices in California. It explores how various factors, such as **location, total rooms, median house age, and number of bedrooms**, impact housing prices.

## 📊 Dataset Description  
We use the **California Housing Prices dataset** from the **StatLib repository**. The dataset is based on the **1990 California Census** and, although not recent, serves as an excellent resource for learning and modeling housing price predictions.

### 🔹 Dataset Details  
- **Source:** StatLib Repository  
- **Data Year:** 1990  
- **Features:**
  - `longitude` 📍 → Geographic coordinate  
  - `latitude` 📍 → Geographic coordinate  
  - `housing_median_age` ⏳ → Median age of houses  
  - `total_rooms` 🏠 → Total number of rooms in a district  
  - `total_bedrooms` 🛏️ → Total number of bedrooms in a district  
  - `median_house_value` 💰 → Target variable (house price)  

## 📉 Regression Model (OLS)  
We use **Ordinary Least Squares (OLS) regression** to understand the relationship between different features and housing prices.

### 🔍 **Key Model Insights**  
- **R-squared Score:** `0.643` (Explains ~64.3% of price variance)  
- **Most Influential Factors:**
  - 📍 **Location (longitude & latitude):** Strongest impact on price  
  - 🏡 **Older houses:** Tend to have higher prices  
  - 🏠 **More rooms ≠ higher price:** Possible multicollinearity  



## 📦 Setup & Installation  
To run the project locally, follow these steps:  

1️⃣ **Clone the repository:**  

git clone https://github.com/Aditya-54/california-housing-regresssion-OLS.git


Install dependencies:
pip install -r requirements.txt

Run the Jupyter Notebook for analysis

🚀 Future Improvements
✅ Feature engineering (handle multicollinearity, outliers)
✅ Try alternative models like Random Forest, XGBoost
✅ Deploy as a Flask API for real-time predictions

📜 License
This project is for educational & learning purposes only. Dataset sourced from StatLib repository.

💡 Contributions & Feedback Welcome! 🤝



