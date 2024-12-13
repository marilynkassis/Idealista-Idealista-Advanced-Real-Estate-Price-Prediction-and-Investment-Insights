# Idealista-Advanced-Real-Estate-Price-Prediction-and-Investment-Insights
A machine learning-powered solution for accurate property valuation and tailored investment recommendations across Barcelona, Madrid, and Valencia.

# Idealista IQ: Advanced Real Estate Price Prediction and Investment Insights

Idealista IQ is a cutting-edge tool designed to predict real estate prices and provide personalized investment advice in three major Spanish cities: Barcelona, Madrid, and Valencia. This project leverages advanced machine learning techniques and collaborative filtering to empower buyers, sellers, and investors with actionable insights.

## Project Overview

Accurate property valuation is vital for informed decision-making in the real estate market. Idealista IQ analyzes over 189,000 housing units and more than 40 features to deliver fair market values, rental income estimates, and investment trend analysis. By enhancing valuation accuracy, the tool aims to boost investor confidence and optimize returns.

### Key Features:
- **Accurate Price Prediction:** XGBoost with Box-Cox transformation delivers high-precision valuation with MAPE values of 0.87% (Barcelona), 0.24% (Madrid), and 0.60% (Valencia).
- **Personalized Insights:** Collaborative filtering algorithms offer tailored recommendations based on user profiles and market trends.
- **Comprehensive Analysis:** Evaluates relationships between property prices and key factors like size, number of rooms, and proximity to metro stations.

## Methodology

1. **Data Preparation:**
   - Cleaned data to handle outliers, duplicates, and missing values.
   - Transformed data using Box-Cox techniques for improved model performance.

2. **Exploratory Data Analysis (EDA):**
   - Identified key features impacting property prices, including constructed area and metro proximity.

3. **Machine Learning Models:**
   - Tested linear regression, random forest, XGBoost, and LightGBM.
   - Selected XGBoost with Box-Cox transformation for the highest accuracy.

4. **Recommendation Engine:**
   - Applied collaborative filtering to generate personalized investment advice.

## Results and Insights

### Prediction Accuracy:
- **Barcelona:** MAPE = 0.87%
- **Madrid:** MAPE = 0.24%
- **Valencia:** MAPE = 0.60%

### Key Findings:
- Property prices are heavily influenced by constructed area, number of rooms, and proximity to metro stations.
- Investment strategies can improve by 10-15% with insights from Idealista IQ.

![Model Performance](images/model_performance.png)

### Limitations:
- Requires robust ETL processes to maintain data quality.
- Adherence to data privacy laws is critical.
- Continuous updates are needed to reflect market changes and reduce bias in recommendations.

## Recommendations

1. **Integration with Financial Institutions:**
   - Provide seamless financing options for investors.

2. **Blockchain Implementation:**
   - Enhance transactional security using blockchain technology.

3. **AR/VR Features:**
   - Enable virtual property tours for improved customer experience.

4. **Sustainability Focus:**
   - Highlight eco-friendly properties to align with market trends.

5. **Predictive Market Analytics:**
   - Incorporate future market trend predictions to guide investment decisions.

## Future Potential

Idealista IQ positions itself as a game-changing tool in the real estate sector. By addressing data quality and privacy concerns, scaling infrastructure, and implementing innovative features, the platform can revolutionize property valuation and investment strategies.

