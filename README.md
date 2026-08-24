# Yulu Case Study: Analysing Demand for Shared Electric Cycles

## Project Overview

This project analyses Yulu bike rental data to identify the key factors influencing demand for shared electric cycles. The objective is to provide data-driven insights that can help Yulu improve fleet management, marketing, pricing, and demand forecasting.

## Dataset

The dataset contains information about:

* Temperature and humidity
* Wind speed
* Season
* Weather conditions
* Holiday and working day status
* Casual and registered users
* Total bike rentals

## Analysis Performed

* Data loading and initial exploration
* Missing value and duplicate checks
* Descriptive statistics
* Univariate and bivariate analysis
* Outlier detection using IQR
* Correlation analysis
* Hypothesis testing
* Seasonal and weather-based demand analysis

## Key Findings

* No missing values or duplicate records were found.
* Temperature has a positive relationship with bike demand, while humidity has a negative relationship.
* There is no significant difference in average rentals between working days and weekends/holidays.
* Average daily demand is approximately **188.70 rentals**, significantly below the target of 500.
* High-demand days have an average temperature of approximately **24.69°C**.
* Weather conditions are significantly related to seasons.
* Bike demand varies significantly across seasons, with **Fall and Summer** showing higher demand.
* Demand also varies significantly by weather, with **clear weather** producing the highest demand.

## Hypothesis Testing

The following statistical tests were performed:

| Analysis                         | Test               | Result          |
| -------------------------------- | ------------------ | --------------- |
| Weekdays vs. Weekends            | Independent T-test | Not significant |
| Average Demand vs. 500           | One-Sample T-test  | Significant     |
| Temperature on High-Demand Days  | One-Sample T-test  | Significant     |
| Weather vs. Season               | Chi-Square Test    | Significant     |
| Demand Across Seasons            | One-Way ANOVA      | Significant     |
| Demand Across Weather Conditions | One-Way ANOVA      | Significant     |

## Recommendations

1. Adjust fleet availability based on seasonal and weather-based demand.
2. Use targeted promotions during low-demand periods.
3. Consider flexible pricing during peak and off-peak periods.
4. Improve bike durability and maintenance for different weather conditions.
5. Set more realistic rental targets based on current demand.
6. Further segment casual and registered users for targeted marketing.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* gdown

## Conclusion

The analysis shows that **season, weather, temperature, and humidity** significantly influence Yulu's bike rental demand. These insights can help Yulu optimize fleet allocation, marketing campaigns, pricing strategies, and demand targets.
