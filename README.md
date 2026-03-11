# 🛒 D2C Marketing Funnel & Customer Churn Analysis

## 📄 Executive Summary
This project presents a comprehensive, data-driven analysis of a **Direct-to-Consumer (D2C) ecosystem**, utilizing a large-scale dataset of **120,000 user sessions** sourced from **Kaggle** over a 6-month period. The core objective was to diagnose a critical business paradox: why high-volume marketing traffic was failing to generate proportional revenue growth. 

Through the development of a multi-page interactive Power BI dashboard, I conducted a deep-stage funnel analysis that identified a staggering **65% drop-off rate** specifically occurring between the "Product View" and "Add to Cart" phases. This significant "leak" in the conversion pipeline represents the single greatest opportunity for revenue recovery. Beyond simple visualization, this project provides a strategic roadmap for stakeholders to optimize marketing spend across Direct, Organic, and Paid channels, while deploying targeted retention loops to mitigate churn in high-risk customer segments.

---

## 🎯 Business Problem: The Traffic-Conversion Gap
The primary challenge identified was **High Traffic Volume with Suboptimal Conversion Rates.** Despite consistent growth in user sessions, the conversion floor remained stagnant.
This project aimed to:
* **Pinpoint Funnel Friction:** Map every step of the 6-month journey to find exactly where 65% of potential revenue is lost.
* **Evaluate Channel Quality:** Differentiate between "high-volume/low-intent" traffic and "low-volume/high-value" acquisition sources.
* **Decode Churn Triggers:** Identify the behavioral patterns that cause customers to disengage after their first interaction.

---

## 📂 Dataset & Methodology
* **Data Source:** Kaggle (D2C Marketing Dataset).
* **Volume:** 120,000+ Session-level records.
* **Timeframe:** 6 Months of behavioral data.
* **Tech Stack:** * **Power BI:** Data modeling, advanced DAX, and narrative visualization.
    * **SQL:** Comprehensive data cleaning, feature engineering, and session categorization.
    * **Power Query:** ETL workflows and data normalization.

---

## 🔍 Dashboard Deep-Dive: Page-by-Page Insights

### 1. Executive Overview
![Executive Overview Dashboard](./Executive_Overview_Dashboard.png)

**Strategic Insights:**
* **Revenue Inconsistency:** Data highlights that traffic surges do not always correlate with revenue spikes, proving that acquisition volume is a secondary metric to conversion efficiency.
* **Real-time KPI Tracking:** Established a baseline for Sessions, Conversion Rate (CR), and Revenue that allows for immediate detection of performance anomalies.

**Business Recommendations:**
* **ROI-First Spending:** Shift the marketing focus from "Session Quantity" to "Conversion Quality" by tracking the lead-to-purchase ratio rather than just clicks.

---

### 2. Funnel Analysis (The 65% Bottleneck)
![Funnel Analysis Dashboard](./Funnel_dashboard_image.png)

**Strategic Insights:**
* **The 65% Conversion Leak:** The most critical finding is the **65% drop-off** at the "Product View to Add to Cart" stage. This indicates that while users are interested in the product, there is extreme friction in the consideration phase.
* **Path Analysis:** Once users successfully add an item to the cart, the conversion to purchase is significantly higher, meaning the "closing" stage is healthy, but the "intent" stage is broken.

**Business Recommendations:**
* **UX/UI Overhaul:** Implement dynamic product recommendations and clearer call-to-action (CTA) buttons to bridge the 65% gap.
* **Social Proof Integration:** Add real-time reviews or "low-stock" alerts on product pages to increase the urgency of the "Add to Cart" action.

---

### 3. Channel Performance Analysis
![Channel Performance Dashboard](./Channel_performance_image.png)

**Strategic Insights:**
* **Quality Disparity:** **Organic Search** and **Direct** channels show a 3x higher conversion rate than Paid Social, which brings in mass volume but very low intent.
* **Efficiency Lead:** Referral traffic provides the highest LTV (Lifetime Value) per acquisition, making it the most efficient channel in the mix.

**Business Recommendations:**
* **Channel Reallocation:** Reallocate 20% of the Paid Social budget to SEO and Referral-incentive programs to prioritize high-intent traffic over raw clicks.

---

### 4. Churn Analysis & Retention
![Churn Analysis Dashboard](./Churn_Analysis_Image.png)

**Strategic Insights:**
* **The 45-Day Churn Threshold:** Users who do not engage with the brand within **45 days** of their initial purchase have an 80% probability of permanent churn.
* **Promo Sensitivity:** Customers acquired through heavy discounting demonstrate the highest churn rates, indicating they are "price-sensitive" rather than "brand-loyal."

**Business Recommendations:**
* **Automated Retention Loop:** Trigger a personalized re-engagement campaign at the 30-day mark (15 days before the churn threshold) to secure a second purchase and increase LTV.

---

## 📊 Key Metrics & Methodology
* **Funnel Efficiency:** Measured via Stage-over-Stage conversion rates.
* **Customer Retention Rate:** Calculated using time-lapse analysis between sessions.
* **DAX Implementation:** Created complex measures for Rolling Revenue, Churn Probability, and Channel Attribution.

---

## 📬 Contact & Portfolio
* **Adesola Abiodun Taofeek**
* **LinkedIn:** [www.linkedin.com/in/abiodun-adesola-a75b53358/]
* **Email:** [abiodunadesola73@gmail.com]
