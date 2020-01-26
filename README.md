# Customer retention: equity investment
For the full project report and code, please view Customer_Retention_Equity_Investment.ipynb

## Business goal
In order to imporove user retention and lower churn, company is interested in understanding why and which users withdraw money from thier account.

## Data
Anomalized real data from financial service company.

## Project summary
• Analyzed 1 million entries of customer data in equity investment collected over 1 year. <br>
• Performed exploratory data analysis on churned customers<br>
• feature engineering: ordinal -> numerical, categorical -> one-hot encoded.<br>
• Upsampled churned customer data (4% of total) to address data imbalance.<br>
• Tuned random forest to obtain best recall score, and used logistic regression as baseline comparison.<br>
• Discovered meaningful insight from feature importance: target customers with limited or no investment experience and high risk tolerance to lower churn rate.

## Conclusion
This data analysis unveiled that customer churn rate is higher for the group with limited or no investment experience. The data suggested that providing assistance for customers with less investment experience can effectively decrease customer churn / increase customer retention. Customer churn rate is also higher for the group with higher risk tolerance. When customers take higher risks, they may panic and sell at the wrong time, which in turn them to churn. From the data, high risk tolerance is correlated with investment experience. This reierate again on the importance of providing further assistance for customers with less investment experience.
