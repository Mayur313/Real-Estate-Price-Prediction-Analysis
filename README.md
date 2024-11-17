# **Real Estate Price Prediction Analysis**

## **Project Overview**  
This project aims to analyze historical real estate pricing data to predict future price trends based on factors such as location, square footage, and market conditions. Using data scraping, cleaning, and visualization techniques, the goal is to uncover actionable insights that guide investment decisions and understand market behavior.  

---

## **Table of Contents**  
1. [Introduction](#introduction)  
2. [Tech Stack](#tech-stack)  
3. [Data Sources](#data-sources)  
4. [Project Workflow](#project-workflow)  
5. [Insights & Findings](#insights--findings)  
6. [How to Run the Project](#how-to-run-the-project)  
7. [Contact](#contact)  

---

## **Introduction**  
Real estate prices are influenced by multiple factors, including location, property size, and economic conditions. This project leverages data science techniques to analyze these variables, revealing trends and providing predictive models for future price forecasting.  

---

## **Tech Stack**  
- **Programming Languages**: Python  
- **Libraries/Tools**:  
  - Data Scraping: `BeautifulSoup`, `Selenium`  
  - Data Cleaning & Analysis: `Pandas`, `NumPy`  
  - Data Visualization: `Matplotlib`, `Seaborn`, `Power BI`  
  - Machine Learning: `Scikit-learn`, `XGBoost`  

---

## **Data Sources**  
The data is sourced through web scraping from real estate platforms like:  
1. [99acres.com](https://www.99acres.com)  
2. [Zillow](https://www.zillow.com)  
3. [Realtor](https://www.realtor.com)  

Collected features include:  
- **Property Details**: Location, size (sq. ft), price, type (apartment/house).  
- **Amenities**: Parking, pool, home office, etc.  
- **Market Conditions**: Seasonal trends, interest rates.  

---

## **Project Workflow**  

### **1. Data Collection**  
- Scraped data using tools like `BeautifulSoup` and `Selenium`.  
- Extracted relevant features: price, location, square footage, amenities.  

### **2. Data Cleaning**  
- Handled missing values using median/mean imputation.  
- Removed outliers with IQR (Interquartile Range) or z-scores.  
- Normalized numerical features to ensure consistent scaling.  

### **3. Data Visualization**  
- **Python**: Used `Matplotlib` and `Seaborn` for scatter plots and bar charts to explore feature correlations.  
- **Power BI**: Created an interactive dashboard to visualize:  
  - Price trends across regions and property types.  
  - Comparative analysis based on amenities and seasonal trends.  

### **4. Predictive Modeling**  
- Applied machine learning models like **Linear Regression** and **Random Forest** to predict property prices.  
- Evaluated model performance using metrics like RMSE and R-squared.  

---

## **Insights & Findings**  

1. **Location Premium**: Properties in downtown areas are 20-30% costlier than suburban properties.  
2. **Property Size**: Larger properties (>3000 sq. ft) have a premium of 15-25%.  
3. **Seasonal Trends**:  
   - Prices tend to increase during **spring** and **summer**.  
   - Winter months often see a slight drop in prices.  
4. **Market Trends**:  
   - Cities like **San Francisco** and **New York** are experiencing consistent price growth due to gentrification.  
5. **Impact of Amenities**:  
   - Properties with pools, home offices, or parking spaces can command up to 10% higher prices.  
6. **Economic Factors**: Rising interest rates reduce market activity, negatively affecting home affordability.  

---
