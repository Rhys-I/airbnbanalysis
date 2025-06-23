# 🏙️ NYC Airbnb Data Analysis

This project explores short-term rental listings in New York City using data-driven techniques to uncover pricing trends, host behaviors, and neighborhood-level insights. The goal is to identify patterns that can help hosts and investors optimize their listings for profitability and competitiveness.

---

## 📁 Folder Structure

/data             # CSVs or cleaned data  
/notebooks        # Jupyter notebooks used for analysis  
/visuals          # Images exported from Python or Tableau  
README.md         # This file  

---

## 🔍 Project Summary

Using the NYC Airbnb Open Data set, I conducted:

- Exploratory Data Analysis (EDA) to profile listings by borough, room type, and host status  
- Regression analysis to explore the relationship between accommodates and revenue  
- K-Means clustering to segment listings by pricing and location features  
- Visual storytelling in Tableau to present findings interactively  

---

## 📊 Key Findings

- 💰 **Superhosts earn more**: Superhost listings tend to charge higher prices and have higher occupancy.  
- 🗺️ **Location drives pricing**: Manhattan and Brooklyn listings command premium rates compared to Queens or the Bronx.  
- 🛏️ **Accommodates ≠ Revenue**: More guests doesn’t always mean more revenue — diminishing returns kick in for larger properties.  
- 📌 **Clusters revealed segments**: K-means clustering highlighted 3 main listing types: budget private rooms, mid-range entire homes, and high-end properties.

---

## ✅ Next Steps

- Include seasonal or time-based price trends  
- Integrate sentiment analysis from review texts  
- Compare NYC listings to other major cities for benchmarking  

---

## 🧠 Takeaways

This project demonstrates how exploratory data analysis and clustering can uncover real business insights from messy real-world data. By combining statistical modeling with clear visual storytelling, we can provide actionable recommendations for hosts, property managers, and investors in competitive rental markets.

---

## 📎 Tools Used

- **Python Libraries**:  
  - `pandas` – data manipulation  
  - `numpy` – numerical operations  
  - `matplotlib`, `seaborn` – visualizations  
  - `scikit-learn` – regression and clustering (K-Means)  
  - `statsmodels` – statistical modeling and regression diagnostics  
  - `folium` – interactive geographic mapping  
  - `plotly` – advanced visualizations  

- **Jupyter Notebook** – Analysis workflow  
- **Tableau** – Final dashboard visualizations  
- **Git** – Version control  
