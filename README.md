# Comparative Agricultural Data Analysis: Ireland vs The Netherlands

## 📘 Academic Context

This project was developed as part of the **Master in Data Analytics** at **CCT College Dublin**, within the following modules:

- Programming for Data Analytics  
- Statistics for Data Analytics  
- Machine Learning for Data Analysis  
- Data Preparation & Visualisation

## 🌍 Project Overview

This analysis explores and compares agricultural land use trends in **Ireland** and **The Netherlands**, applying modern data analytics techniques. The work includes **data cleaning**, **EDA**, **descriptive and inferential statistics**, **machine learning forecasting models**, and a **sentiment analysis** based on public opinion related to agriculture in Ireland.

The project is structured following the **CRISP-DM methodology** to ensure a systematic and professional analytical process.

## 🎯 Objectives

- Compare land use, crop diversification, and farm trends between Ireland and the Netherlands.
- Apply statistical methods to validate patterns and test hypotheses.
- Use ML models (Random Forest and Linear Regression) to forecast land use trends.
- Perform sentiment analysis on social media (Reddit) using NLP tools.
- Provide evidence-based recommendations for the Irish agricultural sector.

## ⚙️ Technologies Used

- Python  
- Jupyter Notebook  
- Pandas, NumPy  
- Scikit-learn, Statsmodels  
- TextBlob & VADER (for sentiment analysis)  
- Matplotlib, Seaborn, Plotly  
- GridSearchCV for model optimization

## 📈 Methodology

- **EDA** to identify trends and outliers in land use data from both countries  
- **Data cleaning and transformation** including handling null values, outliers, and merging multi-source datasets  
- **Descriptive & inferential statistics**: t-tests, Mann-Whitney U, OLS regression, ANOVA, Kruskal-Wallis  
- **Machine Learning**:  
  - Random Forest Regressor  
  - Linear Regression with F-regression feature selection  
- **Sentiment Analysis**:
  - Reddit data collected via PRAW (API)  
  - TextBlob and VADER models used to classify sentiment regarding Irish agriculture

## 🔍 Key Insights

- Significant differences in land use change between Ireland and the Netherlands.
- Ireland’s farm numbers decreased, but average farm size increased.
- Linear Regression showed the best performance in predicting future land use.
- Grassland features were most influential in prediction models.
- Public sentiment on Reddit leaned slightly positive, though with limitations in classification accuracy.

## 🗂️ Data Sources

- Central Statistics Office Ireland (CSO.ie)  
- Statistics Netherlands (CBS.nl)  
- Reddit post: *“What do you think of the current state of the agricultural industry in Ireland?”*  
- GeoJSON and choropleth data from CartographyVectors.com  

## 📊 Project Results (R² Scores)

| Model                 | Ireland R² | Netherlands R² |
|----------------------|------------|----------------|
| Random Forest        | 0.979      | 0.905          |
| Linear Regression    | 0.999      | 0.940          |

## 💡 Recommendations

- Encourage diversification in crop types to mitigate land-use decline.
- Monitor high-impact areas (e.g., Cork in Ireland, P30/P25 in Netherlands).
- Leverage ML for agricultural planning and productivity forecasting.
- Engage more with farmers and the public through platforms like Reddit for sentiment tracking.

---

### 👨‍🎓 Author

**Nelson Josue Pineda Mendez**  
Master in Data Analytics – CCT College Dublin  
