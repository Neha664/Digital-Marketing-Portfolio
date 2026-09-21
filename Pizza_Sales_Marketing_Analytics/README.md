# 🍕 Pizza Sales Marketing Analytics

### Turning transaction data into ordering behavior, product marketing and promotional insights

This project repurposes an existing pizza sales dataset into a **digital marketing case study**.

Instead of repeating a standard sales-analysis dashboard, the project translates **ordering patterns, product demand and basket behavior** into practical marketing opportunities such as campaign timing, product promotion, bundling and merchandising.

---

## 🎯 Business Question

**When should the business communicate, which products should it feature, and how can offers be structured to improve basket value and demand?**

---

## 📊 Dataset Snapshot

- **48,620** transaction rows
- **21,350** distinct orders
- **32** pizza products
- **49,574** pizzas sold
- Transaction data from **2015**
- No customer ID, campaign ID, marketing channel or discount fields

---

## 📈 Key Baseline Metrics

| Metric | Value |
|---|---:|
| Revenue | $817,860.05 |
| Orders | 21,350 |
| Pizzas Sold | 49,574 |
| Average Order Value | $38.31 |
| Average Pizzas / Order | 2.32 |

---

## 🔎 Marketing Insights

### Demand & Timing
- **Evening** has the highest order volume among the analyzed dayparts.
- **12 PM** is the strongest individual ordering hour, with **2,520 orders**.
- **Thursday** records the highest weekday order volume, with **1,275 orders**.

### Product Marketing
- **Classic** generates the highest category revenue at approximately **$220.1K**.
- The highest-volume products include **Classic Deluxe, Barbecue Chicken, Hawaiian, Pepperoni and Thai Chicken**.
- These products can be considered for hero-product creative, merchandising and bundle testing.

### Basket Opportunities
- Customers purchase an average of **2.32 pizzas per order**.
- This provides a basis for testing **bundles, add-ons and upselling strategies**.

### Size Mix
- **Large pizzas** represent the highest quantity share in the dataset.
- Size-level demand can be used to test bundle structures, upsell messaging and menu placement.

---

## 🎯 Marketing Focus

- Ordering-behavior signals
- Product marketing
- Daypart and weekday demand
- Behavioral order-value segmentation
- Promotional hypotheses
- Bundle and upsell opportunities
- Marketing measurement framework

---

## 📊 Dashboard

The dashboard combines sales behavior with marketing interpretation.

**Key areas:**

- Demand & Timing
- Category Revenue Mix
- Marketing Signals
- Product Performance
- Pizza Size Mix
- Campaign Planning Inputs

![Pizza Marketing Analytics Dashboard](reports/marketing_dashboard.png)

---

## 📓 Analysis Notebook

The complete analysis is available in:

[`pizza_sales_analysis.ipynb`](reports/pizza_sales_analysis.ipynb)

The notebook covers:

- Data quality checks
- Marketing KPI baseline
- Demand by daypart and hour
- Weekday demand
- Product performance
- Category and size analysis
- Behavioral order-value segmentation
- Promotional planning
- Marketing recommendations

---

## 💡 Marketing Strategy Files

Additional strategy work is organized into:

### Insights
- [`customer_behavior.md`](insights/customer_behavior.md)
- [`product_insights.md`](insights/product_insights.md)
- [`peak_demand_analysis.md`](insights/peak_demand_analysis.md)

### Strategy
- [`customer_segmentation.md`](strategy/customer_segmentation.md)
- [`promotional_strategy.md`](strategy/promotional_strategy.md)
- [`campaign_ideas.md`](strategy/campaign_ideas.md)

### Research
- [`marketing_opportunities.md`](research/marketing_opportunities.md)

---

## ⚠️ Important Limitation

The source dataset does not contain customer identifiers, marketing channels, campaign exposure, discounts or acquisition sources.

Therefore, this project **does not claim**:

- Individual customer retention
- Customer lifetime value
- Campaign ROI
- True customer acquisition cost
- Demographic segmentation
- Individual-level repeat-customer behavior

Segmentation and marketing recommendations are based on **transaction, order, product, timing and basket-level behavior**.

---

## 🧩 Portfolio Positioning

This project complements the portfolio's campaign analytics project:

**AI Marketing Campaign → Campaign performance and optimization**

**Pizza Sales Marketing Analytics → Ordering behavior, product marketing and promotional strategy**

Together, the projects demonstrate both **campaign-level analytics** and **customer/product-oriented marketing analysis**.

---

## 🛠️ Tools

**Python · Pandas · NumPy · Matplotlib · Jupyter Notebook**

---

## 📁 Project Structure

```text
Pizza_Sales_Marketing_Analytics/
│
├── insights/
│   ├── customer_behavior.md
│   ├── product_insights.md
│   └── peak_demand_analysis.md
│
├── reports/
│   ├── pizza_sales_analysis.ipynb
│   └── marketing_dashboard.png
│
├── research/
│   └── marketing_opportunities.md
│
├── source_data/
│   └── pizza_sales.csv
│
├── strategy/
│   ├── customer_segmentation.md
│   ├── promotional_strategy.md
│   └── campaign_ideas.md
│
└── README.md