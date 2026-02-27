# FoodPanda Taiwan – Customer Behavior & Marketing Strategy Analysis

**Data Analysis | Marketing Insights | Python Visualization**  
**Group Project** 


---

## 📋 Project Overview

Comprehensive exploratory data analysis on **4.58 million FoodPanda orders** in Taiwan over **89 days**.  
The project uncovers **customer ordering patterns**, identifies high-performing cuisines/vendors, highlights data quality issues, and delivers **actionable marketing & operational strategies** for FoodPanda and partner restaurants.


---

## 🎯 Objectives

### Customer Behavior
- Food category preferences  
- Ordering time (day of week + hourly patterns)  
- When do customers order the most?  
- Impact of promotions & drink/combo sets  

### Food Supplier & Marketing Strategy
- Maintain & grow supplier base  
- Evaluate previous campaign performance  
- Recommend cuisine-specific promotions by day  
- Suggest peak-hour discounts  
- Identify best restaurant collaboration opportunities (high transaction-rate cuisines)

---

## 📊 Dataset

- **Source**: FoodPanda Taiwan (Order + Customer + Vendor tables)  
- **Time range**: 89 days  
- **Size**: 4,581,346 rows × 13 columns  
- **Key fields**: order time, geohash (location), cuisine type, food name, vendor_id, etc.

---

## 🔍 Key Findings

### 1. Order Time & Distribution
- **Weekends dominate**: Sunday (15.81%), Saturday (14.95%)
- **Peak hours**: Strong lunch peak at **11:00 AM** and dinner peak around **18:00**
- Top districts by orders: **中正區 (32.5k)** > 中山區 > 桃園區

### 2. Cuisine & Vendor Performance
- **台式 (Taiwanese)** leads in total orders and number of vendors
- Highest **orders per vendor**:
  - 健康餐 (Healthy) – **46.1**
  - 歐美 (Western) – **41.2**
  - 小吃 (Snacks) – **38.5**
- In **中正區**, Healthy meals and Korean cuisine significantly outperform national averages.

### 3. Popular Items (after keyword cleaning)
- Top 5: 鍋貼 (68k+), 甜不辣 (53k+), 青菜, 酸辣湯, 玉米湯

### 4. Combo & Promotion Insights
- Only **9.25%** of orders include drink sets
- Promotion/discount usage is extremely low (**0.2%**)
- Fast-food combo meals with drinks perform best → strong bundling potential

### 5. Retention Insight
- Many customers are **one-time users** → big opportunity for re-engagement campaigns

---

## 💡 Strategic Recommendations (Marketing & Operations)

1. **Retention Campaigns**  
   - EDM + personalized discount messages for one-time users  
   - Geo-based food recommendation engine

2. **App Display Optimization (A/B Testing)**  
   - Improve ranking on restaurant preview page  
   - Smart item recommendations on order page (especially drink sets)

3. **Promotion Strategy**  
   - Heavy push on drink/combo sets across fast-food partners  
   - Targeted discounts during 11 AM & 18:00 peaks  
   - Weekend promotions for Taiwanese & Snack cuisines

4. **Restaurant Collaboration**  
   - Prioritize partnerships with **Healthy**, **Western**, and **Snack** categories  
   - District-specific campaigns (e.g. promote Korean in 中正區)

---

## 🛠️ Tech Stack & Methodology

- **Python** – Pandas (data cleaning & aggregation)  
- **Visualization** – Matplotlib / Seaborn (bar charts, line plots, heatmaps)  
- **Data Cleaning** – Keyword extraction for messy food names, handling nulls (chain_id), removing non-food entries  
- **Analysis** – GroupBy, pivot tables, order-per-vendor metrics

---

## 📁 Repository Structure

---
FoodPanda-Taiwan-Analysis/
├── FoodPanda project.pdf          # Full 60-slide presentation
├── notebooks/                     # Jupyter notebooks (analysis code)
## 🚀 How to Explore

1. Open **`FoodPanda project.pdf`** for the full visual presentation  
2. Run the Jupyter notebooks in `/notebooks` to reproduce all charts and insights  
3. Check the final slides (46–60) for **Summaries & Strategic Planning**

---

## 🔗 Connect & Portfolio

This project is part of my **Data Analyst Portfolio**.  
→ [Alex Wong Portfolio Website](https://alexwonghh.github.io/)  
→ [LinkedIn](https://www.linkedin.com/in/alex-wong-059304230)  
→ [GitHub](https://github.com/AlexWonghh)

**Open to entry-level Data Analyst / Business Intelligence roles** (Hong Kong & remote).  
Feel free to reach out if you’d like to discuss the project, data, or potential collaboration!

---

**Last Updated**: February 2026  
**Made with ❤️ in Hong Kong** | Taiwan-focused analysis

---

**Would you like me to also create:**
- A shorter 1-page project summary (for LinkedIn/GitHub profile)
- Jupyter notebook header / title slide version
- Or add actual chart images to the README?

Just say the word and I’ll generate it instantly! 🚀
