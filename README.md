# Online Retail Sales Analysis & Dashboard

## 🚀 Business Problem

An e-commerce business lacks visibility into **revenue drivers, customer concentration, and return behavior**, making it difficult to optimize sales strategy and reduce losses.

---

## 🎯 Objective

Translate raw transactional data into **actionable insights** to:

* Identify **revenue drivers (volume vs value)**
* Detect **seasonal demand patterns**
* Analyze **customer and geographic concentration**
* Quantify **return impact on revenue**

---

## 🛠️ Tech Stack

* **Python**: Pandas, NumPy, Matplotlib (data cleaning & analysis)
* **Tableau**: Interactive dashboard
* **Dataset Size**: 1M+ transactions

---

## ⚙️ Data Preparation

* Removed invalid transactions (negative quantity, zero price)
* Handled missing values and inconsistent entries
* Engineered key features:

  * **Revenue = Quantity × Price**
  * **Year-Month for trend analysis**
* Separated **returns vs actual sales**

---

## 📊 Key Metrics Built

* Total Revenue
* Number of Orders
* Average Order Value (AOV)
* Return Rate

---

## 🔍 Key Insights (Business-Focused)

* **Seasonality drives revenue** → Peak in Nov–Dec indicates strong holiday demand
* **Revenue = Volume + AOV** → Growth depends on both order frequency and basket size
* **High customer concentration** → Small % of customers generate majority of revenue (retention risk)
* **Geographic dependency** → UK dominates revenue → expansion opportunity/risk
* **Returns stable (~3.5%)** → manageable but still impacts net revenue

---

## 📈 Dashboard

🔗 https://public.tableau.com/app/profile/kukudala.sreejani/viz/RetailSalesReturnsAnalysisDashboard/Dashboard52

---

## 💡 Business Impact

This analysis enables:

* Better **inventory planning for peak seasons**
* **Customer retention strategies** for high-value users
* Identification of **market expansion opportunities**
* Monitoring and control of **returns impact on revenue**

---

## ⚠️ Limitations

* Missing customer IDs for some transactions
* No customer segmentation (demographics unavailable)
* Descriptive analysis only (no forecasting)

---

## ✅ Conclusion

This project demonstrates how raw transactional data can be transformed into **decision-ready insights** using data cleaning, analysis, and visualization.
