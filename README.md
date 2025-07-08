# 📈 Marketing Campaign Performance Analysis

This project analyzes marketing performance data across multiple campaigns and channels to assess ROI, customer engagement, and campaign effectiveness using Python. By applying descriptive, the analysis uncovers what’s working, what’s underperforming, and where the best opportunities lie to optimize marketing spend.

## 🧾 Project Description

This project evaluates the performance of a company’s marketing campaigns with a focus on **ROI**, **conversion rates**, **click-through rates**, **customer segments**, and **channel performance**.
The dataset contains marketing metrics for several campaigns, including:
* **Campaign Name**
* **Marketing Channel** (e.g., Email, Social Media, Google Ads)
* **Cost**
* **Revenue**
* **Impressions**
* **Clicks**
* **Conversions**
* **Customer Segment**
* **Date**

### 🧠 Primary Objectives:
This analysis aims to address the following key business questions:
1. **Which marketing channels deliver the highest ROI?**
2. **Which customer segments respond best to our campaigns?**
3. **What is the conversion performance by channel and segment?**
4. **How should we optimize marketing budget allocations?**

Each question is approached using appropriate statistical summaries, visual insights, and calculated KPIs.

## 🛠️ Tool Used: Python Libraries

* `pandas` – data wrangling and preparation
* `numpy` – numerical operations
* `matplotlib.pyplot` – static visualizations
* `seaborn` – statistical data visualizations

## 🧭 Process Overview
1. **Import Libraries & Load Data**
   * Dataset imported from XLSX source
   * Initial inspection using `.head()`, `.info()`, `.shape`

2. **Data Cleaning**
   * Checked for missing values
   * Formatted columns (e.g., dates, numerical types)
   * Standardized categorical values

3. **Feature Engineering**
   * ROI = (Revenue - Cost) / Cost
   * Conversion Rate = Conversions / Clicks
   * CTR = Clicks / Impressions

4. **Interpretation & Business Insights**

   * Maintain current marketing channels—they are all performing consistently.
   * Prioritise high-conversion campaign types in future efforts.
   * Further analyse top-performing cities and companies to identify key success factors.
   * Continue using multilingual strategies, as engagement remains strong across the board.
   
Check out the notebook here['https://github.com/Top-BenBen/Marketing-Campaign-Performance-Analysis/blob/main/Marketing.ipynb']

