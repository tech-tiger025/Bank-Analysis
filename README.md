# Bank Marketing Campaign Analysis

## Overview
This project analyzes customer data collected during a marketing campaign by a bank. It aims to uncover key factors influencing customer subscription behavior through data exploration, statistical analysis, and visualization techniques.

## Features
- **Data Cleaning**: Ensures data quality by removing duplicates and handling missing values.
- **Exploratory Data Analysis (EDA)**: Provides insights into customer demographics, financial profiles, and subscription trends.
- **Statistical Analysis**: Validates hypotheses using techniques like Chi-Square and T-Tests.
- **Visualizations**: Includes histograms, bar charts, and other graphs to illustrate findings clearly.

## Dataset Information
- **Rows**: 49,732 entries
- **Columns**: 17 features, including `age`, `job`, `balance`, `duration`, and `subscription outcome (y)`
- Source: Provided as a CSV file.

## Key Insights
### 1. Demographics
- **Age**: Subscriptions peak among younger (<30 years) and older (>60 years) customers.
- **Education**: Higher education correlates with higher subscription rates.
- **Job Types**: Management and technician roles show high subscription likelihood.

### 2. Financial Profiles
- **Account Balance**: High balances increase subscription likelihood.
- **Loan Status**: Customers without housing or personal loans are more likely to subscribe.

### 3. Campaign Interaction
- **Call Duration**: Longer calls correlate with higher subscriptions.
- **Timing**: Subscriptions are higher during May and at the beginning of the month.

### 4. Historical Campaign Outcomes
- Customers who responded positively in past campaigns are more likely to subscribe again.

## Technologies Used
- **Python**: Analysis and data manipulation.
  - Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`
- **Statistical Tests**: Chi-Square, T-Test, ANOVA
- **Data Visualization**: Graphs to explore trends and relationships.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/bank-marketing-analysis.git
