# financial-and-survey-analysis
Overview: In this project, I conducted a comprehensive data analysis for a non-profit organization aiming to improve event attendance, membership engagement, and donation levels. The analysis involved designing a 27-question survey, which garnered 264 responses, and analyzing the organization’s financial data from January 2022 to August 2024. The goal was to identify key factors that influence member participation and financial contributions, ultimately guiding strategic decision-making.

Survey Analysis: The survey focused on understanding the preferences and behaviors of the organization's members and supporters. Key areas of interest included event attendance, membership status, donation habits, and communication channels. The insights gained from this analysis informed the organization's marketing and engagement strategies, ensuring they align with the needs and interests of their community.

Machine Learning Models: To gain deeper insights and predict key outcomes, I employed a variety of machine learning models, including:

Random Forest Model:

Purpose: To predict membership retention and donation likelihood based on survey responses.

Performance:

Accuracy: 77.36%

Class 0 (Majority Class):

Precision: 0.78

Recall: 0.95

F1-Score: 0.85

Class 1 (Minority Class):

Precision: 0.75

Recall: 0.38

F1-Score: 0.50

Insights: The model excelled in predicting outcomes for the majority class, while it struggled with the minority class, highlighting a potential class imbalance issue that could be addressed in future model tuning.

Regularized Linear Regression Model:

Purpose: To assess the relationship between multiple features (such as age, event attendance, and donation history) and their impact on key outcomes.

Regularization: Ridge Regression with alpha set to 4.

Performance:

Training R²: 0.8325 to 0.8662

Test R²: Ranged from -0.3861 to 0.9107

Training RMSE: 0.1553 to 0.1741

Test RMSE: 0.1275 to very large errors in some cases (indicating potential overfitting or data issues in specific segments).

Insights: The model provided strong predictive performance in training but showed variability in test performance, suggesting that further tuning or feature selection may be needed to improve generalization.

Logistic Regression Model:

Purpose: To classify members based on their likelihood to donate or renew membership.

Approach: Standard logistic regression was used to model binary outcomes, focusing on key predictors identified from the survey.

Performance: The model provided clear insights into which factors most strongly influenced binary outcomes, such as donation behavior or membership renewal.

K-Fold Cross-Validation:

Purpose: To validate the robustness and generalizability of the models.

Approach: I applied K-Fold cross-validation to ensure that the models performed consistently across different subsets of the data, reducing the risk of overfitting and improving confidence in the results.

Financial Data Analysis: Parallel to the survey, I analyzed the financial data of the non-profit, focusing on cash flow and membership contributions. This analysis highlighted trends in revenue generation, event profitability, and donor engagement, providing actionable insights for improving financial management.

Key Findings:
Optimize Advertising Strategy: 

•Consider investing in targeted marketing, especially to boost event attendance and membership renewals, particularly in underperforming areas. This could include leveraging the preferred communication channels identified in the survey, such as word of mouth and online methods.

Enhance Donor Engagement: 

•Personal Connection: Emphasize the impact of donations and strengthen storytelling around the organization’s mission.

•Trust & Motivation: Ensure communication highlights trust in the organization and the impact of donations. Regular updates and transparency can reinforce donor confidence and encourage continued support.

Focus on Profitable Events:

 Analyze successful events and replicate their key elements to maximize revenue. The survey indicates a preference for low-cost, family-oriented events among younger audiences and cause-specific events for older demographics. Prioritizing these could enhance attendance and satisfaction.

Strengthen Membership Retention:

 •Targeted Engagement: Membership renewal rates are higher among older demographics with long-term ties to the organization. Tailor engagement strategies, benefits, and communication to reinforce their connection and encourage renewals.

•Youth Engagement: Younger demographics express uncertainty about future membership. Introduce programs that specifically appeal to them, potentially leading to long-term loyalty.

Community Involvement & Growth:

•Word of Mouth: Leverage this powerful tool for spreading awareness, as indicated by the survey. Engaging current members as ambassadors could enhance community involvement and drive membership growth.

•Long-Term Loyalty: Engage younger audiences early to cultivate long-term membership. Offering early value and benefits can lead to sustained involvement over the years.

Financial Management:

Donation & Event Revenue: Optimize revenue streams by focusing on the most profitable events and enhancing donor engagement. Continued monitoring of income sources will help maintain financial stability.

Diversify Income Streams: To reduce the reliance on donations and event-based income, consider developing additional revenue streams, such as merchandise sales or partnerships with local businesses.

Conclusion: This project provided the non-profit with data-driven insights to enhance member engagement, optimize events, and improve financial stability. The findings will guide future strategies, helping the organization fulfill its mission more effectively.

