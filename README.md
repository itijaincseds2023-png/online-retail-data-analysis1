# online-retail-data-analysis1
Data analysis of the UCI Online Retail II dataset using Python, Pandas and Looker Studio.
# Online Retail Data Analysis

## Project Overview

This project analyzes the Online Retail II dataset to understand sales performance, product performance, country-wise revenue, customer contribution, and cancellation/return patterns.

## Dataset

- Dataset: Online Retail II
- Source: UCI Machine Learning Repository
- Records: 1,067,371
- Columns: 8
- Period: December 2009 to December 2011

## Business Problem

The objective is to identify sales opportunities, performance gaps, trends, and cancellation/return patterns that can help support better business decisions.

## Data Processing

The data was processed using Python and Pandas.

Main processing steps:
- Removed exact duplicate records
- Handled missing descriptions
- Identified missing Customer IDs
- Identified cancellation/return transactions
- Created Sales Value = Quantity × Price
- Prepared analysis-ready data

## Key Findings

1. November was the strongest revenue period in both years.
2. The UK generated the highest revenue.
3. A small number of products generated substantially higher revenue.
4. Revenue was concentrated among high-value customers.
5. Cancellation activity was higher in certain periods.

## Recommendations

1. Prepare inventory and marketing ahead of November.
2. Focus retention efforts on high-value customers.
3. Investigate products and periods with high cancellation activity.

## Dashboard

[View Looker Studio Dashboard](https://datastudio.google.com/s/gw2dubRLrcg)

## Presentation

The project presentation is included in this repository.

## Limitations

- Many transactions have missing Customer IDs.
- Negative-quantity transactions require separate treatment.
- December 2011 contains only partial-month data.

## Tools Used

- Python
- Pandas
- Google Sheets
- Looker Studio
- Microsoft PowerPoint
