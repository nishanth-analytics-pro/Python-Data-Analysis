# 🎬 Netflix Content Strategy Analysis | Python EDA

## 📌 Project Overview
This project involves a deep-dive Exploratory Data Analysis (EDA) of the Netflix dataset (~7,000+ records) to uncover global streaming trends. By analyzing content distribution across genres, countries, and time, this study provides a data-driven perspective on how Netflix's library has evolved over the years.

---

## 🎯 Objectives
*   **Data Integrity**: Performed rigorous cleaning, including null value removal and duplicate checks across 7,000+ records.
*   **Time-Series Analysis**: Converted raw data into datetime formats to track year-over-year content growth.
*   **Global Mapping**: Identified the top 10 content-producing nations to understand regional dominance.
*   **Genre Intelligence**: Deconstructed the `listed_in` column to map distribution across various categories.

---

## 🧼 Data Engineering & Cleaning
Before analysis, the raw Kaggle dataset underwent a professional cleaning pipeline:
1.  **Null Management**: Removed records with missing critical values to maintain statistical accuracy.
2.  **Feature Extraction**: Derived `year_added` from the `date_added` column to enable time-based trend analysis.
3.  **Deduplication**: Verified the dataset for unique entries to prevent skewed results.

---

## 🔍 Exploratory Data Analysis (EDA) Highlights
*   📈 **Growth Trends**: Analysis of the number of shows added annually to identify peak expansion years.
*   🌍 **Top 10 Countries**: Visualized the primary markets contributing to Netflix’s global library.
*   🎞️ **Content Mix**: Evaluated the ratio between Movies and TV Shows to understand platform priorities.
*   🎭 **Genre Insights**: Identified the most popular tags and genre clusters using advanced Pandas grouping.

---

## 📊 Tools & Libraries Used
- **Python 3**: Core programming language.
- **Pandas**: Advanced data cleaning and transformation.
- **Matplotlib & Seaborn**: High-fidelity data visualizations and plots.
- **Google Colab**: Cloud-based interactive development environment.

---

## 🗂️ Folder Contents
*   📄 **`Netflix_EDA_Analysis.ipynb`**: Full Jupyter Notebook containing the cleaning pipeline and visualization code.
*   📂 **`screenshots/`**: Visual charts showing year-wise trends and genre distributions.
## 📁 Dataset Information
Source: Kaggle – Netflix Movies and TV Shows
Size: ~7,000+ records
Columns: Title, Director, Cast, Country, Date Added, Genre, etc.
Format: CSV
  

---

## ✅ Conclusion
Through this analysis, I have demonstrated the ability to take a large, raw dataset and transform it into a series of actionable visual insights. This project showcases my proficiency in **Pandas** for complex data manipulation and my analytical mindset in interpreting digital media trends.

---
**Author**: Nishanth M | Elite NPTEL Gold Medalist (Python for Data Science).
