# 🛍️ Retail Customer Segmentation using RFM & K-Means

## 📌 Overview
This project analyzes 541,909 retail transactions from a UK-based online store to segment customers into meaningful groups using RFM (Recency, Frequency, Monetary) analysis and K-Means clustering.

## 🎯 Business Goal
Help the marketing team identify distinct customer groups so they can tailor campaigns, reduce churn, and maximize revenue.

---

## 📊 Key Findings

| Segment | Recency | Frequency | Monetary | Count |
|---|---|---|---|---|
| 👑 VIP | 161 days | 66 orders | $85,826 | 26 |
| ⚠️ At Risk | 226 days | 5 orders | $2,045 | 2,215 |
| 💤 Casual | 80 days | 3 orders | $1,013 | 2,097 |

### Business Recommendations
- **👑 VIP (26 customers)** — Offer exclusive loyalty rewards, dedicated account managers
- **⚠️ At Risk (2,215 customers)** — Launch re-engagement email campaign with discount codes
- **💤 Casual (2,097 customers)** — Send frequency-boosting promotions like "buy 2 get 1 for free"

---

## 🗂️ Project Structure
```
retail-customer-segmentation/
│
├── notebook.ipynb
├── README.md
├── requirements.txt
├── data/
│   └── rfm_segments.csv
└── images/
    └── elbow_plot.png
```

---

## 📈 Dataset
Download the dataset from:
[UCI Online Retail Dataset](https://archive.ics.uci.edu/dataset/352/online+retail)

Place it in the root folder as `online_retail.csv` before running.

---

## 🛠️ Tools Used
- **Python** — Core language
- **Pandas** — Data manipulation
- **Scikit-learn** — K-Means clustering
- **Matplotlib** — Visualization

---

## 👤 Author
**Azizbek Abdullayev**  
[LinkedIn](https://linkedin.com/in/yourprofile) · [GitHub](https://github.com/yourusername)

