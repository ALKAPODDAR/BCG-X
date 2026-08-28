# BCG X - Introduction to Data for Decision Makers - Job Simulation
analyzed using Jupyter Notebook

## Introduction
In this simulation, I joined the BCG X team on a fast-paced retail project. The client, NewCo, is a big box retailer that has just completed a multi-channel marketing campaign testing different messages (sales-focused vs. brand-focused) and channels (emails, Instagram, etc.). The BCG X team is partnering with NewCo to drive business growth and develop a sustainable long-term strategy.

* Client: NewCo - Completed a one-week, multi-channel marketing campaign designed to test messaging and customer response across a set of featured retail products.

client wants to know:

- Which campaign and channel combination delivered the most value?
- What drove engagement from new customers?
- Where should we focus our marketing investment next quarter—and why?

The job simulation was broken down into two tasks:

Task 1 – Analyze campaign performance. Compare how different strategies performed across formats, messages, and customer groups.
Task 2 – Visualize and present my insights. Help the client understand what worked, why it matters, and where to go from here.

## Task 1: 
This task aims at analyzing how different strategies performed across formats, messages, and customer groups.

Activities:
1. Reviewed the raw data as a dataframe in jupyter notebook
2. Analyzed measures like 'Total Sales by Channel', 'Total Sales by Campaign'
  
## Task 2:
This task aims at campaign performance analysis.
Note:
1. The campaign included two versions of messaging:
- Campaign A used an informal, conversational tone.
- Campaign B used a more sales-focused, promotional tone.
2. The client used three marketing channels:
- Email
- Instagram
- Website Banner 
3. Client Wants to Know:
“Which campaign + channel combo should we double down on to grow new customer sales—and why?”

Activities:
1. Conversion & Sales Analysis
Approach:
- Filtered dataset to focus only on new customers.
- Calculated conversion rate (percentage of new customers who purchased) by campaign + channel.
- Summarized total sales for each campaign + channel combination.
- Visualized results using bar charts for clarity.
Findings:
- Campaign B + Email had the highest conversion rate (~64.5%).
- Campaign A + Email generated the highest total sales ($2124.47).
- Instagram and Web Banner channels underperformed in both conversion and sales.
Final Recommendation:
- Email is the strongest channel for new customer acquisition.
- Campaign A (conversational tone) via Email should be prioritized for revenue impact.
- Campaign B (promotional tone) via Email can be used tactically for quick conversions.

2. Efficiency & Weighted Ranking
Approach:
- Engineered a new metric: Sales per Second on Site (efficiency).
- Normalized metrics (conversion, sales, efficiency) to make them comparable.
- Built a weighted scoring model (40% conversion, 40% sales, 20% efficiency).
- Ranked all campaign + channel combinations.
Findings:
- Campaign A + Email achieved the highest overall weighted score (~0.95).
- Campaign B + Email ranked second (~0.83).
- Other channels scored below 0.3, showing weak performance.
Final Recommendation:
- Double down on Campaign A + Email — it balances conversion, revenue, and efficiency.
- Use Campaign B + Email as a secondary strategy for promotions.
- Reduce spend on Instagram and Web Banner for acquisition; they are not cost-effective.


Suggestion: 
- Some strategies that work overall might not be the best at attracting new customers. 
- Segmenting by customer type helps us uncover which message and channel combinations were most effective for first-time buyers, exactly what the client cares about.

 
source: Forage 
