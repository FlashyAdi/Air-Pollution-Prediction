🌍 Air Pollution Prediction using AI/ML  

This project aims to predict **air pollution levels** using Machine Learning techniques.  
Currently, the repository contains **progress up to Week 2 (~60%)** including dataset preparation, preprocessing, and exploratory data analysis (EDA).  

---

📂 Repository Structure  

Air-Pollution-Prediction/  
│  
├── Data/                 # Dataset files  
├── Notebooks/            # Jupyter notebooks (Week-wise progress)  
├── requirements.txt      # Dependencies  
├── README.md             # Project documentation  

---

🚀 Current Progress  

✅ Week 1  
- Dataset collected and uploaded (`city_day.csv`)  
- Data successfully loaded in Google Colab  
- Basic column cleaning and inspection  
- Initial statistics (`describe`, missing values check)  

✅ Week 2  
- Handled missing values (numeric columns filled with mean)  
- Cleaned column names and parsed date column  
- Added feature engineering (`year`, `month`, `city_code`)  
- Performed Exploratory Data Analysis (EDA):  
  - AQI distribution  
  - AQI trend over time (sample city)  
  - Correlation heatmap  
  - Top 10 most polluted cities by average AQI  

---

📒 Usage  

1. Open notebooks inside the `Notebooks/` folder (Week 1, Week 2, etc.)  
2. Run them sequentially in Google Colab or Jupyter Notebook  
3. Upload the dataset `city_day.csv` when prompted  

---

🚧 Next Steps  

- Week 3 → Implement baseline ML models (Linear Regression, Decision Tree, Random Forest)  
- Week 4 → Evaluate performance with metrics (RMSE, R², etc.), finalize results, and improve README with findings
