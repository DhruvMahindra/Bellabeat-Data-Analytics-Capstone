# 📊 Bellabeat Smart Device Data Analysis (Google Data Analytics Capstone)

This project was completed as part of the **Google Data Analytics Certificate Capstone**.  
The goal was to analyze smart fitness device data and provide **marketing insights** and **strategic recommendations** for Bellabeat, a wellness brand targeting health-conscious women.

---

## 🧭 Project Overview

**Business Task:**  
Analyze smart device usage data to uncover user behavior trends and help Bellabeat's marketing team identify new growth opportunities.

**Company Context:**  
Bellabeat is a high-tech company that manufactures health-focused smart products for women. They aim to expand their presence in the global wellness and smart device market.

---

## 📌 Guiding Questions

1. **What are some trends in smart device usage?**  
2. **How could these trends apply to Bellabeat customers?**  
3. **How could these trends help influence Bellabeat’s marketing strategy?**

---

## 🧪 Process Breakdown (Based on the Data Analysis Process)

### 📥 Ask Phase
- The business task and core questions were provided in the capstone prompt.
- Goal: Use data to uncover user behavior patterns and guide marketing recommendations.

### 📦 Prepare Phase
- **Data Source:** FitBit Fitness Tracker Data (Public dataset on [Kaggle](https://www.kaggle.com/datasets/arashnic/fitbit))
- The dataset is legitimate and available under open use for educational purposes.
- Selected datasets that tracked daily activity, hourly steps, calories, sleep, and weight.

### 🧹 Process Phase
- Cleaned and transformed the data in Excel before importing it into SQL.
- **Issues handled:**
  - Converted date columns stored as text into proper date formats.
  - Removed duplicate or incomplete entries.

### 🧮 Analyze Phase
- Used SQL (Google BigQuery) to perform data aggregation and calculate metrics:
  - Average steps, calories, active minutes (light/fairly/very/sedentary)
  - Hourly patterns of activity and calories burned
  - Sleep analysis: average duration
  - BMI and weight summary from a subset of users

### 📊 Share Phase
- Visualized key insights using **Power BI**, creating a multi-page dashboard with the following views:
  1. Overview
  2. Activity Patterns
  3. Sleep & Weight
  4. Marketing Insights & Recommendations

- Created a **PowerPoint presentation** to summarize findings and strategy suggestions for Bellabeat stakeholders.

---

## 🔍 Key Findings

- Users are mostly **lightly active** or **sedentary**.
- Activity peaks during **morning (7–9 AM)** and **evening (6–8 PM)**.
- Many users sleep **less than 7 hours**, below recommended levels.
- Average **BMI of 25.73** suggests slight overweight classification, highlighting the need for general wellness over weight loss focus.

---

## 📢 Marketing Recommendations

- Target sedentary users with **movement nudges and micro-habit campaigns**.
- Promote **sleep and mindfulness features** (e.g., tracking, meditation).
- Send push notifications during **peak activity windows**.
- Position Bellabeat as a **holistic wellness companion**, not just a fitness tracker.
- Launch **30-day challenges** to improve user engagement (e.g., “Better Sleep Week”, “7K Step Challenge”).

---
📁 Files in This Repository
File / Folder	Description
Google data analytics capstone.pbix	Power BI dashboard containing all visual analysis
Bellabeat Data Analysis Capstone.pptx	Slide deck summarizing insights and marketing recommendations
BellaBeat Aggregated Data.xlsx	Aggregated and cleaned data in Excel format
Google Data analytics Capstone - dailyActivity_merged.csv	Raw/merged CSV data file used for analysis
Bellabeat aggregation SQL.pdf	PDF with SQL queries and aggregation steps used in data analysis

---

## 📌 Tools & Skills Used

- SQL (PostgreSQL)
- Power BI
- Excel
- Data Cleaning & Transformation
- Data Visualization
- Business Strategy Communication

---

## 🙌 Acknowledgments

- Dataset by Möbius on [Kaggle](https://www.kaggle.com/datasets/arashnic/fitbit)
- Project created as part of the **Google Data Analytics Professional Certificate**
