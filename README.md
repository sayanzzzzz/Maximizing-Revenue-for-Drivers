# Maximizing Revenue for Taxi Drivers Using Payment Type Analysis

## Project Overview

This project analyzes NYC taxi trip data to understand the relationship between payment methods and fare amounts. The objective is to identify customer payment preferences, examine differences in trip characteristics, and develop data-driven recommendations that could help taxi drivers maximize their revenue.

Using Python for data cleaning, exploratory data analysis (EDA), statistical analysis, and hypothesis testing, this project investigates whether card and cash transactions differ in terms of average fare amount, trip distance, and passenger count.

## Problem Statement

In the competitive taxi booking industry, maximizing driver revenue is essential for sustainable earnings and business performance. This project investigates whether payment methods influence fare amounts and explores how customer payment preferences can be used to identify potential revenue opportunities.

The analysis focuses on understanding the relationship between payment type and total fare amount while considering trip distance and passenger count.

## Research Questions

1. Is there a relationship between total fare amount and payment type?
2. Do customers paying by card have different average fare amounts compared with customers paying by cash?
3. What are the payment preferences of taxi customers?
4. How do passenger count and trip distance vary across payment methods?
5. What strategies could encourage payment methods associated with higher average fares while maintaining a positive customer experience?

## Tools and Technologies Used

| Tool / Library | Purpose |
|---|---|
| Python | Data analysis and implementation of the analytical workflow |
| Jupyter Notebook | Writing, executing, and documenting analysis code |
| Pandas | Data manipulation, data cleaning, and tabular analysis |
| NumPy | Numerical operations and statistical calculations |
| Matplotlib | Data visualization |
| Seaborn | Statistical plots and exploratory data visualization |
| SciPy | Statistical analysis and hypothesis testing |
| Statsmodels | Statistical analysis and Q-Q plots |
| Exploratory Data Analysis (EDA) | Identifying patterns, distributions, and relationships in the data |

## Dataset Overview

The project uses NYC Taxi Trip records. Data cleaning and feature engineering were performed to focus on the variables relevant to the research questions.

### Key Variables

- **Passenger Count:** Number of passengers in a trip, analyzed for counts ranging from 0 to 5.
- **Payment Type:** Payment method used by the customer, categorized as Cash or Card.
- **Fare Amount:** Fare charged for the trip.
- **Trip Distance:** Distance covered during the trip.
- **Trip Duration:** Duration of the trip in minutes.

## Project Workflow

### 1. Data Preparation and Cleaning

- Loaded the NYC taxi trip dataset into Python.
- Performed data cleaning to prepare the dataset for analysis.
- Selected relevant columns required to investigate payment preferences and fare behavior.
- Applied feature engineering where necessary to support the analysis.

### 2. Exploratory Data Analysis (EDA)

Performed descriptive and exploratory analysis to understand customer behavior and trip characteristics.

The analysis examined:

- Distribution of fare amounts.
- Customer preferences for card and cash payments.
- Average fare amounts and trip distances across payment methods.
- Passenger count patterns across different payment types.
- Distribution of data using histograms and Q-Q plots to examine normality.

### 3. Statistical Analysis

Compared fare-related characteristics across payment types to investigate whether card and cash transactions exhibit different patterns.

Descriptive statistics were used to summarize the data and identify differences in average fare amounts and trip distances.

### 4. Hypothesis Testing

A two-sample t-test was conducted to evaluate whether the average fare amount differs between card and cash transactions.

**Null Hypothesis (H₀):** There is no difference in the average fare amount between customers who pay by card and customers who pay by cash.

**Alternative Hypothesis (H₁):** There is a difference in the average fare amount between customers who pay by card and customers who pay by cash.

**Significance level:** 0.05

The analysis reported a t-statistic of 165.5 and a p-value below 0.05. Therefore, the null hypothesis was rejected, indicating a statistically significant difference in average fare amounts between the two payment methods.

## Key Findings

### 1. Customer Payment Preferences

- Card payments accounted for **67.5%** of transactions.
- Cash payments accounted for **32.5%** of transactions.
- Card payments were the more commonly used payment method in the analyzed dataset.

### 2. Fare Amount and Trip Distance

- Customers paying by card tended to have slightly higher average fare amounts.
- Card transactions also tended to have slightly higher average trip distances.
- These patterns suggest an association between payment type, trip characteristics, and fare amounts. They do not establish that the payment method itself causes higher fares.

### 3. Passenger Count Analysis

- Single-passenger rides represented **40.08% of all card transactions**.
- Single-passenger rides represented **20.04% of all cash transactions**.
- The proportion of transactions decreased as passenger count increased, highlighting the importance of passenger count when examining customer and payment behavior.

### 4. Hypothesis Testing Results

- **T-statistic:** 165.5
- **P-value:** Below 0.05
- **Decision:** Reject the null hypothesis.
- **Conclusion:** The analysis found a statistically significant difference in average fare amounts between card and cash transactions.

Statistical significance does not necessarily imply that the difference is large in practical or business terms. The result also does not demonstrate that encouraging card payments will independently increase driver revenue.

## Business Recommendations

Based on the findings, the following strategies could be considered:

1. **Promote convenient card payments:** Make card payment options accessible, secure, and easy to use for customers.
2. **Evaluate customer incentives:** Test targeted offers or payment incentives to determine whether they increase card adoption without reducing overall driver earnings.
3. **Monitor fare and trip characteristics:** Track average fare amounts, trip distances, and payment preferences to understand revenue patterns.
4. **Use data-driven decision-making:** Regularly analyze transaction data to identify changes in customer behavior and payment preferences.
5. **Measure business impact:** Compare revenue, transaction costs, and driver earnings before and after any payment-related initiative to assess whether it delivers measurable benefits.

These recommendations should be validated through further analysis or controlled experiments before implementation.

## Skills Demonstrated

- Python programming for data analytics
- Data cleaning and feature engineering
- Exploratory data analysis
- Descriptive statistics
- Data visualization
- Statistical hypothesis testing
- Interpretation of statistical results
- Customer behavior analysis
- Business problem-solving
- Translating data insights into business recommendations

## Conclusion

This project demonstrates how Python-based data analytics can be used to investigate customer payment behavior and its relationship with taxi fare amounts.

The analysis identified a higher proportion of card transactions, differences in average fare amounts between payment types, and distinct passenger count patterns. Hypothesis testing further indicated a statistically significant difference in average fares between card and cash transactions.

The findings provide a starting point for understanding payment preferences and developing data-driven strategies to support taxi driver revenue optimization.


**Note:** The dataset itself must be available locally, and its file path may need to be updated to match your environment.

