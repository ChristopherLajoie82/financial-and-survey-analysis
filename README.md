### [My  Survey Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYmE3MTkyYWUtMTRiNS00ZmRlLTgyMDQtMGNlYzRhNWIwNmRiIiwidCI6IjUwNjE3YzZkLWJiY2MtNDUwYi1hY2YxLTZiYmEyNzZhNjUzOCIsImMiOjJ9&embedImagePlaceholder=true)

# Financial-And-Survey-Analysis
## **Overview**  
In this project, I conducted a comprehensive data analysis for a non-profit organization with the aim of improving event attendance, membership engagement, and donation levels. The analysis included designing a 27-question survey that received 264 responses and analyzing the organization’s financial data from January 2022 to August 2024. The goal was to identify key factors influencing member participation and financial contributions, ultimately guiding strategic decision-making.

## **Survey Analysis**  
The survey focused on understanding the preferences and behaviors of the organization's members and supporters. Key areas of interest included event attendance, membership status, donation habits, and preferred communication channels. The insights gained from this analysis helped align the organization's marketing and engagement strategies with the needs and interests of its community.

## **Machine Learning Models**

### 1. **Random Forest Model**  
   - **Purpose**: Predict membership retention and donation likelihood based on survey responses.
   - **Performance**:
     - **Accuracy**: 77.36%  
     - **Class 0 (Majority Class)**:
       - Precision: 0.78
       - Recall: 0.95
       - F1-Score: 0.85  
     - **Class 1 (Minority Class)**:
       - Precision: 0.75
       - Recall: 0.38
       - F1-Score: 0.50  
   - **Insights**: The model performed well in predicting outcomes for the majority class but struggled with the minority class, highlighting potential class imbalance. Further model tuning or class balancing techniques may improve results for the minority class.

### 2. **Regularized Linear Regression Model**  
   - **Purpose**: Assess the relationship between multiple features (e.g., age, event attendance, donation history) and their impact on key outcomes.
   - **Regularization**: Ridge Regression (Alpha set to 4)
   - **Performance**:
     - **Training R²**: 0.8325 to 0.8662
     - **Test R²**: Ranged from -0.3861 to 0.9107
     - **Training RMSE**: 0.1553 to 0.1741
     - **Test RMSE**: 0.1275, with significant errors in some cases indicating potential overfitting or data issues.
   - **Insights**: While the model showed strong predictive performance during training, test performance was variable. This suggests that further tuning or refined feature selection may improve the model’s generalizability.

### 3. **Logistic Regression Model**  
   - **Purpose**: Classify members based on their likelihood to donate or renew membership.
   - **Approach**: Standard logistic regression was applied to predict binary outcomes, focusing on key predictors from the survey data.
   - **Insights**: This model identified which factors most strongly influenced binary outcomes, such as donation behavior and membership renewal, providing actionable insights for the organization.

### 4. **K-Fold Cross-Validation**  
   - **Purpose**: Ensure the robustness and generalizability of the models.
   - **Approach**: K-Fold cross-validation was applied to evaluate model consistency across different subsets of the data, reducing the risk of overfitting and increasing confidence in the results.

## **Financial Data Analysis**  
Alongside the survey, I analyzed the organization’s financial data, focusing on cash flow and membership contributions. This analysis provided insights into revenue generation, event profitability, and donor engagement, offering practical recommendations for improving financial management.

## **Key Findings and Recommendations**

### 1. **Optimize Advertising Strategy**  
   - Invest in targeted marketing, particularly to boost event attendance and membership renewals in underperforming areas. Leverage the survey’s insights into preferred communication channels (e.g., word of mouth, online marketing).

### 2. **Enhance Donor Engagement**  
   - **Personal Connection**: Highlight the impact of donations through storytelling around the organization’s mission.
   - **Trust & Motivation**: Build donor trust through transparent communication and regular updates, emphasizing the tangible outcomes of their support.

### 3. **Focus on Profitable Events**  
   - Analyze successful events to identify key drivers of success. According to survey responses, younger audiences prefer low-cost, family-oriented events, while older demographics are drawn to cause-specific events. Tailoring event offerings based on these preferences can enhance attendance and satisfaction.

### 4. **Strengthen Membership Retention**  
   - **Targeted Engagement**: Older members with longer-term ties to the organization are more likely to renew. Tailor engagement strategies to maintain their involvement.
   - **Youth Engagement**: Younger members are more uncertain about future membership. Developing youth-centric programs can foster long-term loyalty.

### 5. **Community Involvement & Growth**  
   - **Word of Mouth**: This remains a powerful tool for spreading awareness. Encourage current members to act as ambassadors for the organization to drive membership growth.
   - **Long-Term Loyalty**: Engage younger audiences early by offering value and benefits that encourage sustained involvement.

### 6. **Financial Management**  
   - **Donation & Event Revenue**: Optimize revenue streams by focusing on high-performing events and improving donor engagement.
   - **Diversify Income Streams**: To reduce reliance on donations and event-based income, explore additional revenue opportunities such as merchandise sales or partnerships with local businesses.

## **Conclusion**  
This project provided the non-profit organization with data-driven insights to enhance member engagement, optimize events, and improve financial stability. The survey analysis, combined with financial data and predictive modeling, offered a comprehensive understanding of key areas for improvement. These findings will guide the organization’s future strategies, helping it achieve its mission more effectively and sustainably.
