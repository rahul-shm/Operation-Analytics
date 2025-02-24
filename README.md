# Operation Analytics and Investigating Metric Spike

## Repository Structure
This repository is organized into the following files:
- **Datasets**: Contains data files with descriptions as their respective use case, used for analysis.
- **Report**: Provides the final presentation/report summarizing findings and insights.

---

## Project Overview
Operational Analytics involves analyzing a company’s end-to-end operations to identify areas for improvement. A key aspect of this is investigating metric spikes—understanding and explaining sudden changes in key metrics like user engagement drops or sales fluctuations.

As a Lead Data Analyst at a company like Microsoft, this project focuses on using **Advanced SQL** techniques to analyze datasets, derive insights, and provide valuable recommendations to different departments within the company.

---

## Tasks and SQL Analysis

### Case Study 1: Job Data Analysis

1. **Jobs Reviewed Over Time**
   - **Objective**: Calculate the number of jobs reviewed per hour for each day in November 2020.
   - **Approach**: Extract and aggregate job review events based on timestamps.
   - **SQL Query**: Provided in the `Solution` folder.
   - **Insights**: Identify peak review times for process optimization.

2. **Throughput Analysis**
   - **Objective**: Compute a 7-day rolling average of throughput (number of events per second).
   - **Approach**: Use window functions to calculate rolling averages.
   - **SQL Query**: Provided in the `Solution` folder.
   - **Insights**: Compare daily vs. rolling averages for performance assessment.

3. **Language Share Analysis**
   - **Objective**: Calculate the percentage share of each language in the last 30 days.
   - **Approach**: Aggregate data by language and calculate proportional shares.
   - **SQL Query**: Provided in the `Solution` folder.
   - **Insights**: Identify dominant languages to optimize localization efforts.

4. **Duplicate Rows Detection**
   - **Objective**: Identify duplicate rows in the dataset.
   - **Approach**: Use `GROUP BY` and `HAVING` clauses to detect duplicates.
   - **SQL Query**: Provided in the `Solution` folder.
   - **Insights**: Ensure data integrity by detecting redundant records.

---

### Case Study 2: Investigating Metric Spike

1. **Weekly User Engagement**
   - **Objective**: Measure the activeness of users on a weekly basis.
   - **Approach**: Aggregate event data per user weekly.
   - **SQL Query**: Provided in the `Solution` folder.
   - **Insights**: Understand user engagement trends over time.

2. **User Growth Analysis**
   - **Objective**: Analyze user growth over time for a product.
   - **Approach**: Track new user signups per time period.
   - **SQL Query**: Provided in the `Solution` folder.
   - **Insights**: Identify growth patterns to inform marketing strategies.

3. **Weekly Retention Analysis**
   - **Objective**: Measure user retention based on signup cohorts.
   - **Approach**: Use cohort analysis to track user return rates.
   - **SQL Query**: Provided in the `Solution` folder.
   - **Insights**: Evaluate long-term user retention for product improvements.

4. **Weekly Engagement Per Device**
   - **Objective**: Measure user engagement per device type.
   - **Approach**: Group engagement data by device category.
   - **SQL Query**: Provided in the `Solution` folder.
   - **Insights**: Understand device-specific engagement trends.

5. **Email Engagement Analysis**
   - **Objective**: Analyze how users interact with emails.
   - **Approach**: Track email open and click-through rates.
   - **SQL Query**: Provided in the `Solution` folder.
   - **Insights**: Optimize email campaigns based on engagement metrics.

---

## Approach and Execution
1. **Database Setup**: Imported the sample datasets into MySQL Workbench.
2. **Query Writing**: Developed and tested SQL queries for each analysis task.
3. **Analysis**: Extracted insights from query outputs.
4. **Documentation**: Compiled findings into a report for stakeholders.

---

## Tech-Stack Used
- **MySQL Workbench**: Used for SQL execution and database management.
- **SQL**: Primary tool for querying and analyzing data.
- **Microsoft PowerPoint / Word**: Used for the final report presentation.

---

## Insights and Learnings
- **Operational Efficiency**: SQL-driven insights optimize business processes.
- **Data Validation**: Detecting anomalies like metric spikes improves data quality.
- **User Behavior Analysis**: Identifying engagement trends informs decision-making.
- **Marketing Optimization**: Understanding email and user growth metrics improves strategy.

---

## Results and Impact
- **Improved Operational Processes**: Data-driven insights optimize workflows.
- **Enhanced Decision-Making**: Clear, actionable insights support strategic choices.
- **Stakeholder Confidence**: Transparent data analysis builds trust with leadership teams.
