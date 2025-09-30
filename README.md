# 🌡️ Temperature Forecasting: Predicting Temperature from Humidity & Pressure

##  Project Overview
This project applies **Machine Learning models** to predict temperature from environmental factors such as **humidity, pressure, latitude, and longitude**.  
The predictions are further visualized in a **Tableau dashboard** to compare **Actual vs Predicted Temperatures**, analyze **residuals**, and explore relationships with humidity and pressure.  

---

##  Objectives
- Predict temperature using machine learning models.  
- Compare model performance using **RMSE** and **R² Score**.  
- Build an interactive **Tableau dashboard** for stakeholders to explore results.  
- Provide insights on the effect of **humidity & pressure** on temperature.  

---

##  Dataset
- **Features:** Humidity, Pressure, Latitude, Longitude  
- **Target:** Temperature (°C)  
- Sample datasets are included in the `data/` folder.  

---

##  Workflow
1. **Data Preprocessing & EDA** (Python, Pandas, Matplotlib, Seaborn)  
2. **Model Training:**  
   - Linear Regression  
   - Lasso Regression  
   - Random Forest Regressor  
   - Gradient Boosting Regressor  
3. **Evaluation Metrics:**  
   - RMSE (Root Mean Squared Error)  
   - R² Score  
   - Residual Analysis  
4. **Visualization:**  
   - Tableau dashboard showing KPIs, model comparison, and Top-N filters.  

---

## 🚀 Model Performance
| Model                 | RMSE  | R² Score |
|------------------------|-------|----------|
| Linear Regression      | 9.81  | 0.50     |
| Lasso Regression       | 10.22 | 0.47     |
| Random Forest Regressor| 1.86  | 0.98     |
| Gradient Boosting      | 2.31  | 0.97     |

✅ **Random Forest** performed the best with **RMSE ≈ 1.86°C** and **R² ≈ 0.98**.  

---

## 📊 Tableau Dashboard
The dashboard includes:  
- **KPIs:** RMSE, R² Score  
- **Visuals:**  
  - Predicted vs Actual Temperature  
  - Predicted Temp vs Humidity  
  - Predicted Temp vs Pressure  
  - Residuals table  
  - Top-N filter for flexible insights  

### 🔗 Preview  
<img width="1919" height="994" alt="Screenshot 2025-09-30 202255" src="https://github.com/user-attachments/assets/4f903b45-14fe-46b3-89dd-8113be103c0c" />

https://public.tableau.com/app/profile/rajat.kumar8264/viz/Book1_17591708163430/Dashboard1?publish=yes
---
