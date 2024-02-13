# Operation-Analytics-and-Investigating-Metric-Spike
OPERATION ANALYTICS AND INVESTIGATING METRIC SPIKE

Project Description
The project "Operation Analytics and Investigating Metric Spike" involves analyzing operational data to investigate spikes in specific metrics. This analysis aims to understand the causes and implications of sudden increases in metrics within a system or process.
Approach
•	Prepare & Analyze
The dataset is initially prepared and analyzed through the utilization of SQL functions such as SELECT, WHERE, GROUP BY, JOIN, among others, to extract pertinent insights from the data. These functions serve to filter, aggregate, and combine data, facilitating the extraction of meaningful information from the dataset for analysis.
•	Identify KPIs
After the completion of data cleaning and transformation, the subsequent stage involves the identification of Key Performance Indicators (KPIs) pertinent to the business. These KPIs encompass metrics such as throughput, user engagement, and user retention, among others, which serve as crucial indicators of business performance and effectiveness.
•	Visualize Data
The concluding phase involves leveraging Tableau to craft interactive charts and dashboards. Tableau serves as a pivotal tool for developing dynamic visualizations, aiding in the discernment of trends and patterns within the data.
Tech-Stack Used

•	Data Collection: Custom scripts, APIs, or data extraction tools depending on the source of data. 
•	Data Preprocessing: Python and MySQL Workbench

Case Study 1: Job Data Analysis
You will be working with a table named job_data with the following columns:

job_id: Unique identifier of jobs
actor_id: Unique identifier of actor
event: The type of event (decision/skip/transfer).
language: The Language of the content
time_spent: Time spent to review the job in seconds.
org: The Organization of the actor
ds: The date in the format yyyy/mm/dd (stored as text).
Tasks:

Jobs Reviewed Over Time:
Objective: Calculate the number of jobs reviewed per hour for each day in November 2020.
Your Task: Write an SQL query to calculate the number of jobs reviewed per hour for each day in November 2020.
Throughput Analysis:
Objective: Calculate the 7-day rolling average of throughput (number of events per second).
Your Task: Write an SQL query to calculate the 7-day rolling average of throughput. Additionally, explain whether you prefer using the daily metric or the 7-day rolling average for throughput, and why.
Language Share Analysis:
Objective: Calculate the percentage share of each language in the last 30 days.
Your Task: Write an SQL query to calculate the percentage share of each language over the last 30 days.
Duplicate Rows Detection:
Objective: Identify duplicate rows in the data.
Your Task: Write an SQL query to display duplicate rows from the job_data table.

Case Study 2: Investigating Metric Spike
You will be working with three tables:

users: Contains one row per user, with descriptive information about that user’s account.
events: Contains one row per event, where an event is an action that a user has taken (e.g., login, messaging, search).
email_events: Contains events specific to the sending of emails.
Tasks:

Weekly User Engagement:
Objective: Measure the activeness of users on a weekly basis.
Your Task: Write an SQL query to calculate the weekly user engagement.
User Growth Analysis:
Objective: Analyze the growth of users over time for a product.
Your Task: Write an SQL query to calculate the user growth for the product.
Weekly Retention Analysis:
Objective: Analyze the retention of users on a weekly basis after signing up for a product.
Your Task: Write an SQL query to calculate the weekly retention of users based on their sign-up cohort.
Weekly Engagement Per Device:
Objective: Measure the activeness of users on a weekly basis per device.
Your Task: Write an SQL query to calculate the weekly engagement per device.
Email Engagement Analysis:
Objective: Analyze how users are engaging with the email service.
Your Task: Write an SQL query to calculate the email engagement metrics.
