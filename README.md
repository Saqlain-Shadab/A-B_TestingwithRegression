# 📈 Marketing Campaign Optimization through A/B Testing & Regression Analysis

**Project Overview**  
This project evaluates and optimizes digital advertising performance using **A/B testing and regression analysis**. It aims to identify whether **Facebook** or **Google AdWords** offers better results in terms of clicks, conversions, and cost-efficiency. These insights enable data-driven decisions for **strategic budget allocation**.

---

**📝 Background**  
As part of the strategic team at a marketing agency, our core objective was to **maximize return on investment (ROI)** for client ad campaigns. This project focused on identifying the more effective advertising platform based on **clicks, conversions, and cost-efficiency**.

---

**🎯 Objective**  

- Determine which platform—**Facebook** or **Google AdWords**—delivers:
  - Higher **conversions**
  - Better **click-through rates (CTR)**
  - Greater **cost-effectiveness**

---

**📊 Data Description**  
The analysis is based on **daily campaign performance data** collected throughout **2019**. Each row represents one day’s metrics for both platforms and includes the following features:

-  **Date**: Daily records from Jan 1 – Dec 31, 2019  
-  **Ad Views**: Total number of impressions  
-  **Ad Clicks**: Number of user clicks  
-  **Ad Conversions**: Successful conversions from clicks  
-  **Cost per Ad**: Daily expenditure per platform  
-  **Click-Through Rate (CTR)**: Clicks ÷ Impressions  
-  **Conversion Rate**: Conversions ÷ Clicks  
-  **Cost per Click (CPC)**: Cost ÷ Clicks  

➡️ The dataset contains **365 entries**—one for each day of the year.
---
**🔍 Methodology**  

1. **Data Cleaning**
   - Standardized date formats  
   - Handled missing or inconsistent data

2. **Exploratory Data Analysis (EDA)**
   - Visualized trends in clicks and conversions  
   - Identified seasonal and platform-specific patterns

3. **Statistical Analysis**
   - Conducted **t-tests** to compare performance metrics  
   - Analyzed correlations between clicks and conversions  
   - Used **cointegration tests** to assess long-term relationships between ad spend and conversions

4. **Predictive Modeling**
   - Built a **linear regression model** to predict conversions from clicks  
   - Evaluated using **R²** and **Mean Squared Error (MSE)**
---
**📈 Key Insights**  
- **Platform Performance**:  
  Facebook consistently outperformed Google AdWords with **higher conversion rates** and **lower CPC**

- **Budget Optimization**:  
  Results suggest that shifting more of the ad budget to Facebook could improve overall **campaign ROI**

- **Seasonal Trends**:  
  Conversion performance varied across the year, indicating that **campaign timing** should align with seasonal behavior
---

**💻 Technologies Used**  
- **Python**: For end-to-end data analysis and modeling  
- **Pandas & NumPy**: Data cleaning and numerical operations  
- **Matplotlib & Seaborn**: Visualizing distributions and trends  
- **SciPy**: Hypothesis testing and statistical analysis  
- **Scikit-learn**: Linear regression modeling and evaluation
