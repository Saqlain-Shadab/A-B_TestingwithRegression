## Advertisement Campaign through A/B Testing & Regression Analysis

### Overview  
This project analyzes digital advertising performance using **A/B testing** and **regression modeling**. It compares **Facebook** and **Google AdWords** to determine which platform offers better performance in terms of **clicks, conversions**, and **cost-efficiency**. The goal is to enable **data-driven budget allocation** to maximize return on investment (ROI).

### Background  
As part of a marketing agency’s analytics team, our objective was to evaluate the effectiveness of ad platforms based on key performance indicators (KPIs). This allowed stakeholders to identify the most cost-effective platform for future campaigns.

### Objective  
- Determine which advertising platform performs better across:
  - **Conversion Rate**
  - **Click-Through Rate (CTR)**
  - **Cost per Click (CPC)**  
- Recommend budget allocation strategies based on platform performance

### Data Description  
The dataset contains **daily ad performance data** for both platforms from **January 1 to December 31, 2019** (365 entries). Each row includes:

- `Date`: Daily timestamp  
- `Ad Views`: Number of impressions  
- `Ad Clicks`: Number of user clicks  
- `Ad Conversions`: Successful conversions  
- `Cost per Ad`: Daily spend per platform  
- `CTR (Click-Through Rate)`: Clicks ÷ Views  
- `Conversion Rate`: Conversions ÷ Clicks  
- `CPC (Cost per Click)`: Cost ÷ Clicks

### Methodology  

#### 1. Data Cleaning  
- Formatted date fields  
- Handled missing and inconsistent entries  

#### 2. Exploratory Data Analysis (EDA)  
- Visualized daily trends in views, clicks, and conversions  
- Compared distributions across platforms  
- Identified seasonal or platform-specific performance patterns  

#### 3. Statistical Testing  
- Conducted **t-tests** to compare Facebook vs. Google AdWords performance  
- Measured **correlation** between ad clicks and conversions  
- Performed **cointegration testing** to analyze long-term spending-conversion relationships  

#### 4. Predictive Modeling  
- Built a **linear regression model** to predict conversions from clicks  
- Evaluated model using **R² score** and **Mean Squared Error (MSE)**  

### Key Insights  
- **Facebook outperformed** Google AdWords in:
  - **Conversion Rate**
  - **Cost per Click**
- **Budget Recommendation**:
  - Redirecting more ad spend to Facebook may lead to **higher ROI**
- **Seasonal Effects**:
  - Conversion performance fluctuated throughout the year, suggesting campaign timing is important

### Resources Used  
- **Python**: Data processing and modeling  
- **Pandas, NumPy**: Data manipulation  
- **Matplotlib, Seaborn**: Visualization  
- **SciPy**: Hypothesis testing  
- **Scikit-learn**: Regression modeling  

### Conclusion  
This project demonstrates how A/B testing and regression analysis can be applied to real-world advertising data. The insights generated support smarter budget allocation and help improve overall campaign efficiency.
