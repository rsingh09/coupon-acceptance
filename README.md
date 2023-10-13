# Coupon-Acceptance
Exploratory data analysis to see if a driver will accept the coupon and take a detour to the restaurant/bar

## 1: Data Analysis and cleaning

The dataset used for this analysis is stored in a file named [data.csv]. The dataset consists of several columns, including driver and passenger details like age, occupation, income etc. and column 'Y' (which represents acceptance of coupon).

To prepare the data for analysis, we performed the following steps:

1. Replaced 'below21' with '20' and '50plus' with '50' in the 'age' column to make it numeric.
2. Converted the 'age' column to integers.
3. Conducted several queries to filter and segment the data based on specific criteria, such as 'Bar' frequency, passenger type, marital status, and income.

## Analysis

The analysis consists of following queries for bar data:

### Query 1
- Focuses on drivers who go to bars more than once a month, are not with 'Kid(s)', and are not 'Widowed'. It calculates the acceptance rate for this group.

### Query 2
- Examines drivers who go to bars more than once a month and are younger than 30. It calculates the acceptance rate for this group.

### Query 3
- Filters for drivers who visit restaurants with '4~8' or 'gt8' ratings and have income levels within specific salary ranges. It calculates the acceptance rate for this group.
