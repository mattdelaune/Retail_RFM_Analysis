# Power BI RFM Analysis Multi-Page Report

## Executive Overview
Welcome to the Customer RFM (Recency, Frequency, Monetary) Analysis Project! This initiative provides comprehensive insights into customer behavior, engagement, and value, showcasing the power of RFM analysis. This project demonstrates how to drive targeted marketing strategies, enhance customer retention, and maximize business profitability by understanding and segmenting customers. Key features include the use of DAX expressions for precise calculations, interactive visualizations with dynamic filters and tooltips for an enhanced user experience, and a thorough data analysis with actionable recommendations. Additionally, a fictionalized timeline and roadmap outline the proposed steps for implementation.

## Table of Contents
- [Technologies Used](#technologies-used)
- [Data Source](#data-source)
- [Features](#features)
- [Business Question](#business-question)
- [Methodology](#methodology)
- [Insights and Recommendations](#screenshots)
- [Further Analysis and Insights](#further-analysis-and-insights)
- [Recommendations](#recommendations)
- [Future Work](#future-work)
- [Contact](#contact)
- [Screenshots](#screenshots)

## Technologies Used
- **Power BI**: For creating multi-page interactive dashboards and reports.
  - **Advanced DAX Formulas**: Utilized for complex calculations and custom metrics.
  - **Data Modeling**: Ensured accurate relationships and calculations across tables.
  - **Power Query**: Used for data transformation and cleaning.
  - **Interactive Visualizations**: Implemented dynamic filters, tooltips, and engaging charts.

## Data Source
Our data comes from retail store sales transactions available on Kaggle. [The anonymized dataset](https://www.kaggle.com/datasets/marian447/retail-store-sales-transactions?resource=download) includes 64.682 transactions of 5.242 SKU's sold to 22.625 customers during one year.

## Features
- **Interactive Visualizations:** Engaging and interactive charts and graphs to deeply explore various customer segments.
- **RFM Segmentation:** Detailed breakdown of customers based on Recency, Frequency, and Monetary values.
- **Tooltips and Annotations:** Comprehensive explanations and insights are available through interactive tooltips on each page.
- **Dynamic Filters:** Slicers enabling data filtering based on R, F, and M scores for tailored analysis.
- **Comprehensive Analysis:** Dedicated pages for each aspect of RFM, including a thorough segment analysis, conclusions, and business recommendations.

## Business Question
**"How can we optimize our marketing budget by focusing on the highest ROI segments identified in the RFM analysis, while simultaneously addressing the needs of low-frequency and at-risk customers to maximize overall customer lifetime value?"**

## Methodology
I'll be performing an RFM (Recency, Frequency, Monetary) analysis to answer this business question. RFM analysis is a proven technique that segments customers based on how recently they made a purchase, how often they purchase, and how much they spend. This approach allows businesses to identify their most valuable customers and tailor marketing efforts to maximize ROI.

By using RFM analysis, we can prioritize marketing spend on high-value segments that are likely to deliver the greatest returns while also developing strategies to re-engage low-frequency and at-risk customers. This ensures that marketing efforts are both efficient and effective in enhancing customer retention and maximizing lifetime value.

## Insights and Recommendations:
1. **Customer Segment by Revenue:**
- **Oberservation:** High-value segments, such as Promising Customers, Cannot Lose Them, and Champions, significantly contribute to the overall revenue. These segments demonstrate strong engagement and loyalty, making them crucial for sustaining and growing revenue.
- **Actionable Insight:** Allocate a larger portion of the marketing budget to personalized loyalty programs, targeted offers, and retention strategies for these high-value segments. This will ensure that these customers remain engaged and continue contributing positively to the revenue.

2. **Customer Segement by Frequency and Engagement:**
- **Observation:** Low-frequency customers (F1, F2) have lower engagement levels, presenting an opportunity to boost their purchase frequency through targeted marketing efforts. Additionally, segments like At Risk and About To Sleep, while still contributing positively, are at risk of becoming inactive.
- **Actionable Insight:** Implement targeted marketing campaigns with personalized incentives for low-frequency customers to encourage more frequent purchases. Re-engage at-risk segments with specialized retention efforts, such as discounts, personalized communication, and tailored offers, to prevent churn and enhance customer lifetime value.

3. **Growth Potential of Customer Segements:**
- **Observation:** The RFM analysis reveals that New Customers and Lost Customers segments show potential for growth, yet they are not fully leveraged.
- **Actionable Insight:** Invest in strategies to nurture New Customers, moving them into higher value segments over time. Develop win-back campaigns aimed at Lost Customers to regain their business, focusing on addressing their previous pain points and offering compelling incentives.


## Further Analysis and Insights

### Recency Insights
- The majority of customers have made recent purchases, indicating high engagement.
- While only compromising a minority, the amount of customers with higher R scores suggests a need for retention strategies.
### Frequency Insights
- Most customers score highly in frequency.
- Targeting low-frequency customers with marketing campaigns can increase their engagement.
### Monetary Insights
- High-value segments like "Champions" and "Promising Customers" contribute significantly to revenue.
- Segments at risk of churning need targeted campaigns to maintain their engagement.

## Recommendations

### Immediate Actions: Quick Wins
**Engagement Programs:** 
- Initiate programs specifically aimed at recent customers to sustain their engagement.
- Consistently track the distribution of recent interactions to spot shifts in engagement patterns.

**Reactivation Campaigns:**
- Craft tailored campaigns to re-engage customers with high recency scores through personalized offers and incentives.
- Target low-frequency customers (F1, F2) with special promotions and reminders to encourage more frequent purchases.

**Focus on High-Value Customers:** 
- Launch loyalty initiatives for high-value segments such as Promising Customers, Cannot Lose Them, and Champions to sustain and enhance their value.

### Long-Term Strategies

**Customer Behavior Insights:** 
- Continuously study the behaviors and preferences of high-frequency customers to apply successful strategies to other segments.
- Develop and implement referral programs that leverage loyal customers to attract new ones.

**Segment-Specific Approaches:** 
- Re-engage segments like At Risk and About To Sleep with tailored incentives, discounts, and personalized communications.
- Encourage new customers to make repeat purchases, transitioning them into higher value segments.
- Devise strategies to win back Lost Customers and bolster retention efforts.

**Monitoring and Adaptation:**
- Regularly assess the contributions of different segments to the overall monetary value and adjust strategies based on evolving customer behaviors.
- Utilize insights from the waterfall chart to dynamically guide marketing and retention strategies.

## Future Work
- **Customer Lifetime Value (CLV) Evaluation:** Conduct an in-depth analysis of customer lifetime value to pinpoint long-term revenue potential and optimize the allocation of resources accordingly.
- **Churn Prediction:** Develop predictive models to identify customers at risk of churning and implement proactive retention strategies to mitigate this risk.
- **Enhanced Segmentation:** Investigate additional segmentation criteria beyond RFM, including customer demographics and behavior patterns, to refine and enhance marketing strategies.

## Contact
For more information, please contact:

**Name:** Matt Delaune

**Email:** matt.delaune@gmail.com

## Screenshots

![Dashboard Overview](images/dashboard_overview.png)
*Dashboard Overview Page*

![RFM Dashboard](images/rfm_dashboard.png)
*RFM Dashboard*

![Customer Segmentation](images/customer_segmentation.png)
*Customer Segmentation*

![Recency Analysis](images/customer_recency_analysis.png)
*Recency Analysis Page*

![Frequency Analysis](images/customer_purchase_frequency_analysis.png)
*Frequency Analysis Page*

![Monetary Analysis](images/customer_value_analysis.png)
*Monetary Analysis Page*

![Conclusion and Recommendations](images/conclusion_and_recommendations.png)
*Conclusion and Recommendations*

![Next Steps](images/next_steps.png)
*Next Steps*

![Project Timeline and Roadmap](images/project_timeline_and_roadmap.png)
*Project Timeline and Roadmap*
