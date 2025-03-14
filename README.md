## ShopEasy-Marketing Analytics (Online Retail Store) With SQL, Python, And PowerBI
---
### Table of Contents
- [Overview](#overview)
- [Objectives](#objectives)
- [Steps And Processes](#steps-and-processes)
- [Tools](#tools)
- [Key Performance Indicators](#key-performance-indicators)
- [Actions And Recommendations](#actions-and-recommendations)
### Overview
This project seeks to conduct a detailed marketing analytics to uncover insights into ShopEasy's reduced customer engagements,  conversion rates, and campaign performance metrics despite launching several new online marketing campaigns, in addition to actionable strategies for improved business performance and delivery.


<img width="611" alt="OverviewDashboard" src="https://github.com/user-attachments/assets/09de384f-477e-4b32-9c14-0f850417c2f0" />

### Objectives
#### Increase Conversion Rates:
- Goal: Identify factors impacting the conversion rate and provide recommendations to improve it.
- Insight: Highlight key stages where visitors drop off and suggest improvements to optimize the conversion funnel.
#### Enhance Customer Engagement:
- Goal: Determine which types of content drive the highest engagement. 
- Insight: Analyze interaction levels with different types of marketing content to inform better content strategies (Likes, Clicks, Views).
#### Improve Customer Feedback Scores:
- Goal: Understand common themes in customer reviews and provide actionable insights.
- Insight: Identify recurring positive and negative feedback to guide product and service improvements.
### Steps And Processes
1. Data Collection:
    - Data from various sources, including customer reviews, social media comments, and campaign performance metrics were gotten through the Marketing Manager and the Customer Experience Manager at ShopEasy.
2. Data Cleaning And Preprocessing (SQL):
    - Checking and Removal of Dublicate values
    - Performing Various SQL queries and transformations on Tables as: Product Table, Customer Table, Customer Review Table, Engagement Table, and Customer Journey Table.
    - Advanced Sentiment Analysis with Python:Enriching marketing data with valuable sentiment information, aiding in more data-driven, decision-making.
3. Importing Data Into PowerBI:
    - Transforming tables into right data formats.
    - Adding suitable data models and creating right relaionships to link various tables together.
    - Creating suitable Measures for easy visualizations.
    - Designing and creating Interactive Dashboard.
### Tools
- SQL(SSMS):Performing data cleaning, joining of tables and dealing with duplicates.
- Python: Advanced sentiment analysis and enrichment of marketing data.
- MS PowerBI: Creating data models amonst various tables, relationships, data transformation and visualizations.
### Key Performance Indicators
1. Decreased Conversion Rates:
    - Conversion rate demonstrated a strong rebound in December, reaching 10.2%, despite a 5.0%  dip in October.
    - Conversion rates varied, with higher numbers of products converting successfully in months like February and July suggesting that  some products had strong 
      seasonal peaks.
    - January recorded the highest overall conversion rate at 18.5%, driven significantly by the Ski Boots with a remarkable 150% conversion.
    - May experienced the lowest overall conversion rate at 4.3%, with no products standing out significantly in terms of conversion.

      

2. Customer Engagement:
    - Decline in overall social media engagement, with views dropping throughout the year.
    - clicks and likes were low compared to views, the click-through rate stands at 15.37%, meaning that engaged users are still interacting effectively.
    - Blog content drove the most views, especially in April and July, while social media and video content maintained steady but slightly lower engagement.
    - Views peaked in February and July but declined from August and on, indicating reduced audience engagement in the later half of the year.
  
      <img width="418" alt="Views-clicks-likes db" src="https://github.com/user-attachments/assets/c76876e3-b010-4104-bef8-c0ea9df2a187" />

3. Customer Feedback Analysis:
    - Customer ratings did remain consistent, averaging around 3.7 throughout the year.
    - Though stable, the average rating was below the target of 4.0, suggesting a need for focused improvements in customer satisfaction, for products below 3,5.
    - The majority of customer reviews are in the higher ratings, with 140 reviews at 4 stars and 135 reviews at 5 stars, indicating overall positive feedback.
    - Positive sentiment dominated with 275 reviews, reflecting a generally satisfied customer base. Negative sentiment was present in 82 reviews.
    - The presence of mixed positive and mixed negative sentiments suggests that there are opportunities to convert those mixed experiences into more clearly positive
      ones.

      <img width="230" alt="customer_sentiment_db" src="https://github.com/user-attachments/assets/ff8620cf-496d-4486-ad35-937b5e546bc5" />

### Actions And Recommendations
- Target High-Performing Product Categories: Focus marketing efforts on products with demonstrated high conversion rates, such as Kayaks, Ski Boots, and Baseball 
  Gloves. 
- Implement seasonal promotions or personalized campaigns during peak months (e.g., January and September) to capitalize on these trends.
- Revitalize Content Strategy: To turn around declining views and low interaction rates, experiment with more engaging content formats, such as interactive videos 
  or user-generated content. Additionally, boost engagement by optimizing call-to-action placement in social media and blog content, particularly during 
  historically lower- engagement months (September-December).
- Address Mixed and Negative Feedback: Implement a feedback loop where mixed and negative reviews are analyzed to identify common issues. Develop improvement plans 
  to address these concerns. 
- Consider following up with dissatisfied customers to resolve issues and encourage re-rating, aiming to move average ratings closer to the 4.0 target.

  



        




         





      


