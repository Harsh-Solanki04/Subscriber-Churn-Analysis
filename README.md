# Subscriber-Churn-Analysis

## Executive Summary

This report analyzes subscription cancelation trends to identify key reasons for customer churn. Through SQL-based data exploration, we assess the frequency of cancelation reasons, customer behavior in selecting multiple reasons, and year-over-year trends. The analysis highlights the most common reasons for churn and provides recommendations to improve customer retention and reduce cancelations.

### Business Problem

The company has observed a higher-than-expected churn rate, which negatively impacts revenue and growth. Understanding why customers cancel their subscriptions is crucial for developing strategies to enhance customer retention and improve user satisfaction. The leadership team requires data-driven insights to address this retention challenge effectively.


### Skills: 
- SQL: CTEs, CASE, Union, View creation
- Data visualization
- Data Wrangling
- Data Cleaning
- Data Science Notebook
- Snowflake Data warehouse
- Data Interpretation: Identifying trends in customer churn behavior.
- Business Intelligence: Translating insights into actionable retention strategies.
- Problem-Solving: Recommending solutions to reduce cancelation rates.

### Data Exploration and Understanding

Dataset Overview

The analysis focuses on key data sources tracking subscription cancelations:

- Cancelation Logs: Capturing reasons for user churn.
- Subscription Identifiers: Tracking unique customer subscriptions.
- Cancelation Timestamps: Allowing year-over-year trend analysis.

Understanding this data helped uncover patterns in customer churn behavior.

Cancelation Analysis-

Frequency of Cancelation Reasons

The most common cancelation reasons were identified and ranked by their occurrence.

The distribution of reasons was analyzed across unique subscriptions.

5.2 Completeness of Cancelation Reason Selection

Customers were required to select at least one reason for cancelation, with up to two additional optional reasons.

The average number of reasons selected per subscription was calculated to determine how detailed users were in their feedback.

Analysis was conducted to assess whether users were engaging thoughtfully with the cancelation survey or selecting random reasons to expedite the process.

5.3 Trends in Cancelation Reasons Over Time

A consolidated dataset was created to track cancelation reasons across all three possible selections.

Year-over-year analysis was conducted to identify shifts in cancelation motivations.

Percentages of specific cancelation reasons within each year were calculated to highlight significant changes over time.

### Key Findings

A large percentage of users provided only the required first reason for cancelation, with fewer selecting additional reasons.

The most frequently cited cancelation reasons included pricing concerns, lack of feature usage, and better alternatives available.

Cancelation trends fluctuated over time, with certain reasons becoming more prominent in specific years.

Some users appeared to select random reasons to bypass the cancelation process quickly, raising concerns about the accuracy of the data.

### Recommendations

- Enhance the Cancelation Flow:

Allow users to provide additional context for their cancelation reason.

Implement an optional feedback section for qualitative insights.

- Targeted Customer Retention Strategies:

Introduce tailored retention offers based on cancelation reasons.

Provide proactive engagement for users at risk of cancelation based on historical trends.

- Product Improvements:

Address common pain points highlighted in cancelation feedback.

Enhance value propositions to better compete with alternatives in the market.

- Since most users, have selected Expensive and Not Useful as the reasons to cancel, we should rollout better onboarding and provide more help early on in their subscription to ensure users and understanding the product and finding it useful. If they find the product more useful and valuable, they also many become less cost-sensitive to the value.
- Since the most common cancelation reason for the secondary reason is Went to Competitor, we should research the market and ensure we're keeping up to date with industry trends.
### Results

The following visualizations illustrate key insights from the analysis:

- Cancelation Reason Distribution – Identifying the most common reasons for churn.
  ![image](https://github.com/user-attachments/assets/91289d07-1faf-48c4-88d9-9781b9816142)
  
- Average Number of Reasons Selected – Analyzing user engagement with the cancelation survey.
- Yearly Cancelation Trends – Highlighting shifts in user dissatisfaction over time.
![image](https://github.com/user-attachments/assets/0e1ed0ca-4644-41f6-8d8d-a9a39b4c8d5c)

- 81% of users are selecting at least 1 additional cancelation reason (beyond the first required one), but most users are not selecting all 3 which suggests lack of interest and frustration for the user.
- 31% of users reported "Expensive" as the primary (first) cancelation reason. The top choices for the primary reason were "Not Useful","Expensive","Bad Customer Service" and "Went to a competitor".

### Conclusion

By analyzing subscription cancelation data, we identified key factors contributing to customer churn. Addressing these pain points through targeted retention strategies and product enhancements can improve user satisfaction and reduce cancelation rates. The next steps involve collaborating with the product and marketing teams to implement these recommendations and measure their effectiveness over time.

