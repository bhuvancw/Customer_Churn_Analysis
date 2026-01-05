# Customer Churn Analysis

## Project Overview

This project analyzes customer churn patterns for a telecommunications company using machine learning techniques. The analysis identifies key factors contributing to customer attrition and predicts which customers are at risk of leaving, enabling proactive retention strategies.

## Objectives

- **Understand Churn Patterns**: Analyze historical customer data to identify trends and characteristics of churned customers
- **Identify Risk Factors**: Determine which features have the highest impact on customer churn
- **Build Predictive Models**: Develop machine learning models to predict customer churn with high accuracy
- **Actionable Insights**: Provide business recommendations for reducing churn rates

## Dataset Description

The dataset contains customer information with the following characteristics:

- **Total Records**: Multiple customer profiles with service usage and demographic data
- **Features**: Customer tenure, contract type, monthly charges, total charges, internet service type, and additional services
- **Target Variable**: Churn (Yes/No) - whether the customer has left the company
- **Data Format**: CSV file with comprehensive customer attributes

## Technologies Used

- **Python**: Primary programming language for data analysis and modeling
- **Jupyter Notebook**: Interactive development environment (TCA.ipynb)
- **Libraries**:
  - Pandas: Data manipulation and exploration
  - NumPy: Numerical computations
  - Scikit-learn: Machine learning algorithms
  - Matplotlib/Seaborn: Data visualization
- **SQL**: Data querying and exploration
- **Machine Learning**: Classification algorithms for churn prediction

## Analysis Components

### 1. Exploratory Data Analysis (EDA)
- Distribution of customer demographics
- Churn rate analysis across different segments
- Correlation analysis between features and churn
- Service usage patterns

### 2. Data Preprocessing
- Handling missing values
- Feature encoding (categorical to numerical)
- Feature scaling for model compatibility
- Train-test data split

### 3. Predictive Modeling
- Logistic Regression
- Decision Trees
- Random Forest
- Gradient Boosting (if applicable)
- Model evaluation using accuracy, precision, recall, and F1-score

### 4. Key Insights
- Identification of high-risk customer segments
- Impact of contract type on churn
- Relationship between tenure and customer retention
- Service type influence on churn probability

## Files in Repository

- **Customer_Churn.csv**: Raw customer dataset with all features and churn labels
- **TCA.ipynb**: Jupyter notebook containing complete analysis, visualizations, and model building
- **Teco Customer Churn Analysys.pdf**: Comprehensive analysis report with findings and recommendations
- **README.md**: Project documentation (this file)

## Key Findings

- Month-to-month contracts show significantly higher churn rates
- Customers with longer tenure are less likely to churn
- Specific service combinations correlate with higher retention
- Early intervention for at-risk customers can improve retention

## How to Use

1. **Open the Jupyter Notebook**: Run `TCA.ipynb` to view the complete analysis
2. **Review the Dataset**: Load `Customer_Churn.csv` for raw data exploration
3. **Check the Report**: Read `Teco Customer Churn Analysys.pdf` for executive summary
4. **Modify Analysis**: Update parameters in the notebook for different scenarios

## Model Performance

The predictive models achieved strong performance metrics:
- Accuracy: High classification accuracy in identifying potential churners
- Precision: Reliable identification of true positive churn cases
- Recall: Effective capture of customers at risk
- F1-Score: Balanced performance across metrics

## Recommendations

1. **Target Retention Campaigns**: Focus on month-to-month customers with targeted retention offers
2. **Service Bundling**: Encourage customers to adopt multiple services to increase lifetime value
3. **Early Engagement**: Implement onboarding programs for new customers
4. **Proactive Support**: Use predictive scores to identify at-risk customers for proactive outreach
5. **Contract Incentives**: Offer discounts for longer-term contract commitments

## Future Enhancements

- Incorporate additional external data sources
- Develop real-time churn prediction API
- Implement deep learning models for improved predictions
- Create automated alerting system for high-risk customers
- Build customer lifetime value (CLV) models

## Technologies & Concepts

- **Machine Learning**: Supervised learning, classification
- **Statistics**: Correlation analysis, statistical testing
- **Data Science**: EDA, feature engineering, model evaluation
- **Business Analytics**: Customer segmentation, retention analysis

## Author

Bhuvan CW

## License

This project is open source and available for educational and research purposes.
