# E-commerce Customer Experience & Growth Strategy
## Executive Summary

This project analyzes customer experience across product categories in an e-commerce platform, with the goal of identifying strategic levers for sustainable growth.

By combining customer reviews, delivery performance, and sales volume into a unified **Customer Experience Index (CEI)**, we assessed not only how much each category sells, but how well it serves customers.

Key findings reveal that:
- The average customer review score is approximately **4.1**, indicating solid performance but clear room for improvement.
- Around **91% of orders are delivered on time**, highlighting operational strength but also exposing a non-negligible failure rate.
- High sales volume does not always correlate with high customer satisfaction, creating hidden risks for long-term growth.

Using a quadrant-based strategic framework, categories were segmented into:
- **Growth Engines** that drive revenue and customer satisfaction,
- **Hidden Opportunities** with strong experience but underutilized potential,
- **Critical Fixes** where high revenue is offset by poor customer experience,
- and **Re-evaluate** segments with limited strategic value.

The analysis indicates that the greatest growth potential lies in addressing **Hidden Opportunity** and **Critical Fix** categories. Improving customer experience in these areas can yield disproportionate gains in retention, brand perception, and long-term revenue.

Overall, this project demonstrates how customer experience metrics can be transformed into concrete, data-driven business strategies.

## Business Recommendations

Based on the Customer Experience Index and quadrant analysis, the following actions are recommended:

### 1. Immediate Actions (0–30 days)
**Focus: Critical Fix categories**

- Prioritize categories with high sales volume but low customer experience.
- Investigate root causes of poor performance, particularly delivery delays and negative reviews.
- Implement short-term operational fixes such as logistics optimization, clearer delivery communication, and customer support reinforcement.

**Expected impact:** Rapid improvement in customer perception with minimal impact on revenue flow.

---

### 2. Short-Term Growth Actions (30–90 days)
**Focus: Hidden Opportunity categories**

- Increase visibility of high-experience, low-volume categories through marketing campaigns and homepage placement.
- Leverage positive customer reviews as social proof.
- Test pricing, bundling, or promotional strategies to stimulate demand.

**Expected impact:** Revenue growth driven by already satisfied customers.

---

### 3. Long-Term Strategic Actions (90+ days)
**Focus: Growth Engines and Re-evaluate categories**

- Protect and scale Growth Engine categories by maintaining service quality and operational excellence.
- Continuously monitor CEI to detect early signs of degradation.
- Reassess or phase out Re-evaluate categories unless a clear turnaround strategy exists.

**Expected impact:** Sustainable growth and optimized resource allocation.

---

### 4. Measurement & Monitoring
- Track Customer Experience Index (CEI) at regular intervals.
- Establish alert thresholds for delivery performance and review scores.
- Integrate CEI into strategic dashboards used by leadership teams.

**Expected impact:** Proactive decision-making based on early signals, not lagging indicators.


## Business Problem

E-commerce growth is not limited by sales volume alone, but by customer experience consistency. Companies often fail to identify which parts of their business are silently eroding customer trust and which categories represent untapped growth opportunities.

## Key challenges addressed in this project:

- Measuring customer satisfaction in a structured, data-driven way
- Understanding the impact of delivery performance on customer perception
- Identifying product categories that require intervention versus those that should be scaled
- Designing a prioritization framework to guide investment and operational decisions

## Dataset

The project uses the Olist Brazilian E-commerce Dataset, which includes transactional, customer, product, delivery, and review-level data across multiple years.

## Dataset Source & Naming Convention

The original Olist datasets were renamed for clarity and readability while preserving their original structure and semantics.

| Original File	                  | Renamed File       |
|---------------------------------|--------------------|
| olist_customers_dataset.csv	  | customers.csv      |
| olist_orders_dataset.csv	      | orders.csv         |
| olist_order_items_dataset.csv	  | order_items.csv    |
| olist_geolocation_dataset.csv	  | geolocation.csv    |
| olist_order_reviews_dataset.csv | order_reviews.csv  |
| olist_payments_dataset.csv	  | payments.csv       |
| olist_products_dataset.csv	  | products.csv       |
| olist_sellers_dataset.csv	      | sellers.csv        |
|---------------------------------|--------------------|

## Methodology

### The project follows a structured analytical approach:

1 Data ingestion and validation
2 Exploratory analysis of customer satisfaction and delivery performance
3 Feature engineering:
- On-time delivery rate
- Average review score
- Order volume per category
4 Construction of a Customer Experience Index (CEI) using normalized metrics
5 Category segmentation into strategic quadrants
6 Business interpretation and growth-oriented recommendations

## Key Insights

The average customer review score is approximately 4.0, indicating solid but non-exceptional satisfaction

Around 9% of orders are delivered late, representing a significant friction point in the customer experience

Not all poorly rated categories are low-volume; some represent high-potential opportunities if operational issues are addressed

Delivery performance shows a strong relationship with customer perception and repeat behavior

## Strategic Segmentation

Product categories are classified into four strategic groups based on their Customer Experience Index and order volume:

- Growth Engine: High satisfaction, high volume — scale and protect
- Hidden Opportunities: High volume, poor experience — highest growth potential
- Critical fix: Low volume, average experience — monitor
- Re-evaluate: Low satisfaction, low volume — evaluate or redesign

This segmentation enables targeted, data-driven decision-making rather than blanket optimizations.

## Business Recommendations

- Prioritize Hidden Opportunity categories for operational and experience improvements
- Focus on delivery reliability as a key lever for improving customer perception
- Use CEI as a recurring monitoring metric rather than a one-off analysis
- Avoid eliminating underperforming categories prematurely; optimize before cutting
- Align logistics, product, and customer experience teams around shared metrics

## How to Run
1. Clone the repository
2. Install dependencies listed in `requirements.txt`
3. Run the notebook in `notebooks/data_ingestion.ipynb`

---

## Author
**Jason Urrutia**  
Data Scientist  
Customer Analytics & Business Strategy