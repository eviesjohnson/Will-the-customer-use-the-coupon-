# Coupon Acceptance Analysis

This project explores coupon acceptance rates based on various factors such as destination, time of day, habits, and demographics. The analysis is conducted using Python in a Jupyter Notebook and includes visualizations to highlight key findings.

## Project Organization

- **README.md**: This file provides an overview of the project, key findings, and links to the main notebook.
- **notebooks/**:
  - `Willthecustomeropenthecoupon.ipynb`: The Jupyter Notebook containing all the analysis, visualizations, and formatted text.
- **data/**:
  - `coupons.csv`: The dataset used in the analysis, cleaned and ready for processing.

## Summary of Findings

1. **Overall Acceptance Rates**:
   - The average acceptance rate varies significantly across different coupon types. Bar coupons had the lowest acceptance rate, carry out coupons had the highest, followed by inexpensive restaurants. 
     

2. **Factors Influencing Acceptance**:
   - **Time of Day**: Morning times (7AM and 10AM) had lower acceptance rates of coffee house coupons compared to afternoon times (2PM).
   - **Destination**: Drivers with no urgent place to go were more likely to accept coffee house coupons than those who were going to work or home.
   - **Habits**: People who went to bars more than 3 times a month were much more likely to accept bar coupons than those who went fewer than 3 times a month.

3. **Specific Insights**:
   - Coupons for Coffee Houses showed a strong correlation with time of day and destination.
   - Acceptance rates for Grocery coupons were consistently low across all demographics.

## Repository Structure

