# Chicago_Case_Study-IBM-Databases-And-SQL-for-Data-Science

## Assignment Instructions

In this assignment, download the datasets provided, load them into a database, write and execute SQL queries to answer the problems provided.

This assignment involves 3 datasets for the city of Chicago obtained from the Chicago Data Portal:

1. Chicago Socioeconomic Indicators

This dataset contains a selection of six socioeconomic indicators of public health significance and a hardship index, by Chicago community area, for the years 2008 – 2012.

2. Chicago Public Schools

This dataset shows all school level performance data used to create CPS School Report Cards for the 2011-2012 school year.

3. Chicago Crime Data

This dataset reflects reported incidents of crime (with the exception of murders where data exists for each victim) that occurred in the City of Chicago from 2001 to present, minus the most recent seven days.

## Instructions:

### 1. Review the datasets

Before you begin, you will need to become familiar with the datasets. Download the three datasets in .CSV format:

•	Chicago Socioeconomic Indicators 
•	Chicago Public Schools 
•	Chicago Crime Data

NOTE: Ensure you have downloaded the datasets using the links provided instead of directly from the Chicago Data Portal. The versions linked here are subsets of the original datasets and have some of the column names modified to be more database friendly which will make it easier to complete this assignment. The CSV file provided above for the Chicago Crime Data is a very small subset of the full dataset available from the Chicago Data Portal. The original dataset is over 1.55GB in size and contains over 6.5 million rows. For the purposes of this assignment data used is a much smaller sample with only about 500 rows.

### 2. Load the datasets into a database

Perform this step using the LOAD tool in the Db2 console. You will need to create 3 tables in the database, one for each dataset, named as follows, and then load the respective .CSV file into the table:

1.	CENSUS_DATA
2.	CHICAGO_PUBLIC_SCHOOLS
3.	CHICAGO_CRIME_DATA

### 3. Write and execute queries

Perform this step in the Jupyter notebook provided. Carefully read and understand each problem. Compose and execute the appropriate SQL queries to answer each of the problems. Take a screenshot of each query and its results and save it as a jpg file..

Problem 1: Find the total number of crimes recorded in the CRIME table.

Problem 2: List community areas with per capita income less than 11000.

Problem 3: List all case numbers for crimes involving minors?

Problem 4: List all kidnapping crimes involving a child? (children are not considered minors for the purposes of crime analysis)

Problem 5: What kind of crimes were recorded at schools?

Problem 6: List the average safety score for all types of schools.

Problem 7: List 5 community areas with highest % of households below poverty line.

Problem 8: Which community area(number) is most crime prone?

Problem 9: Use a sub-query to find the name of the community area with highest hardship index.

Problem 10: Use a sub-query to determine the Community Area Name with most number of crimes?
