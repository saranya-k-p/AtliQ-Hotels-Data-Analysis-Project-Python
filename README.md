# AtliQ Grands Hotel Data Analysis-Project-Python

## Project Overview
This project was part of the Codebasics Data Analyst course. AtliQ Grands, a fictional hotel chain, operates in major Indian cities and has recently been facing declining revenue due to increasing competition. The objective of this project was to analyze booking data using **Python** to support data-driven decision-making that can help improve revenue and regain market share.

## Business Problem
After operating in the hospitality industry for over 20 years, AtliQ Grands has started losing its market share due to strong competition from other hotel chains. The management aims to use data analysis to understand booking patterns, revenue trends, and customer behavior in order to regain a competitive advantage.

## Project Goal
The goal of this project was to analyze booking and revenue data to uncover trends, understand customer behavior, and evaluate booking platform performance. These insights can support decisions that improve revenue generation and strengthen the company’s market position.

## Company Details
AtliQ Grands operates hotels in major Indian cities such as **Delhi, Mumbai, Bangalore, and Hyderabad**. The company offers multiple hotel brands and room categories to cater to different customer segments. Customers can book rooms through the company’s website as well as several third-party booking platforms.

## Tools Used
- Python
- Pandas
- Jupyter Notebook

## Project Workflow
- Data Cleaning  
- Data Transformation  
- Exploratory Data Analysis (EDA)  
- Visualization of Findings  

## Key Insights

- Presidential rooms (RT4) have the highest average occupancy rate (59.30%), while other room categories maintain occupancy around 58%.
- Delhi shows the highest average occupancy (62.47%), indicating strong demand.
- Bangalore has the lowest occupancy (56.58%), suggesting potential opportunities for demand improvement.
- Weekend occupancy (72.39%) is significantly higher than weekday occupancy (50.90%).
- Mumbai generates the highest revenue (₹668M) among all cities.
- May 2022 recorded the highest monthly revenue, followed by July and June.

## Technical Approach

- Used `shape`, `head`, `tail`, and `columns` to understand dataset structure  
- Applied `describe`, `mean`, `std`, and `round` to summarize numerical data  
- Used `unique` and `value_counts` to identify categories and platforms  
- Applied `lambda` to format occupancy percentage (×100, rounded to 2 decimals)  
- Used `groupby` to analyze patterns by city, category, and time  
- Merged datasets using `merge` for deeper insights  
- Ensured consistent date formatting for time-based analysis  
- Created bar charts (vertical & horizontal) for visualization  


## Business Recommendations
1. Delhi Strategy:  
   - Despite high occupancy, Delhi’s revenue per city is low.  
   - Review pricing and upscale packages to drive higher revenue.  
   - Maintain and strengthen customer experience and service quality to sustain high occupancy.

2. Bangalore Deep Dive:  
   - Bangalore shows decent revenue, but low occupancy.  
   - Analyze which room categories or customer segments are less booked and adjust offerings accordingly.

3. Premium Focus:  
   - Leverage the success of presidential rooms by boosting demand for elite and premium categories through targeted marketing.

4. Weekday Occupancy Boost:  
   - Introduce business-focused packages (e.g., meeting rooms, co-working) to drive weekday bookings.

5. Monthly Revenue Planning:  
   - Identify reasons for June’s dip and replicate successful strategies from May and July.

6. Dynamic Pricing:  
   - Implement dynamic pricing strategies for weekends to maximize revenue during high-demand periods.  
   - Adjust pricing and marketing strategies based on seasonal demand patterns.


## Business Impact

- Increased overall revenue through optimized pricing strategies.  
- Improved occupancy rates in underperforming cities.  
- Better revenue realization from premium room categories.  
- Stronger market competitiveness in high-performing cities.  
- More effective seasonal planning for marketing and operations.
