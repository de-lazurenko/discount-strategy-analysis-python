# Eniac's Discount Strategy: Revenue & Margin Optimization

## 📌 Project Overview
The goal of this project was to analyze Eniac's historical sales data (2017-2018) to evaluate the effectiveness of their permanent discount model. By analyzing over 46,000 orders, I identified the "sweet spot" for discount depth that maximizes revenue without unnecessarily eroding profit margins.

---

## 📊 Business Insights & Visual Analysis

### 1. The State of Discounts
Analysis shows that discounts have become the default state rather than a tactical tool. **93.1% of all items** were sold at a discount, signaling permanent markdowns which can dilute brand value over time.

### 2. Finding the "Sweet Spot"
Through scenario modeling, I found that revenue peaks at a moderate discount depth of **20-25%**. Deeper cuts (exceeding 30%) fail to deliver incremental volume gains and significantly damage the net margin.

<p align="left">
  <img src="image/sweet_spot.png" width="600" alt="Optimal Revenue Zone">
</p>

### 3. Seasonality vs. Discount Depth
Sales spikes are primarily driven by **calendar events** (like Black Friday and Q4) rather than the size of the discount itself. Outside of these peak periods, the correlation between discount size and day-to-day revenue remains low.

<table border="0">
  <tr>
    <td width="54%" valign="middle">
      <img src="image/revenue_seasonality.png" width="100%" alt="Revenue Seasonality">
      <p align="center"><em>Revenue Seasonality</em></p>
    </td>
    <td width="2%"></td> 
    <td width="44%" valign="middle">
      <img src="image/discount_seasonality.png" width="100%" alt="Discount Seasonality">
      <p align="center"><em>Discount Seasonality</em></p>
    </td>
  </tr>
</table>

---

## 🛠️ Tech Stack
* **Language:** Python (Pandas, NumPy)
* **Visualization:** Matplotlib, Seaborn
* **Analysis:** Exploratory Data Analysis (EDA), Correlation Analysis, Scenario Modeling
* **Domain:** E-commerce, Pricing Strategy

## 📂 Project Structure
* `discount_analysis.ipynb` — Full Python pipeline including data cleaning (ETL), statistical analysis, and visualization.
* `Eniac_Discount_Strategy.pdf` — Executive summary with visual data storytelling and strategic recommendations.

## 💡 Final Recommendations
1. Concentrate the discount budget on high-seasonality periods where price elasticity is highest.
2. Focus on the **20-25% range** to protect profit margins while maintaining peak revenue.
3. Maintain premium anchors with minimal discounts, while using accessories as traffic magnets.
