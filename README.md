# 📊 Marketing Analytics Portfolio Project

Welcome to my **Marketing Analytics Portfolio Project**! This project tackles real-world challenges for **ShopEasy**, an online retailer struggling with declining customer engagement, low conversion rates, and customer feedback issues. Using **SQL**, **Python**, and **Power BI**, I transformed raw data into actionable insights, driving strategies to boost sales, engagement, and satisfaction. 🚀

Dive in to explore how I turned data into impact! 👇

---

## 🎯 Project Overview

ShopEasy faced critical business challenges:
- **Decreased Conversion Rates**: Sales dropped to 4.3% in May, despite a peak of 18.5% in January.
- **Reduced Customer Engagement**: Social media views declined post-August, with a 15.37% click-through rate.
- **Customer Feedback Gaps**: Reviews averaged 3.7, below the 4.0 target, with 275 positive and 82 negative sentiments.

**My Goal**: Analyze customer journey, engagement, and review data to uncover insights and recommend strategies to improve:
1. **Conversion Rates** by optimizing the sales funnel.
2. **Customer Engagement** through better content strategies.
3. **Feedback Scores** by addressing negative sentiments.

**Tools Used**:
- 🛢️ **SQL** for data cleaning and transformation
- 🐍 **Python** (pandas, nltk) for sentiment analysis
- 📈 **Power BI** for interactive dashboards and visualizations

---

## 📈 Key Achievements

- **Cleaned Data**: Removed 79 duplicates and standardized formats in SQL, ensuring accurate 18.5% conversion rate analysis.
- **Enriched Insights**: Performed sentiment analysis in Python, classifying 275 positive and 82 negative reviews to guide satisfaction improvements.
- **Visualized Trends**: Built a Power BI dashboard showcasing conversion lows (4.3% in May), engagement declines, and review distributions.
- **Drove Impact**: Recommended targeted promotions for high-converting products (e.g., Ski Boots), video content to boost engagement, and feedback loops to improve 3.7 rating toward 4.0.

---

## 🛠️ Project Workflow

### 1. **Data Cleaning with SQL**
- **Objective**: Prepare high-quality data from ShopEasy’s database.
- **Actions**:
  - Removed duplicates in the Customer Journey table using CTEs and ROW_NUMBER.
  - Standardized content types (e.g., “Social Media” vs. “social media”) with REPLACE and UPPER.
  - Filled null durations with averages via subqueries.
- **Files**: See `/sql` folder for queries (e.g., `clean_customer_journey.sql`).

### 2. **Sentiment Analysis with Python**
- **Objective**: Analyze customer reviews to uncover sentiments.
- **Actions**:
  - Used Python’s nltk library to compute sentiment scores (-1 to 1).
  - Classified reviews into 275 positive, 82 negative, and mixed categories.
  - Exported enriched data as CSV for Power BI.
- **Files**: Check `/python` folder for script (e.g., `sentiment_analysis.py`).

### 3. **Dashboard Creation with Power BI**
- **Objective**: Visualize insights for stakeholders.
- **Actions**:
  - Built a data model with fact (Customer Journey, Reviews) and dimension (Products, Customers) tables.
  - Created DAX measures for KPIs like Conversion Rate (18.5% in January).
  - Designed 4 interactive dashboard pages:
    - **Overview**: KPIs (18.5% conversion, 3.7 rating).
    - **Conversion Details**: Funnel chart for drop-offs (4.3% May low).
    - **Social Media**: Line chart for declining views post-August.
    - **Customer Reviews**: Scatter chart for 275 positive reviews.
- **Files**: View `/powerbi` folder for dashboard file or screenshots (e.g., `dashboard_screenshot.png`).

### 4. **Recommendations**
- **Conversions**: Promote high-performing products (e.g., Ski Boots at 150% conversion in January) with seasonal campaigns.
- **Engagement**: Shift to interactive videos to reverse declining views and boost 15.37% click-through rate.
- **Feedback**: Address pricing issues in 82 negative reviews to reach 4.0 rating target.

---

## 📊 Key Metrics
| **Metric**                  | **Value**                     | **Insight**                                      |
|-----------------------------|-------------------------------|-------------------------------------------------|
| **Highest Conversion Rate** | 18.5% (January)              | Driven by Ski Boots; suggests seasonal focus.   |
| **Lowest Conversion Rate**  | 4.3% (May)                   | Indicates need for targeted promotions.        |
| **Social Media Views**      | Declined post-August         | Calls for engaging content like videos.        |
| **Click-Through Rate**      | 15.37%                       | Engaged users interact effectively.            |
| **Customer Rating**         | 3.7 (below 4.0 target)       | Opportunity to improve via feedback loops.     |
| **Review Sentiments**       | 275 positive, 82 negative    | Mixed sentiments offer improvement potential.  |

---

