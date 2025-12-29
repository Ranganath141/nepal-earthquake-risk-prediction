# Nepal Earthquake Risk Prediction

##  Problem Statement
Predict the level of destruction (Low to High) caused by earthquakes across different regions in Nepal using building and location-related attributes.

The objective is to assist in **risk assessment and disaster preparedness** by identifying high-risk zones based on historical and structural data.

---

##  Dataset Overview
- The dataset contains information related to buildings, geographical factors, and structural characteristics.
- Target variable represents **damage severity levels**.
- The data is **imbalanced**, making Macro F1-score a critical evaluation metric.

---

##  Approach
1. **Data Cleaning & Preprocessing**
   - Handling missing values
   - Feature selection and transformation

2. **Exploratory Data Analysis (EDA)**
   - Understanding feature distributions
   - Identifying key attributes affecting damage severity

3. **Handling Class Imbalance**
   - Applied techniques such as resampling and SMOTE
   - to improve minority class prediction

4. **Model Building & Comparison**
   - Trained multiple tree-based and ensemble models
   - Compared performance using Macro F1-score and Accuracy

5. **Model Evaluation**
   - Focused on Macro F1-score due to class imbalance
   - Selected best-performing model based on validation results

---

##  Models Used
- XGBoost  
- LightGBM  
- Random Forest  
- Decision Tree  

---

##  Results
- **Macro F1-score:** 0.71  
- **Accuracy:** 0.75  

The ensemble-based models outperformed single estimators, with LightGBM and XGBoost showing strong generalization on unseen data.

---

##  Key Insights
- Structural and location-based attributes significantly influence damage severity.
- Ensemble models handle complex, non-linear relationships effectively.
- Macro F1-score provides a more reliable performance measure for imbalanced multi-class problems.

---

##  Tech Stack
- **Programming Language:** Python  
- **Libraries:** NumPy, Pandas, Scikit-learn, XGBoost, LightGBM  
- **Visualization:** Matplotlib, Seaborn  
- **Modeling:** Ensemble & Tree-based ML algorithms  

---

##  How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/Ranganath141/nepal-earthquake-risk-prediction.git
