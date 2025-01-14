# Marketing-Campaign-Analysis

## Project Overview
This project analyzes marketing campaign data to optimize advertising strategies, predict campaign performance, and recommend data-driven improvements. The dataset covers various digital advertising platforms (Google Ads, Facebook Ads, DV360) and includes details like impressions, clicks, media costs, and more.

The final deliverables include:
- Predictive models (Linear Regression, Ridge, Random Forest, etc.)
- Campaign optimization insights using Thompson Sampling.
- Data visualizations for trends and key metrics.

---

## Business Problems
1. **Which platforms and channels generate the highest engagement for the least cost?**
2. **Can we predict high-conversion campaigns based on budget and performance?**
3. **How can advertisers optimize their budget to maximize impressions, clicks, and reach while minimizing costs?**

---

## Technologies Used
- **Python**: Data processing, modeling, and visualization
- **Libraries**: 
  - `pandas`, `numpy` for data manipulation
  - `matplotlib`, `seaborn` for visualizations
  - `scikit-learn` for machine learning
  - `scipy` for statistical analysis
- **Jupyter Notebook**: Development and analysis environment

---

## Dataset
- **Source**: [Kaggle Marketing Campaign Dataset](https://www.kaggle.com/datasets/rahulchavan99/marketing-campaign-dataset)
- **Size**: 72,000 rows, 35 columns
- **Key Fields**:
  - `Campaign Duration`: Duration of the campaign (days)
  - `Media Cost USD`: Total spending in USD
  - `Clicks`, `Impressions`: Engagement metrics

---

## Methodology
1. **Data Preparation**:
   - Renamed columns for clarity
   - Dropped irrelevant features
   - Handled missing values

2. **Exploratory Data Analysis (EDA)**:
   - Analyzed impressions vs. clicks trends
   - Identified high-performing platforms and channels
   - Explored keyword performance in Facebook Ads

3. **Machine Learning Models**:
   - Regression models (Linear, Ridge, Random Forest, Gradient Boosting)
   - Logistic Regression for conversion prediction
   - Thompson Sampling for dynamic budget allocation

4. **Performance Evaluation**:
   - Metrics: R², RMSE, Accuracy, Precision, Recall, F1 Score

---

## Key Results
1. **Platform Analysis**:
   - DV360 provides the highest CTR across multiple channels.
   - Facebook Ads excel in mobile campaigns.

2. **Model Performance**:
   - **Gradient Boosting** achieved the best predictions with an R² of 59.8%.
   - **Logistic Regression** classified high-conversion campaigns with 96.66% accuracy.

3. **Optimization Insights**:
   - Thompson Sampling dynamically allocates budgets to maximize CTR.
