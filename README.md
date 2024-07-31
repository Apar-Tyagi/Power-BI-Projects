# Profession Survey Breakdown


## Introduction: 
This Power BI project presents an analysis of a survey conducted among data professionals to understand various aspects of their careers, including career switches, salaries, industries, programming languages, and job satisfaction. The goal is to extract insights and trends from the survey data to gain a better understanding of the data professional landscape.

## Data Source 
The dataset used for this analysis contains responses from data professionals in various fields, detailing their career journeys and preferences.

## Data Cleaning
Data Cleaning was done by Tranforming the data in Power BI. 
1. Checked for data types i.e: for date and time 
2. Filter out irrelavant data values by splitting values with delimiter:

   a. Remove row text other than word 'options'
   
   b. Delete irrelevant columns
   
4. As in each row current salary is provided with ranges so:
   
   a. Split values with delimiter
   
   b. Find average of two ranges with custom column
   
   c. Remove unwanted colunms

## Data Visualization 
To understand the data professional landscape, I created a comprehensive dashboard using Power BI. The dashboard showcases the results of Data Professional Survey Breakdown, providing fascinating insights into various aspects of the industry.

1. Cards to represent unique metrics like: Count of Survey Takers and Average Age of Survey Taker 
2. The Treemap to represents the distribution of survey takers across different countries
3. The stacked bar chart for average salary by job title sheds light on the earning potential within the field
4. Column chart that illustrates the distribution of votes for programming languages among different job titles
5. Donut chart to categorize the difficulties faced by aspiring data professionals
6. Gauges to measure happiness levels in current positions. One gauge evaluates work/life balance, while the other assesses satisfaction with salary


             <img width="509" alt="Snapshot" src="https://github.com/user-attachments/assets/edb0b246-8f36-403e-9f35-4c58502d829e">

