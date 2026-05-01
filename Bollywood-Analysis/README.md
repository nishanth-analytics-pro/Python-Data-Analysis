# 🎥 Bollywood Box Office ROI Analysis | Python EDA

## 📌 Project Overview
This project performs an in-depth Exploratory Data Analysis (EDA) on a dataset of Bollywood movies released between 2013 and 2015. The primary goal was to uncover meaningful insights into movie profitability, moving beyond raw box office collections to analyze **Return on Investment (ROI)** and the impact of digital engagement.

---

## 🎯 Objectives
*   **Profitability Engineering**: Built a custom ROI metric to identify high-performing films relative to their budget.
*   **Release Timing Analysis**: Evaluated how different release periods (Festive vs. Normal) affect financial success.
*   **Correlation Mapping**: Quantified the relationship between social media engagement (YouTube trailer likes) and box office revenue.
*   **Market Profiling**: Analyzed budget distributions and genre dominance across 149 films.

---

## 🛠️ Technical Workflow & Analysis

### 1. Data Cleaning & Wrangling (Pandas)
Standardized the `bollywood.csv` dataset, handling inconsistent data and categorizing genres such as Drama, Comedy, and Action.

### 2. ROI Metric Calculation
Instead of just revenue, I calculated the efficiency of each film using:
`ROI = ((Box Office Collection - Budget) / Budget) * 100`.

### 3. Digital Engagement Impact
The analysis discovered a **moderately strong positive correlation (+0.68)** between YouTube trailer likes and box office success, confirming that online hype is a significant predictor of commercial performance.

---

## 💡 Key Business Insights
*   **Top Profitability**: 'Aashiqui 2' emerged as a standout performer with an exceptional **ROI exceeding 650%**, proving that modest budgets can yield massive returns.
*   **Strategic Timing**: Movies released during **Festive Seasons** showed the highest average ROI (95%), nearly doubling the returns of films released during normal periods (45%).
*   **Genre Dominance**: **Drama** was the most frequent genre (35 movies), followed by Comedy and Action.
*   **Budget Trends**: A strong right-skewed distribution showed that most films are produced under **₹40 Crores**, while high-budget films (over ₹100 Crores) remain outliers.

---

## 🗂️ Folder Contents
*   📄 **`bollywood.csv`**: Raw dataset containing 149 movie records.
*   📄 **`bollywood_movie_analysis_.ipynb`**: Full Jupyter Notebook containing the Python code, Pandas manipulation, and Seaborn/Matplotlib visualizations.

---

## ✅ Conclusion
This project demonstrates my ability to turn entertainment data into strategic financial insights. By identifying that digital engagement (+0.68 correlation) and release timing (95% ROI in Festive seasons) are critical success factors, this analysis provides a data-driven roadmap for movie profitability.

---
**Author**: Nishanth M | Elite NPTEL Gold Medalist (Python for Data Science).
