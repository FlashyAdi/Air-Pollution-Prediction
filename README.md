🌍 Air Pollution Prediction using AI/ML  

This project aims to predict **air pollution levels (AQI)** using Machine Learning techniques.  
The repository contains week-wise progress (Weeks 1–4) including dataset preparation, preprocessing, EDA, model building, and final evaluation.

---

📂 Repository Structure  

Air-Pollution-Prediction/  
│  
├── Data/                 # Dataset files  
├── Notebooks/            # Jupyter notebooks (Week-wise progress)  
├── requirements.txt      # Dependencies  
├── README.md             # Project documentation  

---

🚀 Project Progress

✅ Week 1
- Dataset collected and uploaded (`city_day.csv`)  
- Data successfully loaded in Google Colab  
- Basic column cleaning and inspection  
- Initial statistics (`describe()`, missing values check)  

✅ Week 2
- Handled missing values (numeric columns filled with mean)  
- Cleaned column names and parsed `date` column  
- Added feature engineering (`year`, `month`, `city_code`)  
- Performed Exploratory Data Analysis (EDA):  
  - AQI distribution  
  - AQI trend over time (sample city)  
  - Correlation heatmap  
  - Top 10 most polluted cities by average AQI  

✅ Week 3
- Built baseline ML models:  
  - Linear Regression  
  - Decision Tree  
- Evaluated with **R² Score** and **RMSE**  

✅ Week 4 (Final)
- Implemented advanced model: **Random Forest Regressor**  
- Compared performance with baseline models  
- Visualized feature importance  
- Saved trained Random Forest model (`final_aqi_model.joblib`)  
- Prepared final notebook combining preprocessing + EDA + modeling  

---

📒 Usage

1. Open any notebook from the `Notebooks/` folder in Google Colab.  
2. Upload the dataset file (`city_day.csv`) when prompted.  
3. Run all cells sequentially to reproduce results.  
4. For complete workflow, use `Air_Pollution_Prediction_Final.ipynb`.  

---

📊 Results

- Linear Regression gave baseline predictions.  
- Random Forest Regressor performed significantly better with higher R² and lower RMSE.  
- Key contributing features: **PM2.5, PM10, NO2, SO2, CO**  
- Identified top polluted cities and important temporal trends (`month`, `year`)  

---

🚧 Future Work

- Try advanced deep learning models (**LSTM**, **GRU**) for time-series forecasting  
- Deploy the model as a simple web app (**Streamlit/Flask**)  
- Extend dataset with real-time air quality API integration
