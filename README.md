# market_campaign_analysis
Using Microsoft SQL Server and Power BI to provide data-driven insights on a market campaign performance

**Introduction**

Campaign performance analysis is the structured evaluation of marketing campaign outcomes aimed at determining the campaign's impact and success. This process includes identifying key metrics like impressions, conversions, conversion rates, click-through rate (CTR), cost per click (CPC), and return on investment (ROI), gathering and analyzing relevant data, and interpreting the findings to derive valuable insights, aimed at making informed, data-driven decisions and improving future marketing strategies.

**Project Overview**

A fictional company has run multiple marketing campaigns across to promote its products, and has collected detailed data on daily ad performance, covering several metrics. The goal of this project is to analyze the data to evaluate campaign effectiveness, optimize advertising costs, and enhance future marketing strategies by identifying performance trends over time.

**Data Description, Analysis, Insights and Recommendations.**

The dataset in a CSV file format, comprised 18 columns with 9,900 rows. The CSV file was imported into MS SQL Server for cleaning, manipulation and exploratory analysis. 

Find detailed sql queries for exploratory data analysis in the repository. 

After exploratory analysis, dataset was exported to Power BI via the SQL Server connection for visualization and report. 

![image](https://github.com/user-attachments/assets/61aee0ab-690e-4bb5-a092-839f3bed4d47)

The report enables users to explore metric impacts and category-specific data (campaign, channel, device, city, location) through interactive slicers and dropdowns. A flow chart visually maps the campaign journey from its start through ad channels to device usage, with selectable metrics dynamically adjusting node connections.


**Analysis, Insights and Recommendations.**

For detailed insights and recommendations, (link to Medium).

**_Correlations between key metrics_**

Correlations in marketing campaigns are essential for understanding the relationships between various metrics and assessing effectiveness, revealing that higher spending on discount ads led to increased engagement and clicks. While a positive correlation between impressions and clicks was noted, with Birmingham and Pinterest demonstrating the strongest connections, no significant relationship was found between impressions and conversions, indicating a need for strategic adjustments to enhance conversion rates.
Campaign performance analyses

_**Campaign period**_

The Fall campaign achieved the highest impressions, clicks, conversions, and engagement rates, along with the highest CTR, but it also had the lowest conversion rate (CVR) and ROI despite significant investment. In contrast, the Summer campaign had the highest CVR and ROI, though it generated the fewest impressions, clicks, and conversions, suggesting that audience segmentation and tailored messaging in the Fall could improve lead quality, while adopting strategies from Fall to boost CTR in the Summer may enhance performance further.

_**Channel**_

Pinterest proved to be the most cost-effective platform for the company, delivering the highest ROI and CVR with the lowest investment and average CPC, while Instagram ranked second in both ROI and CVR, with strong CTR and relatively low CPC. Despite receiving the most investment, Facebook underperformed, showing the need for a reevaluation of targeting and campaign strategies to improve results.

_**City**_

Birmingham achieved the highest CVR and ROI despite having the fewest impressions, clicks, and engagements, indicating that lower investment can yield better outcomes, while London, despite its largest financial input, recorded the lowest ROI and CVR. The varying investment across cities likely reflects population differences, suggesting that a tailored campaign addressing London’s specific audience needs could improve conversion rates, and considering regional factors like cultural preferences and economic conditions may further enhance campaign effectiveness in different cities.

_**Device**_
Understanding the devices used to view ads is essential for developing effective marketing strategies, as tailoring ads to specific devices ensures that products and services remain visible to consumers. While mobile ads generate more impressions, clicks, and engagement due to widespread mobile phone usage, desktop ads demonstrate a significantly better Conversion Rate (CVR) and Return on Investment (ROI), suggesting that despite mobile's ability to drive traffic, desktop platforms are more effective for conversions, indicating a need to allocate more budget toward desktop ads for campaigns focused on high conversion rates and stronger returns.

_**Ad**_

Collection ads generated more impressions and clicks due to their visually appealing format, resulting in lower CPC and higher CTR; however, discount ads provided nearly 200% better ROI and higher CVR, indicating their greater profitability. To optimize performance, it’s advisable to combine collection ads with discount offers, enhancing awareness while driving immediate action, and to allocate more budget toward discount campaigns, especially on platforms like Pinterest, where users are more likely to convert.

_**Time Series**_

Given the lack of variations in key metrics across different days of the week, a detailed analysis of monthly trends was sufficient to identify patterns that could enhance marketing campaigns. The summer campaign, despite having the fewest impressions and clicks from June to August, achieved the highest Conversion Rate (CVR) and Return on Investment (ROI) with lower spending, while the more expensive campaigns from September to November resulted in the highest impressions and clicks but the lowest CVR and ROI

