# Customer Segmentation & Retention Strategy

An end-to-end customer analytics project using **RFM Analysis** and **Cohort Analysis** to understand customer behavior, identify high-value and at-risk segments, and generate actionable retention insights through an interactive **Streamlit dashboard**.

## 📌 Overview

Customer retention is critical for understanding long-term customer value and improving engagement. This project analyzes customer transaction and engagement data to segment customers based on their purchasing behavior and retention patterns.

The project combines:

- **RFM Analysis** to understand customer value and engagement
- **Cohort Analysis** to study customer retention over time
- **Customer Segmentation** to identify behavioral groups
- **Retention Analysis** to identify high-value and at-risk customers
- **Streamlit Dashboard** to visualize and communicate insights

The analysis covers **5,800+ customers** and focuses on identifying segments such as **Champions** and **At-Risk** customers.

---

## 🎯 Objectives

- Segment customers based on **Recency, Frequency, and Monetary Value**
- Analyze customer retention using **cohort analysis**
- Identify high-value customers and customers at risk of churn
- Understand customer engagement and monetization patterns
- Generate insights for targeted retention campaigns
- Build an interactive dashboard for business users

---

## 🛠️ Tech Stack

- **Python**
- **Pandas** – Data manipulation and analysis
- **Scikit-learn** – Customer segmentation and analytical workflows
- **Matplotlib** – Data visualization
- **Streamlit** – Interactive dashboard
- **Jupyter Notebook** – Exploratory data analysis

---

## 📊 Methodology

### 1. Data Preparation

The customer transaction data was cleaned and prepared for analysis by handling relevant data fields and transforming transaction-level information into customer-level metrics.

Key customer attributes were used to understand:

- Purchase activity
- Purchase frequency
- Monetary contribution
- Customer retention behavior

### 2. RFM Analysis

RFM analysis evaluates customers using three dimensions:

| Metric | Meaning |
|---|---|
| **Recency** | How recently a customer made a purchase |
| **Frequency** | How frequently a customer made purchases |
| **Monetary** | How much a customer contributed financially |

Customers were scored and segmented based on their RFM characteristics.

This helped identify behavioral segments such as:

- **Champions** – Highly engaged and valuable customers
- **At-Risk** – Previously valuable customers showing reduced engagement
- Other customer segments based on purchasing behavior

### 3. Cohort Analysis

Customers were grouped into cohorts based on their initial purchase period.

Cohort analysis was used to evaluate:

- Customer retention over time
- Changes in engagement across cohorts
- Retention patterns between customer groups
- Potential areas for retention improvement

### 4. Retention Insights

RFM and cohort results were combined to identify customer groups that could benefit from targeted retention strategies.

The analysis identified **Champion and At-Risk cohorts**, providing a basis for differentiated customer engagement campaigns.

The resulting strategy was projected to support approximately a **15% improvement in re-engagement rates**.

---

## 📈 Dashboard

An interactive **Streamlit dashboard** was developed to make the analysis accessible to business and cross-functional teams.

### Dashboard includes:

- Customer segmentation overview
- RFM segment distribution
- Cohort retention analysis
- Champion customer analysis
- At-Risk customer analysis
- Churn likelihood insights
- Campaign outcome tracking

The dashboard allows users to explore customer behavior and retention patterns interactively rather than relying only on static analysis.

---

## 💡 Key Insights

The analysis demonstrated how combining RFM and cohort analysis can provide a more comprehensive view of customer behavior.

### Key findings:

- Analyzed **5,800+ customers** based on engagement and monetary behavior.
- Identified **Champion customers** representing highly valuable and engaged segments.
- Identified **At-Risk customers** who could be targeted through retention campaigns.
- Cohort analysis provided visibility into customer retention patterns over time.
- Segmentation enabled differentiated strategies rather than applying the same retention approach to all customers.
- The resulting retention strategy projected a **15% improvement in re-engagement rates**.

---

## 🚀 Running the Project Locally

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/customer-segmentation-retention-rfm.git
cd customer-segmentation-retention-rfm
