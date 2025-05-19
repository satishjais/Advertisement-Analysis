# 📊 Ad Exposure vs Consumer Engagement: A Data-Driven Study

**Welcome to the Night Owls team's project** focused on analyzing the **impact of advertisement exposure frequency** on consumer behavior. In the digital age, optimizing ad spend is critical. This project investigates how repeated ad impressions influence metrics like Click-Through Rate (CTR), Conversion Rate, and overall purchase likelihood.

## 🚀 Objectives

* Understand how ad frequency affects user engagement.
* Identify the optimal number of exposures before returns diminish.
* Analyze the effectiveness of different ad campaigns and channels.
* Provide recommendations for efficient ad spend and targeting strategies.

## 📂 Dataset Overview

The dataset includes records from multiple digital marketing campaigns with the following attributes:

* **Campaign Data**: Type (Awareness, Retention, Consideration, Conversion), Platform, Tool.
* **Ad Exposure Metrics**: Ad spend, campaign channel (PPC, Social Media, Email, SEO, Referral), Estimated ad exposures.
* **Engagement Metrics**: CTR, Conversion rate, Website visits, Social shares, Email opens/clicks.
* **User Info**: Age, Gender, Income, Customer ID.
* **Behavioral Data**: Loyalty points, previous purchases.

### ⚠️ Constraints & Creative Solutions

* **No direct exposure count** → Derived Estimated Ad Exposures.
* **No direct timeframe** → Created Short/Medium/Long-term exposure buckets.
* **No flag for first-time viewers** → Segmented using exposure percentiles.
* **Detecting Ad Fatigue** → Used regression trends on CTR and conversion over exposure.

## 🛠️ Approach

1. **Data Cleaning & Preprocessing**
2. **Feature Engineering**

   * Estimated Ad Exposures
   * Viewer Type (First-Time vs Repeated)
   * Exposure Duration (Short/Medium/Long)
3. **Exploratory Data Analysis (EDA)**
4. **Trend & Fatigue Analysis**
5. **Business Recommendations**

## 📌 Decision Variables

* Estimated Ad Exposures
* Exposure Duration
* CTR and Conversion Rate
* Campaign Type & Channel
* Ad Spend Range

## 📈 Key Results & Insights

* **Best Campaign Type**:

  * *Consideration* campaigns = highest conversion
  * *Retention* campaigns = highest CTR
* **Best Channel**:

  * *PPC* = highest CTR
  * *Social Media* = highest conversions
* **Optimal Ad Spend**:

  * \$1K–\$5K is the most efficient range
* **Ad Exposure Findings**:

  * 5–20 exposures in 1–2 weeks yield peak performance
  * > 100 exposures = ad fatigue and decline in CTR
* **Viewer Type**:

  * First-Time viewers outperform Repeated viewers

## ✅ Final Recommendations

* Target 5–20 exposures per user within 1–2 weeks.
* Avoid over-retargeting; prioritize first impressions.
* Focus budget within the \$1K–\$5K range for better ROI.
* Reconsider short 1–3 day campaigns—they tend to underperform.
* Limit ad frequency to prevent fatigue and inefficiency.

---
