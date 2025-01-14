# Free-to-Premium Conversion Analysis

This repository contains an analysis project aimed at improving free-to-premium conversion rates for a subscription-based service. The project uses A/B testing, logistic regression modeling, and daily conversion rate tracking to identify effective interventions.

## Files

1. **`daily_conversion_analysis.ipynb`**
   - **Purpose:** Tracks daily conversion rates by calculating the proportion of premium purchases for each day divided by the number of free users registered within the last 30 days.
   - **Details:** 
     - Assumes users decide to convert within 30 days.
     - Provides insights into daily trends in user behavior.

2. **`overall_analysis.ipynb`**
   - **Purpose:** Performs a comprehensive analysis of the dataset to identify key factors influencing conversion and prepares for A/B testing.
   - **Content Highlights:**
     - Data preprocessing: Handling missing values, outliers, and feature scaling.
     - Logistic regression modeling to predict high-probability converters.
     - Sample size calculations for A/B testing.
     - Recommendations for treatment group interventions focused on early user engagement.

## Key Insights
- Early days are critical for user conversion; targeted interventions can significantly improve conversion rates.
- Data-driven A/B testing ensures statistically sound decisions for boosting premium subscriptions.

## How to Use
1. Open `daily_conversion_analysis.ipynb` to analyze daily conversion trends and assess user behavior dynamics.
2. Explore `overall_analysis.ipynb` for in-depth insights, predictive modeling, and A/B testing recommendations.

## Requirements
- Python 3.8+
- Key libraries: `pandas`, `numpy`, `statsmodels`, `scikit-learn`, `matplotlib`

## Contributions
Contributions to improve analysis methods, add new features, or optimize code are welcome. Please fork the repository and create a pull request with your suggestions.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.
