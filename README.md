# Customer Support Dashboard

![CustomerSupportDashV2](https://github.com/user-attachments/assets/37dcc2be-47e4-4974-a128-0d4971822d96)

## Introduction
This Power BI dashboard is designed to provide a comprehensive view of customer support operations by analyzing complaints and support tickets. Through interactive and dynamic visualizations, the dashboard offers insights into key metrics such as ticket types, products, subjects, communication channels, priorities, and customer satisfaction levels.

The main goal is to identify patterns, uncover areas for improvement, and support data-driven decision-making to enhance the overall customer experience. This tool is especially valuable for customer service teams, product managers, and any stakeholders looking to better understand customer feedback.

The dataset used for this project is sourced from [Kaggle](https://www.kaggle.com/datasets/suraj520/customer-support-ticket-dataset)

## Project Insights
- **Total Tickets:** Total number of tickets created. Quarter trends included for the selected year
- **Closed:** Total number of closed tickets. Quarter trends included for the selected year
- **Open:** Total number of open tickets. Quarter trends included for the selected year
- **Pending Response:** Total number of tickets awaiting customer response. Quarter trends included for the selected year
- **Days to First Contact:** Days between the purchase of a product and the first response from the customer support. Quarter trends included for the selected year
- **Top 5 Tickets Created by Subject:** Bar chart to display top 5 subjects that have the most tickets created
- **Top 5 Tickets Created by Type:** Bar chart to display top 5 types that have the most tickets created
- **Top 10 Tickets Created by Products:** Bar chart to display top 10 products that have the most tickets created
- **Customer Satisfaction:** Gauge chart to display the average customer satisfaction once the ticket is closed
- **Tickets by Channel:** Donut chart to display the distribution of tickets created based on the communication channel

  ## Installation
  You can access this dashboard by:
    1. Download Power BI Desktop
    2. Download [Customer Support Dashboard](main/CustomerSupportDashboard.pbix)
    3. Open the dashboard on Power BI Desktop
 
## Next Steps
  1. Adding countries or states to the dataset and building a map
  2. Adding tickets creation time to:
     - Analyze TTFR (time to first response) from the customer support agent
     - Analyze TRT (time to resolution) from the customer support agent
  3. Adding Time Intelligence functions to the scorecards to enhance the KPI visuals
