Case Study: Analyzing Customer Churn in PowerBI

Description: In this Power BI case study, I have investigated a dataset from an example telecom company and analyzed why customers are leaving. Analyzing churn doesn't just mean knowing what the churn rate is but also figuring out why customers are churning at the rate they are.

Tech Stack: The Report is built using 
📊 Power BI Desktop - Main data visualization platform used for report creation.
🧠 DAX (Data Analysis Expressions)- Used for Calculated measures, dynamic visuals, and conditional logic.

Data Source: The data source used for this analysis is a CSV dataset obtained from Datacamp's couse Case Study.

---------------------------------------------------------------------------
Steps involved in Data Analysis Flow in Power BI:
---------------------------------------------------------------------------
1- Data Check: Check for duplicates or missing values and do a sense check with other internal data sources.
2- Explore Data: Ask yourself the right questions and build your first visualization.
3- Analyze and visualize data: Choose the right visualization to convey a message and perform more advanced analysis.
4- Dashboarding: Combine visualizations in one or more dashboards.
5- Communicate Insight with stakeholders.

------------------------------------------------------------------------
Analyzing Customer Churn Power BI report have multiple pages. Below is the description for 'Overview of ChurnRate' and 'Overall Insights' pages:
--------------------------------------------------------------------------
OVERVIEW OF CHURNRATE:
In this page I have used 'card' visual to show 'Number of customers', 'Number of Churned customers' and 'churn rate'. Used 'Donut' chart to see the percentage of customers for each contract type and used pie-chart to see the percentage of churned customers for each churn category. Finally using 'map' visual I tried to see how churn rate is for each state. For the Bubble size, I have used 'churn rate' so that visually we can tell which state has the highest or lowest churn rate.
!(https://github.com/nikitha-learning98/PowerBIReports/blob/main/Overall%20Insight.png)
OVERALL INSIGHTS:
In this page I have used card visual to show 'customer service calls', 'International Charges' and 'Data Charges' and used a slicer for 'contract category' [Monthly or yearly]  and 'payment method'[Credit card, debit card , paper check] using clusterd bar chart I am visualizing churn rate based on the grouped consumption and unlimited data plan and we see that churn rate is more for customers who have unlimited data plan and who are consuming less then 5 GB. Using Line chart I have visualized average customer service calls by state and Churn Label [Yes-Churned, No- NOt Churned] and we can observe that customers who have churned has the highest customer calls than the other customers. Using map visual I have visualized the customer service calls for eaxh state by applying conditional formatting to Bubble color [For minimum customer calls to maximum customer calls].

