# Cross-Selling with Machine Learning on Product Recommendation

This project builds a machine learning pipeline to identify cross-selling opportunities using transactional and campaign data. We apply market basket analysis and hybrid recommendation systems to deliver more personalized and effective product recommendations.

---

## 🔧 Project Overview

This project explores how machine learning can support targeted marketing and cross-sell strategies by:

- Detecting frequently co-purchased items using association rules (Apriori, FP-Growth).
- Building hybrid recommendation systems combining collaborative filtering (KNN, SVD) with market basket logic.
- Analyzing coupon redemptions, customer demographics, and transaction patterns.
- Visualizing campaign effectiveness through Power BI dashboards.

---

## 🧠 Techniques Used

- **Market Basket Analysis**  
  - Apriori, FP-Growth  
  - Lift, Confidence, Support metrics

- **Collaborative Filtering**  
  - KNN, SVD via Surprise library  
  - RMSE and precision-based evaluation

- **Data Cleaning and Preprocessing**  
  - Handling missing values, outliers  
  - Feature engineering from transaction timestamps

- **Visualization**  
  - Power BI for dashboards  
  - Campaign performance, coupon effectiveness, demographic distribution

---

## 📁 Project Structure
├── scripts/
│ ├── association-rules.ipynb # Apriori & FP-Growth models
│ ├── k-nearest-neighbor.ipynb # Collaborative Filtering (KNN)
│ ├── SVD_Model.ipynb # SVD Recommendation Model
│ └── data-cleaning.ipynb # Preprocessing & ETL
├── Dashboard.pbix # Power BI Dashboard
├── Dashboard.pdf # PDF export of dashboard
├── Report.pdf # Full report and discussion
├── .gitignore
└── README.md

