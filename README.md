
# Product Search Analysis

### Repository: **product_search_analysis**

This repository contains the code, analysis, and insights for evaluating the performance of search queries and product data. The project focuses on understanding search trends, optimizing query performance, and improving the overall search experience on an e-commerce platform.

---

## Overview

This analysis evaluates various metrics such as Click-Through Rates (CTR), search volume (Hits), clicks, orders, and conversion funnels. It identifies high-performing products, analyzes query behavior, and provides actionable insights to enhance the search platform.

---

## Key Features

### 1. Best Performing Products
- **Top Products by Orders**:
  - Chevron Stripe Colorblock Maxi Dress
  - Cotton Knit Fit and Flare Dress
  - Bird Print Pleated Cotton Knit Dress
- **Top Queries by Orders**:
  - "maxi" (13 orders)
  - "green" (9 orders)
  - "chambray" (8 orders)

### 2. Query Performance Metrics
- Strong positive correlation between CTR and conversion rate (0.75).
- High CTR queries: "victorian dress" and "corset dress prom dress" (100% CTR).
- Disconnect observed between hits (volume) and late funnel metrics (carts, orders).

### 3. Product Categories
- Dominant category: **Dress** (428 products).
- Notable keywords: "cotton", "dress", "knit", "print", and "maxi."

### 4. Query Length Analysis
- Short to medium-length queries (under 30 characters) show the highest potential for generating orders.
- Queries with under 10 characters exhibit high variability in performance.

### 5. Query-Product Matching
- Multimodal distribution of query-product similarity scores.
- High similarity doesn't guarantee high orders, indicating external factors (e.g., price, reviews) influence decisions.

---

## Key Insights
1. Specific queries (e.g., "victorian dress") achieve high CTRs, while general terms (e.g., "maxi") drive more orders.
2. Strong correlation between clicks, carts, and orders for products.
3. High-performing products are a better predictor of conversion potential compared to query hits.
4. Optimization strategies for queries and products differ:
   - **Queries:** Improve CTR and optimize relevance.
   - **Products:** Enhance visibility and click-through rates.
5. Low-similarity products with high orders suggest alternative discovery mechanisms beyond direct query matching.

---

## Project Structure

```
product_search_analysis/
├── data/                   # Raw and processed datasets
├── notebooks/              # Jupyter Notebooks for data exploration and analysis
├── scripts/                # Python scripts for metric calculations and visualizations
├── reports/                # Generated reports and visualizations
├── README.md               # Project overview and details
└── LICENSE                 # License for the repository
```

---

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/product_search_analysis.git
   cd product_search_analysis
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Explore the notebooks for detailed analysis:
   ```bash
   jupyter notebook
   ```
4. Run scripts to analyze query and product performance:
   ```bash
   python scripts/query_analysis.py
   python scripts/product_analysis.py
   ```

---

## Future Work
- Explore additional metrics to refine query-product matching.
- Investigate external factors like product pricing, reviews, and seasonal trends.
- Develop models for predicting high-performing queries and products.


## Contributors
- Ankita Singh
```

You can copy this directly into your `README.md` file. Let me know if you'd like to make further adjustments!
