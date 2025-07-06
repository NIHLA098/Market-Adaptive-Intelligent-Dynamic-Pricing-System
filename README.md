# 💡 Market Adaptive Intelligent Dynamic Pricing System

A real-world machine learning-powered dynamic pricing engine that helps businesses optimize product prices based on actual sales behavior, demand trends, and customer purchasing patterns. Designed for the fast-paced e-commerce environment, this system ensures pricing decisions that maximize revenue and reduce financial leakage from over/underpricing.

---

## 🔗 Run in Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/17RLMT61Q6YVSyU96I2_7N7xC6e0hHovy?usp=sharing)

---

## 🧠 Problem Statement

In the real world, static pricing models fail to respond to fluctuating market conditions, often leading to missed revenue or poor competitiveness. This project solves that by building an **adaptive AI-driven pricing system** that:

- Detects patterns in product performance, seasonal demand, and returns  
- Understands the **economic context** using time-based trends  
- Recommends optimal, **real-time-informed price points** for every product

---

## 📊 Dataset Used

**Dataset:** [Online Retail Dataset – UCI / Kaggle]  
A real-world transactional dataset from a UK-based online retailer , used widely in industry projects and analytics challenges.

Key fields include:
- `InvoiceNo`, `StockCode`, `Description`  
- `Quantity`, `UnitPrice`, `InvoiceDate`  
- `CustomerID`, `Country`

---

## 🔍 Key Features Engineered

- 📈 **Revenue** = Quantity × UnitPrice  
- 📊 Product-level KPIs: units sold, product returns, revenue spikes  
- 🌎 **Country-wise trends** to uncover regional performance  
- 🕒 Demand cycles based on **month, weekday, and hour**  
- 🧠 Identification of **high-performing** and **seasonal items**

These features mirror how real-world pricing teams analyze SKUs across geography and time.

---

## ⚙️ Machine Learning Models Used

| Model                        | Purpose                                           |
|-----------------------------|---------------------------------------------------|
| ✅ Linear Regression         | Baseline price forecasting                        |
| ✅ Random Forest Regressor  | Captures complex nonlinear product interactions   |
| ✅ Gradient Boosting Regressor | Final model delivering the most accurate predictions |

---

## 📈 Evaluation Metrics

- 📉 **Mean Absolute Error (MAE)** – how close predictions are to actual prices  
- 📉 **Root Mean Squared Error (RMSE)** – penalizes larger errors  
- 📈 **R² Score** – how well the model explains price variance

🟢 The **Gradient Boosting model** outperformed others, making it highly suitable for real-world deployment scenarios.

---

## ✅ Project Outcomes

- ✅ Discovered actionable insights from real retail data  
- ✅ Developed a dynamic pricing engine with production-ready logic  
- ✅ Created a framework that aligns with industry pricing strategies  
- ✅ Built a solution that can be integrated into e-commerce tools like Shopify, BigCommerce, or ERP systems

---

## 🛠️ Tools & Technologies

- 🐍 Python (Pandas, NumPy, Scikit-learn)  
- 📊 Matplotlib & Seaborn for business-focused data visualizations  
- ☁️ Google Colab for accessible, shareable development  
- 📁 Excel (.xlsx) – real-world structured data source

---

##  Contact

For queries, suggestions, or collaboration opportunities:  
 **Email:** fathimanihla841@gmail.com


