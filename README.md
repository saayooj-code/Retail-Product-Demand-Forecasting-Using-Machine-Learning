# Retail-Product-Demand-Forecasting-Using-Machine-Learning
Machine Learning project for predicting retail product demand using customer behavior, product, competitor, marketing, and market-related features. The project uses data preprocessing, EDA, feature engineering, Random Forest and XGBoost regression to forecast demand and support better inventory and business planning.

📊 Retail Product Demand Forecasting Using Machine Learning

A machine learning project that predicts retail product demand using customer behavior, product information, pricing, competition, marketing activity, and seasonal demand patterns.

The project uses Random Forest Regressor and XGBoost Regressor to estimate product demand and provides a user-friendly Gradio interface for predictions.

🚀 Project Overview

Retail businesses need accurate demand forecasts to manage inventory, understand customer behavior, reduce stockouts, and improve business planning.

This project analyzes multiple retail factors such as:

Customer footfall
Online search activity
Product page views
Add-to-cart rate
Product ratings and reviews
Brand popularity
Shelf availability
Advertising impressions
Social media mentions
Campaign intensity
Product pricing
Competitor pricing
Competitor information
Seasonal patterns
Demand momentum and volatility

The trained machine learning models predict the expected Demand for a retail product.

🎯 Objectives
Predict retail product demand using machine learning.
Analyze important factors affecting product demand.
Perform data cleaning and preprocessing.
Handle missing values.
Perform feature engineering.
Encode categorical features.
Train and compare machine learning models.
Evaluate model performance using regression metrics.
Save the trained model for future predictions.
Provide an interactive Gradio prediction interface.
📁 Dataset

The project uses a retail demand dataset containing:

120,000 records
50 columns
Target variable: Demand
Important Features
Feature	Description
Customer_Footfall	Number of customers visiting the store
Avg_Basket_Size	Average number/value of items in a basket
Returning_Customer_Rate	Rate of returning customers
Online_Search_Count	Number of online product searches
Product_Page_Views	Product page views
Add_To_Cart_Rate	Rate of customers adding products to cart
Product_Rating	Average product rating
Review_Count	Number of product reviews
Brand_Popularity_Score	Popularity score of the brand
Shelf_Availability	Product availability on shelves
Ad_Impressions	Number of advertisement impressions
Social_Media_Mentions	Social media mentions
Campaign_Intensity	Marketing campaign intensity
Our_Price	Product price
Competitor_Price	Competitor product price
Price_Gap	Difference between our price and competitor price
Nearby_Competitor_Count	Number of nearby competitors
Seasonal_Demand_Index	Seasonal demand indicator
Demand_Momentum	Current demand trend
Demand_Volatility	Variation in demand
Demand_Acceleration	Change in demand growth
Target

Demand

🔄 Machine Learning Workflow
Dataset
   ↓
Data Loading
   ↓
Data Inspection
   ↓
Missing Value Analysis
   ↓
Data Cleaning
   ↓
Feature Engineering
   ↓
Categorical Encoding
   ↓
Train-Test Split
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Best Model Selection
   ↓
Model Saving
   ↓
Gradio Prediction Interface
🧹 Data Preprocessing

The project performs several preprocessing steps:

Dataset loading using Pandas
Data type inspection
Missing-value analysis
Date conversion
Date-based feature engineering
Dataset sorting
Numerical feature preparation
Categorical feature encoding
Preparation of training and testing data

Categorical features include:

Product_Size
Product_Lifecycle

The target variable is:

Demand
🧠 Machine Learning Models
1. Random Forest Regressor

Random Forest is used to capture nonlinear relationships between retail features and product demand.

2. XGBoost Regressor

XGBoost is a gradient-boosting algorithm used to build a strong predictive regression model.

The models are compared using regression evaluation metrics and the better-performing model is selected for prediction.

📈 Evaluation Metrics

The project uses:

MAE — Mean Absolute Error
RMSE — Root Mean Squared Error
R² Score — Coefficient of Determination
MAE

Measures the average absolute difference between actual and predicted demand.

RMSE

Measures prediction error while giving greater importance to larger errors.

R² Score

Shows how well the model explains the variation in the target variable.

The exact final metric values should be taken from the final model-training output rather than adding estimated numbers.

💻 Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
XGBoost
Joblib
Gradio
Jupyter Notebook / Anaconda
📦 Project Structure
Retail-Product-Demand-Forecasting/
│
├── projectprese(1).ipynb
├── retail_demand.csv
├── best_model.pkl
├── cat_encoder.pkl
├── feature_columns.pkl
├── README.md
└── requirements.txt
🖥️ User Interface

The project includes an interactive Gradio interface where users can provide product and retail-related information and receive a predicted demand value.

Example
Input Retail Features
        ↓
Trained ML Model
        ↓
Predicted Demand
⚙️ Installation

Clone the repository:

git clone https://github.com/yourusername/retail-product-demand-forecasting.git
cd retail-product-demand-forecasting

Install the required libraries:

pip install pandas numpy matplotlib seaborn scikit-learn xgboost joblib gradio
▶️ Running the Project

Open the notebook:

jupyter notebook

Then open:

projectprese(1).ipynb

Run the cells sequentially.

Make sure the dataset is available:

retail_demand.csv
🌟 Key Features
📊 Large dataset with 120,000 records
🛒 Retail demand prediction
👥 Customer behavior analysis
📱 Online customer activity analysis
💰 Price and competitor analysis
📢 Marketing and advertising features
📅 Seasonal and time-based features
🤖 Random Forest and XGBoost models
📈 Regression model evaluation
🖥️ Interactive Gradio interface
💾 Saved machine learning model
🔮 Future Improvements
Deploy the model using Streamlit or Hugging Face Spaces.
Add real-time retail data integration.
Add advanced time-series forecasting models.
Implement automated model retraining.
Add explainable AI using SHAP.
Build an interactive demand analytics dashboard.
Add inventory optimization recommendations.
👨‍💻 Author

Sayooj

Data Science Student
Trycod Tech School

📌 Project Type

Machine Learning | Regression | Retail Analytics | Demand Forecasting

⭐ If you find this project useful, consider giving the repository a star!
