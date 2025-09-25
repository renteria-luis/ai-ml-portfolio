# Online Retail Analysis

This is a small project exploring the [UCI Online Retail dataset](https://archive.ics.uci.edu/ml/datasets/online+retail).  
Main goal was to practice cleaning data, running some basic analytics, and pulling out useful business insights.  

---

## 🔎 What I did
- Cleaned the dataset (removed cancelled invoices, fixed CustomerIDs, dropped weird country values).  
- Looked at customers using **RFM analysis** (Recency, Frequency, Monetary).  
- Checked the **Pareto 80/20 rule** to see how revenue is distributed.  
- Found the **top products and countries** by sales.  
- Looked at **monthly revenue trends** to spot seasonality.  

---

## 📊 Key Insights
**Time span analyzed:** Dec 2010 → Dec 2011  

**Unique counts:** 18,532 invoices / 4,338 customers / 3,665 products / 37 countries  

**Top-selling products**  
- By quantity: *PAPER CRAFT , LITTLE BIRDIE*, *MEDIUM CERAMIC TOP STORAGE JAR*, *WORLD WAR 2 GLIDERS ASSTD DESIGNS*  
- By revenue: *PAPER CRAFT , LITTLE BIRDIE*, *REGENCY CAKESTAND 3 TIER*, *WHITE HANGING HEART T-LIGHT HOLDER*  

**Top countries**  
- Transactions: United Kingdom, Germany, France  
- Revenue: United Kingdom, Netherlands, Ireland (EIRE)  

**Pareto test**  
About **26% of customers generate 80% of the revenue** → a classic Pareto pattern.  

---

## ⚠️ Notes
- Data only covers one year (Dec 2010–Dec 2011).  
- Cancelled invoices are excluded.  
- Some records had `"Unspecified"` or `"European Community"` as country, I left those out of the country analysis.  

---

## 🚀 Next steps
- I’ll use this same dataset to create more visuals and plots with **Matplotlib** and **Seaborn**.  
- I plan to apply **Machine Learning methods** (like clustering, churn prediction, or customer lifetime value models).  
