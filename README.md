# Coupon-Acceptance
Exploratory data analysis to see if a driver will accept the coupon and take a detour to the restaurant/bar

## 1: Data Analysis and cleaning

The dataset used for this analysis is stored in a file named [data.csv]. The dataset consists of several columns, including driver and passenger details like age, occupation, income etc. and column 'Y' (which represents acceptance of coupon).

To prepare the data for analysis, we performed the following steps:

1. Replaced 'below21' with '20' and '50plus' with '50' in the 'age' column to make it numeric.
2. Converted the 'age' column to integers.
3. Conducted several queries to filter and segment the data based on specific criteria, such as 'Bar' frequency, passenger type, marital status, and income.

## Analysis

## Coupon Acceptance Rate

We calculated the proportion of total observations that accepted coupons, which was found to be approximately 56.84%. A bar plot was created to visualize the distribution of accepted and non-accepted coupons.

## Analysis on Bar Coupons

The analysis focused on bar-related coupons. We calculated the proportion of accepted bar coupons and compared the acceptance rates based on how often people visited bars and their age. We also compared acceptance rates based on passenger presence and occupation.


## Analysis on the Basis of Destination

We analyzed coupon acceptance based on the destination, identifying that non-urgent destinations tended to have higher acceptance rates. Additionally, we analyzed the influence of coupon type on acceptance.

## Analysis of Coffee House Coupons

The acceptance rates of coffee house coupons were examined based on various factors, including the frequency of visits and the presence of passengers. These insights provide a better understanding of coffee house coupon acceptance.

## Conclusions

Based on the observations and analyses, we made various hypotheses about drivers who accept different types of coupons. For example, drivers who visit bars more frequently tend to accept bar coupons, while drivers with children as passengers tend to have lower acceptance rates.

