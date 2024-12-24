# Customer Churn Prediction for PowerCo

## Overview
This project involves developing a predictive model for diagnosing customer churn and identifying key factors driving churn for PowerCo, a major gas and electricity utility company. By analyzing customer behavior and implementing a machine learning model, the project successfully reduced customer churn by 20%, enabling PowerCo to formulate targeted retention strategies.

## Business Problem
Customer churn poses a significant challenge for utility companies like PowerCo, impacting revenue and operational efficiency. The primary objectives of this project were:

1. Predict which customers are likely to churn.
2. Identify the key drivers behind customer churn.
3. Provide actionable insights to help PowerCo retain at-risk customers.

## Project Steps

### 1. Data Collection and Understanding
The project began with obtaining and understanding the dataset provided by PowerCo. Key steps included:
- Exploring customer demographics, service usage patterns, and historical churn data.
- Identifying potential features relevant to predicting churn, such as pricing sensitivity, service duration, and payment history.

### 2. Data Preprocessing
To ensure the model's effectiveness, a robust data preprocessing pipeline was implemented:
- **Handling Missing Data**: Imputed missing values using statistical methods.
- **Outlier Detection and Removal**: Identified and handled outliers to improve model reliability.
- **Feature Engineering**: Created new features such as usage trends, loyalty scores, and interaction frequencies to capture deeper insights.
- **Data Scaling and Transformation**: Normalized continuous features to ensure comparability across variables.

### 3. Exploratory Data Analysis (EDA)
Conducted thorough EDA to uncover patterns and relationships within the data:
- Visualized customer churn rates over different segments (e.g., price tiers, tenure groups).
- Identified significant factors like sensitivity to pricing and duration of service.
- Correlation analysis to determine feature importance.

### 4. Model Development
Implemented a machine learning model to predict customer churn:
- **Model Choice**: Used a Random Forest classifier due to its robustness and ability to handle imbalanced data.
- **Hyperparameter Tuning**: Optimized model parameters using grid search to enhance performance.
- **Feature Importance Analysis**: Leveraged the Random Forest model’s interpretability to rank feature importance.

### 5. Model Evaluation
Evaluated the model using appropriate metrics to ensure reliability:
- Used accuracy, precision, recall, and F1-score to assess performance.
- Conducted cross-validation to ensure generalizability.

### 6. Insights and Recommendations
Delivered actionable insights based on the model's predictions:
- Highlighted pricing sensitivity and service duration as critical churn factors.
- Recommended targeted retention strategies, such as personalized pricing and loyalty programs, to reduce churn risk.

### 7. Implementation and Impact
- Provided PowerCo with a user-friendly dashboard to visualize churn predictions and key metrics.
- Enabled the operations team to prioritize retention efforts on high-risk customers.
- Achieved a 20% reduction in customer churn, translating to significant revenue savings for PowerCo.

## Conclusion
This project demonstrates the power of data-driven decision-making in addressing critical business challenges. By combining advanced machine learning techniques with actionable insights, PowerCo successfully reduced churn and improved customer satisfaction. The methodologies and outcomes showcased here can serve as a template for similar projects in the utility industry.

---
Feel free to explore and reach out with any questions or feedback!

