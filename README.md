# 🛍️ Customer Shopping Behavior Analytics  
## Revenue Optimization | Customer Segmentation | Subscription Growth Strategy

---

## 📌 Executive Summary

Performed end-to-end customer behavior analysis on **3,900+ transactional records** to identify revenue drivers, optimize discount strategy, improve customer segmentation, and increase subscription conversion.

Built a scalable analytics workflow using:

- Python (Data Cleaning & Feature Engineering)
- PostgreSQL (Advanced SQL & Business Queries)
- Power BI (Executive Dashboarding)

The project focuses on delivering **data-driven business decisions** aligned with product-based company standards: revenue growth, retention improvement, margin optimization, and customer lifetime value enhancement.

---

# 🧠 Business Problem Statement

E-commerce businesses struggle with:

- Identifying high-value customer segments  
- Over-reliance on discounting  
- Low subscription penetration  
- Inefficient marketing targeting  
- Lack of data-backed segmentation  

This project addresses these problems using structured analytics and KPI-driven insights.

---

# 📊 Dataset Overview

- **Transactions:** 3,900  
- **Features:** 18  
- **Data Quality Fix:** 37 missing review ratings (handled via median imputation by category)

### Key Dimensions
- Customer: Age, Gender, Location, Subscription Status
- Transaction: Item, Category, Purchase Amount, Season
- Behavioral: Discount Usage, Shipping Type, Purchase Frequency
- Satisfaction: Review Rating

---

# 🛠️ Data Engineering & Pipeline

### 1️⃣ Data Cleaning (Python)
- Schema validation (`df.info()`, `describe()`)
- Missing value treatment
- Column normalization (snake_case)
- Removed redundant fields (`promo_code_used`)
- Created derived features:
  - `age_group`
  - `purchase_frequency_days`

### 2️⃣ Database Integration
- Connected to PostgreSQL using SQLAlchemy
- Loaded cleaned data for scalable SQL analysis
- Structured analytical queries for KPI extraction

---

# 📈 Advanced Business Analysis (SQL)

---

## 1️⃣ Revenue Contribution by Gender

- Male Revenue: **$157,890**
- Female Revenue: **$75,191**

### Insight
Male customers contribute ~68% of total revenue.

### Product Strategy
- Under-penetrated female segment = growth opportunity
- Personalization & targeted discount campaigns can expand TAM

---

## 2️⃣ Age-Based Revenue Segmentation (Revenue Share Model)

| Age Group      | Revenue | % Contribution |
|---------------|----------|----------------|
| Middle Aged   | $68,066  | 29.20% |
| Adult         | $65,216  | 27.98% |
| Young Adult   | $52,905  | 22.70% |
| Senior        | $46,894  | 20.12% |

### Strategic Insight
Middle-Aged (45–60) segment is the highest revenue-generating cohort.

### Product-Level Growth Levers
- Premium product recommendations
- Express shipping upsell
- Loyalty tier upgrade programs
- High-margin product targeting

This segment should drive retention and LTV strategies.

---

## 3️⃣ Subscription Performance Analysis

| Subscription | Customers | Avg Spend | Total Revenue |
|-------------|------------|------------|---------------|
| Yes | 1053 | $59.49 | $62,645 |
| No  | 2847 | $59.87 | $170,436 |

### Insight
Subscribers show similar AOV but lower base count.

### Product Strategy
- Increase subscription penetration among loyal customers
- Target repeat buyers (>5 purchases) for subscription conversion
- Offer value-added benefits (shipping, early access)

This directly increases recurring revenue and CLV.

---

## 4️⃣ High-Spending Discount Users

- 839 customers used discounts yet spent above average.

### Insight
Discounting does not always reduce basket size.

### Business Implication
- Introduce smart discounting (tier-based offers)
- Increase average order value (AOV)
- Reduce blanket discounting

---

## 5️⃣ Discount Dependency Risk

Top Discount-Heavy Products:

- Hat (50%)
- Sneakers (49.66%)
- Coat (49.07%)
- Sweater (48.17%)
- Pants (47.37%)

### Risk
Heavy reliance on promotions → margin pressure.

### Optimization Strategy
- Improve product positioning
- Bundle with high-rated products
- Dynamic pricing experiments (A/B testing ready)

---

## 6️⃣ Shipping Behavior & Premium Signals

- Express Avg Spend: $60.48
- Standard Avg Spend: $58.46

### Insight
Express users indicate premium intent.

### Product Lever
- Upsell faster shipping
- Introduce premium membership shipping bundles

---

# 📊 Customer Segmentation

| Segment | Customers |
|----------|------------|
| Loyal | 3,116 |
| Returning | 701 |
| New | 83 |

### Insight
Strong retention base → opportunity to improve monetization.

### Growth Strategy
- Convert Loyal → Subscribers
- Introduce gamified loyalty tiers
- Predict churn risk via frequency modeling

---

# 📈 Power BI Executive Dashboard

Designed KPI-driven dashboard including:

- Total Revenue ($233K)
- Average Order Value ($59.76)
- Revenue by Category
- Sales by Age Segment
- Discount Penetration
- Shipping Mix
- Product Ratings
- Payment Behavior

Dashboard built for executive stakeholders and product managers.

---

# 🚀 High-Impact Business Recommendations

### 1️⃣ Increase Subscription Penetration
Target repeat buyers for recurring revenue expansion.

### 2️⃣ Focus on Middle-Aged Segment (29% Revenue Share)
Drive premium SKUs and loyalty upgrades.

### 3️⃣ Reduce Discount Dependency
Implement smart pricing experiments.

### 4️⃣ Expand Female Revenue Share
Personalized campaigns & product targeting.

### 5️⃣ Upsell Premium Shipping
Leverage high-intent customers.

---

# 🏗️ Scalability & Product Thinking

This project demonstrates:

- Revenue share modeling
- Customer lifetime value thinking
- Margin-risk analysis
- Segmentation strategy
- Cross-sell & upsell opportunities
- Data-backed product decisions

---

# 🛠️ Tech Stack

- Python (Pandas, NumPy)
- PostgreSQL
- Advanced SQL
- SQLAlchemy
- Power BI
- Data Cleaning & Feature Engineering
- Business Intelligence
- Revenue Modeling
- Customer Segmentation Analytics

---

# 📌 Core Competencies Demonstrated

- Data Analytics & EDA
- SQL Query Optimization
- Revenue Analysis
- Cohort & Segment Analysis
- KPI Development
- Subscription Growth Strategy
- Product-Oriented Analytics
- Stakeholder Reporting
- Dashboard Design
- Business Impact Communication

---

# 💼 Why This Project Aligns with Product-Based Companies

✔ Focus on revenue & growth metrics  
✔ Scalable data workflow  
✔ KPI-driven insights  
✔ Strong business interpretation  
✔ Product-level recommendations  
✔ Monetization strategy  
✔ Customer lifecycle thinking  

---
# 📊 Live Power BI Dashboard

🔗 **Interactive Dashboard Link:**  
👉 https://app.powerbi.com/view?r=eyJrIjoiZmQ0NGM2MDAtOTEwMy00NGFmLTkzYjktYzdiNzVmYmU3YzlhIiwidCI6IjY4ZjNjZDYxLTYxOTQtNDc1OC04ZGZlLTA4NGRjOWM3ZDJmYiJ9


## 📬 Contact

If you're looking for a Data Analyst who combines technical expertise with strong business acumen and product thinking, feel free to connect.

---
