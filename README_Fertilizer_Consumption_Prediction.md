# 🌾 Fertilizer Consumption Prediction Using Machine Learning

## 📘 Overview  
This project aims to **predict fertilizer consumption** across Indian districts using machine learning models.  
It leverages agricultural data such as nitrogen, phosphate, and potash usage to understand fertilizer trends and assist in smart agricultural planning.

---

## 🧠 Project Summary
- **Total Records:** 3,171  
- **Total Features:** 20  
- **Dataset Size:** 495.6 KB  
- **Data Source:** Fertilizer consumption dataset (district-wise and year-wise)

---

## ⚙️ Workflow
1. **Data Loading & Cleaning:**  
   - Loaded Excel data into pandas  
   - Verified no missing values across 20 columns  

2. **Feature Engineering:**  
   - Selected key indicators like NPK ratios and per-hectare consumption  
   - Encoded categorical variables (State, District)

3. **Model Building:**  
   - Trained regression models to predict fertilizer usage  
   - Evaluated models based on performance metrics  

4. **Visualization & Insights:**  
   - Distribution plots for nitrogen, phosphate, and potash  
   - Correlation heatmaps for feature importance  

---

## 📊 Key Results
- **Dataset Shape:** (3171, 20)  
- **Model Performance:**  
  - ✅ **Accuracy:** 96.00%  
  - 📉 **MSE:** 0.0546  
- **Top Correlated Features:**  
  - Nitrogen Per Hectare of NCA  
  - Phosphate Per Hectare of NCA  
  - Potash Share in NPK  

---

## 🧰 Technologies Used
- **Python** 🐍  
- **Libraries:** Pandas, NumPy, Matplotlib, Scikit-learn, Seaborn, XGBoost  
- **Environment:** Jupyter Notebook  

---

## 🚀 How to Run
```bash
git clone https://github.com/yourusername/Fertilizer_Consumption_Prediction.git
cd Fertilizer_Consumption_Prediction
pip install -r requirements.txt
jupyter notebook Fertilizer_Consumption_Prediction_Using_Machine_Learning.ipynb
```

---

## 📈 Conclusion
The model efficiently predicts fertilizer usage patterns, offering insights for policymakers and agricultural planners to ensure **balanced and optimized fertilizer consumption**.
