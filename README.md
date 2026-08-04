# ConnectaTel: Customer Usage and Segmentation Analysis

## Executive Summary

ConnectaTel needed to better understand how its customers used mobile services and whether different user groups showed distinct needs, usage patterns, plan behavior, or churn risk.

I analyzed customer, plan, and service-usage data using Python. The project included data-quality validation, descriptive statistics, outlier review, visualization, and customer segmentation.

The analysis was designed to transform raw telecom data into practical insights that could support customer-experience improvements, plan optimization, and more targeted commercial strategies.

## Business Problem

The project focused on the following business questions:

- How do customers use calls, messages, and mobile services?
- Are there meaningful differences between customer groups?
- Which plans are associated with different usage behaviors?
- Are there data-quality problems that could affect business conclusions?
- Which customer segments may require differentiated offers or retention actions?

The objective was to identify actionable customer profiles rather than treat all users as a single homogeneous group.

## Data Sources

The analysis used three datasets:

### `plans.csv`

Contains information about the available mobile plans, including:

- Plan price
- Included benefits
- Plan characteristics
- Service allowances

### `users_latam.csv`

Contains customer information, including:

- Customer attributes
- Subscribed plan
- Registration date
- Churn status

### `usage.csv`

Contains customer-activity information, including:

- Calls
- Messages
- Service duration
- Usage frequency
- Activity period

## Analytical Workflow

### 1. Data Exploration

I reviewed:

- Dataset dimensions
- Column types
- Missing values
- Duplicate records
- Numerical distributions
- Categorical consistency

### 2. Data-Quality Validation

The datasets were evaluated for:

- Null values
- Sentinel values
- Invalid or out-of-range dates
- Unexpected categories
- Potential outliers
- Inconsistent customer records

These checks were necessary to avoid building customer segments from unreliable information.

### 3. Descriptive Analysis

I calculated summary metrics to understand:

- Typical customer usage
- Differences between plans
- Call and message behavior
- Customer activity levels
- Churn-related patterns

### 4. Customer Segmentation

Customers were grouped according to relevant behavioral and service characteristics.

The purpose of the segmentation was to identify groups with different:

- Usage intensity
- Communication preferences
- Plan needs
- Commercial potential
- Retention requirements

### 5. Data Visualization

Visualizations were created to compare:

- Usage distributions
- Customer groups
- Plan behavior
- Outliers
- Activity patterns
- Churn-related differences

## Key Findings

The analysis identified differences in customer behavior and service usage across the available customer profiles.

It also confirmed that data-quality validation was essential before performing segmentation, particularly when working with missing values, sentinel values, inconsistent dates, and potential outliers.

The segmentation provided a clearer view of customer needs and created a foundation for developing more targeted commercial and customer-retention strategies.

> Specific metrics and segment sizes should be taken directly from the final notebook before adding them to this section.

## Business Recommendations

- Design differentiated offers according to customer usage intensity.
- Review whether existing plans align with actual call and messaging behavior.
- Monitor customers with declining activity or churn-related characteristics.
- Use customer segments to improve campaign targeting and communication.
- Strengthen data-validation rules for dates, missing values, and categorical fields.
- Recalculate customer segments periodically as usage behavior changes.

## Tools and Techniques

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Data cleaning
- Descriptive statistics
- Outlier analysis
- Customer segmentation
- Telecom customer analytics

## Visualizations

### Customer Usage Distribution

![Usage Distribution](images/usage_distribution.png)

### Customer Segments

![Customer Segments](images/customer_segments.png)

### Plan Comparison

![Plan Comparison](images/plan_comparison.png)

## Repository Structure

```text
notebooks/  Data preparation, analysis, and customer segmentation
data/       Source datasets
images/     Main visualizations
README.md   Project documentation

