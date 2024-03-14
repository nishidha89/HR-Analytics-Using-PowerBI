# HR-Analytics-Using-PowerBI

The project aims to design a Power BI dashboard to track employee data for HR team which includes working hours,attendence,leaves for three months(April,May,June). The goal is to provide insights into attendence patterns and to differentiate between Work From Home (WFH) and Work From Office (WFO) percentages.

## Steps followed

### Understanding problem:
 Defined the scope of the analysis, focusing on attendance patterns,WFH and sick leave percentages.

### Data Gathering and Transformation:
Collected the attendance data from the provided Excel file.
Cleaned and transformed the data into a suitable format for analysis which includes renaming columns, unpivoting(converting columns into rows), changing datatypes.
Created a parameter to select the desired data based on a specific condition
All the steps are encapsulated into the function whoch will be resused for future sheets and data.
Load and apply the cleaned data into PowerBI

### Creating Metrics using DAX:
Using DAX functions like count,sum,calculate,if,switch,divide and Date-Time to create measures and columns to explore clean data 

### Dashboarding with Power BI Desktop:
Utilized Power BI Desktop to visualize the data and create interactive dashboards.
Created a seperate measure table to include all the measures.
Used filters to filter the data and charts for visualizations.

### Project Outcome:
By analysing data through visualizations in dashboard it has been observed that according to months as June is approaching presence percentage is declining, WFH % is increasing, Sick Leave percentage is little bit increasing because of hot summer months
If we have software releases for client across June then we can do release planning accordingly as the presence percentage capacity for June is lower compared to other months.
