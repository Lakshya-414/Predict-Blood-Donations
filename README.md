# Predicting Blood Donation Using Machine Learning  

## 📌 Project Overview  
This project aims to predict whether a blood donor will donate again in the future using machine learning techniques. The dataset consists of **748 blood donors** from a mobile blood donation vehicle in Taiwan. By analyzing donation patterns, we can help blood banks optimize their collection efforts and ensure a stable blood supply.  

## 📂 Dataset  
The dataset follows the **RFMTC (Recency, Frequency, Monetary, Time, and Compactness) model**, commonly used in marketing analytics. It contains the following features:  
- **Recency** – Months since the last donation  
- **Frequency** – Total number of donations  
- **Monetary** – Total volume of blood donated  
- **Time** – Months since the first donation  
- **Target** – Whether the donor donated in March 2007 (1 = Yes, 0 = No)  

## 🚀 Project Workflow  
1. **Data Preprocessing**  
   - Checked for missing values  
   - Normalized high-variance features using **log transformation**  
   - Split data into **training (75%)** and **testing (25%)** sets  

2. **Machine Learning Models**  
   - **Logistic Regression** (Baseline model)  
   - **TPOT Classifier** (Automated ML pipeline selection)  

3. **Model Evaluation**  
   - Used **AUC Score** as the primary performance metric  
   - **TPOT achieved an AUC of 0.7850**, slightly outperforming logistic regression  
   - Compared results using **confusion matrices and feature importance analysis**  


## 🛠️ Technologies Used  
- **Programming Language**: Python  
- **Libraries**: Pandas, NumPy, Scikit-learn, TPOT  
- **Model Evaluation Metrics**: AUC Score, Accuracy  
