# 📊 Customer Churn Analysis & Prediction

> **An end-to-end Data Analytics & Machine Learning project using SQL, Python, Scikit-learn, and Power BI to analyze customer behavior, identify churn patterns, and predict customers at risk of leaving.**

---

# 📷 Dashboard Preview

> <img width="1407" height="790" alt="image" src="https://github.com/user-attachments/assets/1a4bc569-7da6-49f1-b55d-76db366721b0" />
> <img width="1389" height="783" alt="image" src="https://github.com/user-attachments/assets/1cf48734-2195-4084-8431-2d342859522d" />


---

# 📖 Project Overview

Customer churn is one of the biggest challenges for subscription-based businesses because losing existing customers directly impacts revenue. In this project, I analyzed a telecom customer dataset to understand the main reasons behind churn and built a machine learning model to predict customers who are likely to leave.

The project starts with SQL-based exploratory data analysis to identify customer trends and business insights. The data is then cleaned and preprocessed in Python before training a Random Forest classifier. Finally, the results are visualized in an interactive Power BI dashboard to make the insights easy to understand.

---

# 🚀 Project Highlights

- Analyzed **6,418 telecom customer records** using SQL to uncover customer behavior, churn trends, and revenue patterns.
- Identified an overall **27.0% churn rate (1,732 customers)** and found that **Month-to-Month contracts (46.5%)** and **Fiber Optic services (41.1%)** had the highest churn rates.
- Discovered that **better competitor offers, pricing, and customer dissatisfaction** were the primary reasons behind customer churn.
- Developed a **Random Forest Classifier** that achieved **86% accuracy**, **85% weighted precision**, and **85% weighted F1-score** on a held-out test set of **1,202 customers**.
- Created an interactive **Power BI dashboard** to visualize KPIs, customer segmentation, churn drivers, revenue trends, and predictive insights for business decision-making.
---

# 🛠 Tech Stack

### Languages & Tools

- SQL Server
- Python
- Power BI

### Python Libraries

- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

# 📂 Repository Structure

```text
Customer-Churn-Analysis-Prediction
│
├── images/
│   ├── dashboard-overview.png
│   ├── sql-analysis.png
│   ├── churn-dashboard.png
│   ├── model-results.png
│   ├── customer-overview.png
│   ├── revenue-dashboard.png
│
├── Customer_Data.csv
├── SQLQueries.sql
├── Churn.ipynb
├── Predictions.csv
├── Churn_Analysis.pbix
└── README.md
```

---

# 📊 Dataset Overview

The dataset contains **6,418 telecom customers** with information such as:

- Customer demographics
- Internet services
- Contract type
- Payment method
- Monthly charges
- Revenue
- Customer status
- Churn category
- Churn reason

---

# 🔄 Project Workflow

```text
Customer Data
      │
      ▼
 SQL Data Analysis
      │
      ▼
 Data Cleaning & Preprocessing
      │
      ▼
 Feature Engineering
      │
      ▼
 Random Forest Model
      │
      ▼
 Churn Prediction
      │
      ▼
 Power BI Dashboard
```

---

# 🔍 Exploratory Data Analysis

Before building the prediction model, I explored the dataset using SQL to understand customer behavior and identify important business trends.

The analysis included:

- Customer distribution
- Customer status
- Revenue analysis
- Contract type analysis
- Internet service usage
- Payment method analysis
- Churn categories
- Churn reasons
- Missing value detection


---

# 💡 Key Business Insights

After exploring the data, several interesting patterns became clear.

### Customer Overview

- Total Customers: **6,418**
- Stayed: **4,275**
- Churned: **1,732**
- Joined: **411**

Almost **27% of customers had churned**, showing that customer retention is a significant business challenge.

---

### Contract Type

Customers with **Month-to-Month contracts** showed the highest churn rate, while customers with One-Year and Two-Year contracts were much more likely to stay.

This suggests that longer contract commitments improve customer retention.


---

### Payment Methods

Customers paying with **Credit Cards** had the lowest churn, whereas customers using **Mailed Checks** and **Bank Withdrawals** churned more frequently.

---

### Why Customers Leave

The most common churn reasons included:

- Better competitor offers
- Better devices from competitors
- Customer dissatisfaction
- Poor support experience
- Higher pricing

Competition and customer experience appeared to have the greatest impact on customer retention.

---

# 🤖 Machine Learning Model

After preprocessing the data, I trained a **Random Forest Classifier** to predict whether a customer is likely to churn.

The workflow included:

- Handling missing values
- Encoding categorical features
- Feature selection
- Train-test split
- Model training
- Customer churn prediction

The predictions were exported to **Predictions.csv**, allowing businesses to identify high-risk customers before they leave.

### Model Results

> <img width="636" height="330" alt="image" src="https://github.com/user-attachments/assets/10833be9-0698-46f8-9936-2be769c02521" />


---

# 📊 Power BI Dashboard

The dashboard was designed to present the analysis through interactive visualizations.

It includes:

- KPI Cards
- Customer Overview
- Revenue Analysis
- Customer Status
- Contract Distribution
- Internet Service Analysis
- Payment Method Analysis
- Churn Categories
- Interactive Filters & Slicers

---

# 🎯 Business Impact

This project shows how data analytics and machine learning can support customer retention by:

- Identifying customers with a high risk of churn.
- Understanding the main factors contributing to customer loss.
- Helping businesses prioritize retention campaigns.
- Supporting decision-making through interactive dashboards and predictive analytics.

---

# 🚀 Future Improvements

- Compare multiple machine learning models (XGBoost, LightGBM, Logistic Regression).
- Perform hyperparameter tuning.
- Deploy the model using Flask or FastAPI.
- Connect Power BI directly to a live SQL database.
- Build a real-time churn prediction API.

---

# 👨‍💻 Author

**Soham**

If you found this project helpful, feel free to ⭐ the repository.
