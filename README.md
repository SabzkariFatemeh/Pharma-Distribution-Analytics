# 💊 Pharma Distribution Analytics

**Customer intelligence for pharmaceutical wholesale** — EDA, RFM segmentation, and churn risk identification.

---

## 🎯 Business Problem

Pharmaceutical distribution companies need to understand:
- Which customers are most valuable?
- Who is at risk of leaving?
- How can we optimize sales efforts?
 
 ---

## 📊 Dataset
- **Source:** Kaggle — [Pharma Data Analysis](https://www.kaggle.com/datasets/akanksha995579/pharma-data-analysis)
- **254K transactions** | **751 customers** | **2017–2020**

---

## 🔍 What I Did

### 1. Exploratory Data Analysis
- Sales by channel, city, product class, team
- Monthly sales trend (seasonality: Q4 > Q1 by 30%)
- Top city: Tehran (28% of sales)
- Top product class: Antibiotics (35% share)

### 2. RFM Customer Segmentation
| Segment | Count | % |
|---------|-------|---|
| Champions | 185 | 24.6% |
| Loyal | 192 | 25.6% |
| At Risk | 174 | 23.2% |
| Lost | 120 | 16.0% |
| New | 80 | 10.7% |

**Key insight:** 50% are high-value, but 23% need urgent win-back campaigns.

### 3. Churn Risk Prediction
- **Model:** Random Forest
- **Accuracy:** ~98%
- **Top drivers:** Low frequency, low avg order value
- **37 customers** identified with >70% churn probability

---

## 🛠 Tools
Python (Pandas, Scikit-learn, Matplotlib, Seaborn) | Jupyter | Git
