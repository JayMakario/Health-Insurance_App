#  Health Insurance Cost Prediction App

##  Project Overview
This project develops a machine learning solution to predict individual health insurance costs, enabling more accurate pricing, improved risk assessment, and better decision-making in insurance systems.

The solution is deployed as an interactive web application using Streamlit, allowing users to input customer data and receive real-time cost predictions.

---

##  Business Problem
Accurate insurance pricing is critical for profitability and competitiveness. Poor cost estimation can lead to:

- Underpricing → financial losses  
- Overpricing → loss of customers  
- Inefficient risk segmentation  

Insurance providers need data-driven tools to:
- Assess customer risk more accurately  
- Optimize pricing strategies  
- Improve customer segmentation  

This project addresses these challenges by leveraging machine learning to generate reliable cost predictions.

---

##  Objective
To build a predictive model that:
- Estimates individual health insurance charges  
- Identifies key drivers of insurance costs  
- Supports data-driven underwriting and pricing decisions  

---

##  Methodology

### 1. Exploratory Data Analysis (EDA)
- Analyzed relationships between demographic and health variables  
- Identified key patterns influencing insurance costs  

### 2. Data Preprocessing
- Handled missing values  
- Encoded categorical variables (e.g., smoking status, region)  
- Scaled numerical features where necessary  

### 3. Feature Engineering
- Selected and refined features impacting cost prediction  
- Improved model input representation  

### 4. Model Development
Trained and compared multiple models:
- Linear Regression  
- Random Forest  
- Support Vector Regression (SVR)  
- Polynomial Regression  
- XGBoost  

### 5. Model Evaluation
Models were evaluated using:
- RMSE (Root Mean Squared Error)  
- MAE (Mean Absolute Error)  
- R² Score  

---

##  Results

- **Best Model:** XGBoost  
- **RMSE:** 5008.93  
- **MAE:** 3864.69  
- **R² Score:** 0.83  

###  Interpretation
- The model explains approximately **83% of the variance** in insurance costs  
- Prediction errors (RMSE/MAE) are within a reasonable range for real-world pricing models  
- XGBoost outperformed other models due to its ability to capture complex, non-linear relationships  

---

##  Key Insights

- **Smoking status** is the most significant driver of increased insurance costs  
- **BMI** shows a strong positive correlation with charges  
- Age and health-related factors significantly influence pricing  
- Non-linear models (like XGBoost) perform better than linear models for this problem  

---

##  Live Application
 **[Click here to use the deployed Streamlit app](https://health-insuranceapp.streamlit.app/)**

### Features:
- Input customer demographic and health data  
- Receive real-time insurance cost predictions  
- Simulate how changes (e.g., smoking status, BMI) affect pricing  

---

##  Business Impact

This solution demonstrates how machine learning can:

- Improve underwriting accuracy  
- Enable more precise and competitive pricing  
- Support risk-based customer segmentation  
- Enhance decision-making in insurance operations  

---

##  Limitations & Future Improvements

### Current Limitations
- Model performance depends on dataset scope and feature availability  
- External factors (e.g., medical history, lifestyle) not included  

### Future Improvements
- Incorporate additional health and behavioral data  
- Improve model interpretability using SHAP values  
- Deploy using cloud platforms for scalability  
- Integrate into real-world insurance workflows  

---

##  Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- XGBoost  
- Matplotlib / Seaborn  
- Streamlit  

---

## 📂 Project Structure
Health-Insurance_App/
│
├── data/
├── notebooks/
├── models/
├── app.py
├── requirements.txt
└── README.md


---

##  Author
**Jonathan Makario**  
Mechanical Engineer | Data Science Enthusiast  

Background in engineering, energy systems, and project management, with a focus on applying data science to solve real-world business problems.

---

##  Conclusion
This project highlights the application of machine learning in predicting insurance costs, demonstrating both technical modeling capability and an understanding of real-world business implications in the insurance industry.
