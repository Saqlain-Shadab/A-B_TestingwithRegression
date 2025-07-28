### 📈 Advertisement Campaign through A/B Testing & Regression Analysis

**Problem Statement :**  
This project evaluates and optimizes digital advertising performance using **A/B testing** and **regression analysis**. It compares **Facebook** and **Google AdWords** in terms of clicks, conversions, and cost-efficiency, enabling data-driven decisions for strategic budget allocation.

---
**📂 Data Sources**  
The dataset includes daily performance metrics for both ad platforms from **January 1 to December 31, 2019**:  
- **Date** – Daily campaign records  
- **Ad Views** – Total impressions  
- **Ad Clicks** – Number of clicks  
- **Ad Conversions** – Successful conversions  
- **Cost per Ad** – Daily spend  
- **CTR (Click-Through Rate)** – Clicks ÷ Views  
- **Conversion Rate** – Conversions ÷ Clicks  
- **CPC (Cost per Click)** – Cost ÷ Clicks  
---
**🧹 Data Cleaning**  
- Standardized date formats  
- Converted numerical fields to proper data types  
- Handled missing values and removed duplicates  
- Ensured consistency across both platform data points
---
**🛠️ Data Modeling**  
Merged and structured datasets for comparative analysis:  
- Created **platform indicator columns**  
- Calculated CTR, CPC, and Conversion Rate for both platforms  
- Built additional KPIs and flags for modeling and visualization
---
**📊 Statistical & Predictive Analysis**  
- **A/B Testing**  
  - Used **t-tests** to compare Facebook vs. Google AdWords on CTR, CPC, and conversion rate  
- **Regression Modeling**  
  - Developed a **linear regression model** to predict conversions from clicks  
  - Evaluated model accuracy using **R²** and **MSE**  
- **Correlation & Cointegration**  
  - Explored long-term relationships between ad spend and conversions using **correlation** and **cointegration tests**
---
**📈 Data Visualization**  
Created visual dashboards using **Matplotlib** and **Seaborn**:  
- Line plots: Daily trends of CTR, CPC, and conversions  
- Scatter plots: Clicks vs. Conversions  
- Box plots: Platform-wise distribution of KPIs  
- Time-series: Seasonal patterns and performance variation
---
**📌 Key Insights**  
- **Platform Performance**  
  - **Facebook** showed **higher conversion rates** and **lower CPC** than Google AdWords  
- **Budget Optimization**  
  - Facebook proved more cost-effective, suggesting a shift in ad budget toward it  
- **Seasonal Behavior**  
  - Conversion rates peaked in Q2 and Q4, highlighting the importance of timing in campaign planning
---
**💻 Tools & Technologies Used**  
- **Python**: Core analysis and modeling  
- **Pandas & NumPy**: Data processing  
- **Matplotlib & Seaborn**: Visualization  
- **SciPy**: Statistical testing (t-test, cointegration)  
- **Scikit-learn**: Regression modeling
---
**📎 Outcome**  
This project delivers a **data-driven framework** for comparing ad platforms. It enables:  
- Informed **budget allocation decisions**  
- Better **ROI analysis** for marketing campaigns  
- Insights into **seasonal performance trends**  
Ideal for marketing teams and analysts looking to maximize advertising efficiency.
