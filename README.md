# Eniac's Discount Strategy: Revenue & Margin Optimization

## 📌 Project Overview
The goal of this project was to analyze Eniac's historical sales data (2017-2018) to evaluate the effectiveness of their permanent discount model. By analyzing over 46,000 orders, I identified the "sweet spot" for discount depth that maximizes revenue without unnecessarily eroding profit margins.

---

## 📊 Business Insights & Visual Analysis

### 1. The State of Discounts
Analysis shows that discounts have become the default state rather than a tactical tool. **93% of all order lines** were sold at a discount, signaling permanent markdowns which can dilute brand value.

<img src="images/discount_percentage_pie.png" width="600" alt="Discount Coverage">

### 2. Finding the "Sweet Spot"
Revenue peaks at a moderate discount depth of **20-25%**. Deeper cuts (exceeding 30%) fail to deliver incremental gains and significantly damage the net margin. This is the "Optimal Revenue Zone" for the business.

<img src="images/revenue_sweet_spot.png" width="600" alt="Optimal Revenue Zone">

### 3. Seasonality vs. Discount Depth
Sales spikes are primarily driven by **calendar events** (like Black Friday and Q4) rather than the size of the discount itself. Outside of these peak periods, the correlation between discount size and day-to-day revenue remains low.

<img src="images/seasonality_spikes.png" width="600" alt="Seasonality Analysis">

---

## 🛠️ Tech Stack
* **Language:** Python (Pandas, NumPy)
* **Visualization:** Matplotlib, Seaborn
* **Analysis:** Exploratory Data Analysis (EDA), Correlation Analysis, Scenario Modeling
* **Domain:** E-commerce, Pricing Strategy

## 📂 Project Structure
* `discount_analysis.ipynb` — Full Python pipeline including data cleaning (ETL), statistical analysis, and visualization.
* `Discount_Strategy_Presentation.pdf` — Executive summary with visual data storytelling and strategic recommendations.

## 💡 Final Recommendations
1. **Shift to Event-Driven Strategy:** Concentrate the discount budget on high-seasonality periods where price elasticity is highest.
2. **Optimize Discount Depth:** Focus on the **20-25% range** to protect profit margins while maintaining peak revenue.
3. **Tiered Product Approach:** Maintain premium anchors with minimal discounts, while using Accessories as traffic magnets.
