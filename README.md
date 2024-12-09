# EDA
# COVID-19 Country-Wise Data Analysis

## **Project Purpose**
The goal of this project is to analyze country-wise COVID-19 data to uncover meaningful insights about the pandemic's impact globally. Using exploratory data analysis (EDA), we examine confirmed cases, deaths, recoveries, and other metrics, identifying patterns and disparities across regions and countries.

This project aims to:
- Provide an overview of the COVID-19 pandemic's global impact.
- Highlight significant trends and patterns using visualizations.
- Offer insights that can inform further research or decision-making.

---

## **Dataset Information**
The dataset used for this project contains COVID-19 statistics for 187 countries. Key features include:
- **Confirmed**: Total confirmed cases.
- **Deaths**: Total deaths reported.
- **Recovered**: Total recoveries.
- **Active**: Current active cases.
- **Deaths / 100 Cases**: Death percentage per 100 confirmed cases.
- **WHO Region**: Geographical classification by WHO regions.

### **Source**
The dataset is provided in the file `country_wise_latest.csv` or you can directly download from the url("https://www.kaggle.com/datasets/imdevskp/corona-virus-report").

### **Columns**
1. `Country/Region`: Name of the country or region.
2. `Confirmed`: Total confirmed cases.
3. `Deaths`: Total deaths.
4. `Recovered`: Total recovered cases.
5. `Active`: Total active cases.
6. `New cases`, `New deaths`, `New recovered`: Daily reported changes.
7. `Deaths / 100 Cases`, `Recovered / 100 Cases`, `Deaths / 100 Recovered`: Percentage metrics.
8. `WHO Region`: Regional classification by WHO.

---

## **Insights Derived**
### **1. Top 10 Countries by Confirmed Cases**
- Countries like **USA, India, Brazil**, and **Russia** have the highest confirmed cases.
- These nations show significant variation in active cases and recovery rates.

### **2. Distribution of Confirmed Cases by WHO Regions**
- **Americas** and **Europe** account for the largest share of cases.
- **Africa** and **Western Pacific** regions show lower case contributions, potentially due to underreporting or lower population densities.

### **3. Relationship Between Active Cases and Death Percentage**
- No strong correlation was observed between active cases and death rates.
- Some countries with moderate active cases have high death percentages, suggesting disparities in healthcare systems or demographics.

---

## **Project Structure**
1. **EDA.ipynb**: Jupyter Notebook containing all code and visualizations.
2. **country_wise_latest.csv**: Dataset used for analysis.
3. **README.md**: This file, explaining the project purpose and findings.

---

## **How to Use**
1. Clone this repository:
   ```bash
   git clone <repository_url>
