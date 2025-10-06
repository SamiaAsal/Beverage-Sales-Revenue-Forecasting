##☕ Beverage Sales Revenue Optimization (DDR-Opt)

🎯 Project Introduction and Business Value
This is an End-to-End Data Science Capstone Project designed to transform raw beverage sales data into actionable strategic insights. The primary goal is to build a highly accurate predictive model to help management optimize pricing strategies and maximize revenue by truly understanding the factors that drive the value of each sales transaction.

📈 Methodology and Key Results
Machine Learning algorithms were utilized to forecast the revenue/price variable (money) based on sales features such as coffee_name, Time_of_Day, and Weekday.

1. Model Performance Evaluation
Several models were tested, and the XGBoost model achieved the highest accuracy, establishing it as the production-ready choice.
Linear Regression
RMSE: 0.2489955531292677
R2 Score: 0.9891157543865174
Random Forest
RMSE: 0.1786766034929577
R2 Score: 0.9921895792380254
XGBoost
RMSE: 0.157638686029706
R2 Score: 0.9931092015284175

2. Visual Validation of Accuracy
The "Actual vs. Predicted Sales" chart demonstrates how closely the model's predictions align with the real-world values, confirming high confidence in the results.

🔑 Key Business Insights (Feature Importance)
The core output of this project is the Feature Importance analysis, which uncovers the true revenue drivers.

Core Finding: Product Over Time
The analysis conclusively proved that beverage type (coffee_name) is the dominant factor determining the transaction value, while the influence of time-based factors (Weekday, Time_of_Day) is negligible.

Strategic Recommendation	Supporting Variable	Proposed Action
Focus on Product Portfolio	coffee_name_Espresso (Importance 
≈0.275
)	Pricing and marketing efforts must be directed toward Espresso and Latte beverages to significantly boost the average basket value.
Avoid Time-Based Dynamic Pricing	Time_of_Day (Near-zero Importance)	Avoid complex dynamic pricing based on the hour or day. Focus operational efforts on improving speed and quality during peak times to ensure return on investment (ROI).
Analyze Anomalous Factors	Month name_3 (March)	Investigate the specific conditions of March (e.g., successful campaign, seasonal shift) and replicate that success in other months.
