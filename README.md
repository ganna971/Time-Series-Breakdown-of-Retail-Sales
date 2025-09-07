# Time-Series-Breakdown-of-Retail-Sales
# Task 7: Time Series Breakdown of Retail Sales  
*Part of Elevvo Internship Projects*  

## 📌 Project Description  
This project analyzes the **Walmart Sales Forecasting Dataset (Kaggle)** to uncover **time series trends and patterns** in retail sales. The dataset includes weekly sales, store information, and external features like holidays, fuel prices, and unemployment rates.  

## 📂 Dataset Files  
- **train.csv** → Weekly sales by store and department  
- **test.csv** → Test set for forecasting (not used in this analysis)  
- **features.csv** → Additional variables (holiday flag, fuel, CPI, etc.)  
- **stores.csv** → Metadata about store type and size  

## 🔧 Steps Performed  
1. **Data Cleaning & Merging**  
   - Combined `train`, `features`, and `stores` into one dataset  
   - Converted dates and extracted `Year` and `Month`  

2. **Time Series Analysis**  
   - Overall **monthly sales trends**  
   - **3-month moving average** smoothing  
   - **Seasonal patterns** (monthly averages across years)  

3. **Breakdown Analysis**  
   - Sales trends by **Store Type (A, B, C)**  
   - Sales trends for **Top 5 Product Departments**  

## 📊 Key Insights  
- **Sales seasonality:** Peak sales during November–December due to holidays  
- **Store Type A dominance:** Largest stores (Type A) consistently outperform Types B & C  
- **Departmental trends:** Certain departments show strong seasonal peaks  

## 💻 Tools Used  
- Python (Pandas, Matplotlib)  
- Jupyter/Colab Notebook  
- [Colab Notebook]:https://colab.research.google.com/drive/1PK9tC-zJyEd69cL5yFQ5Er1zEw5AuQpY?usp=sharing 
 

---
