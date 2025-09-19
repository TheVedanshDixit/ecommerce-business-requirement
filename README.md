# ecommerce-business-requirement
Business requirement analysis for a fashion e-commerce company – deciding whether to focus on mobile app or website.


# 🛒 Ecommerce Project – Business Requirement

## 📌 Project Overview
A fashion e-commerce company sells clothing online and also provides in-store styling sessions.  
Customers can purchase clothing either through the **mobile app** or the **website** after meeting personal stylists.  

The company wants to decide whether to **focus on improving the mobile app experience or the website experience**.  
This project analyzes customer data to provide a **data-driven recommendation**.

---

## 🎯 Business Objective
- Analyze customer engagement metrics such as **session length, app usage, website activity, and membership duration**.  
- Identify the key drivers of **annual customer spending**.  
- Build a predictive model to **forecast yearly spending**.  
- Provide **insights & recommendations** for platform strategy.  

---

## 📂 Repository Structure


/data
└── customers_no_outliers.csv
/notebooks
├── EDA.ipynb
└── MODEL.ipynb
/models
└── linear_regression_model.pkl
/reports
└── Group-6.pptx
README.md
requirements.txt



---

## 📊 Key Insights
- **Length of Membership** has the strongest correlation (0.81) with yearly spending.  
- **Time on App** (0.50) impacts spending more than **Time on Website** (weak effect).  
- Outliers in "Length of Membership" and "Yearly Amount Spent" were detected and removed.  
- Scatterplots and regression lines confirm positive correlation between membership length and spending.  

---

## 🤖 Model Selection
- Tested models: **Linear Regression, Lasso, Ridge**.  
- **Linear Regression** chosen → balance of simplicity & accuracy.  
- **R²** shows strong explanatory power.  
- **Low MSE** indicates minimal prediction error.  
- Final model saved as `linear_regression_model.pkl`.  

---

## 🚀 Tech Stack
- Python (Pandas, NumPy, Scikit-learn)  
- Jupyter Notebook  
- Matplotlib, Seaborn for visualization  
- PowerPoint (for presentation deck)  

---

## 👨‍💻 Author
**Vedansh Dixit**
