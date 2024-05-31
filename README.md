# excel-challenge
---

## Project Title: Crowdfunding Campaign Analysis

### Background

Crowdfunding platforms such as Kickstarter and Indiegogo have grown significantly in popularity since the late 2000s. From independent creators to well-known celebrities, many people utilize crowdfunding to launch new products and generate excitement. However, not every project achieves success. To secure funding, projects must meet or exceed their initial goals, prompting many organizations to analyze past projects to uncover the secrets of successful campaigns. 

In this project, we will analyze a database of 1,000 sample crowdfunding projects to identify hidden trends and provide insights into the factors contributing to campaign success or failure.

### Project Objectives

The primary objectives of this project are to:

1. **Analyze Campaign Outcomes**: Use conditional formatting to visualize the success rates of campaigns.
2. **Calculate Key Metrics**: Derive important metrics such as percent funded, average donation, and categorize campaign data.
3. **Visualize Category and Subcategory Statistics**: Use pivot tables and charts to analyze and visualize campaign performance by category and subcategory.
4. **Evaluate Outcomes Based on Launch Dates**: Assess how the timing of campaign launches affects outcomes.
5. **Analyze Crowdfunding Goals**: Explore the relationship between campaign goals and success rates.
6. **Perform Statistical Analysis**: Summarize and compare the number of backers for successful and unsuccessful campaigns.

### Data Analysis and Methodology

#### Conditional Formatting and Key Metrics

- **Outcome Visualization**: Use conditional formatting to highlight the outcome of each campaign (successful, failed, canceled, live).
- **Percent Funded**: Create a column to calculate the percentage of the funding goal achieved by each campaign, with conditional formatting to visualize ranges.
- **Average Donation**: Calculate the average donation per backer for each campaign.
- **Category Splitting**: Split the combined Category and Sub-Category into separate columns for more detailed analysis.

#### Category and Subcategory Statistics

- **Category Stats**: Create a pivot table to count the number of campaigns by outcome for each category, and visualize with a stacked-column chart filtered by country.
- **Subcategory Stats**: Create a pivot table to count the number of campaigns by outcome for each subcategory, and visualize with a stacked-column chart filtered by country and parent category.

#### Date Conversion

- **Date Created and Ended Conversion**: Convert Unix timestamps in the launched_at and deadline columns to readable date formats.

#### Outcomes Based on Launch Date

- **Pivot Table and Line Chart**: Create a pivot table with campaign outcomes by launch date, and visualize trends with a pivot-chart line graph. Add filters for parent category and year.

#### Crowdfunding Goal Analysis

- **Goal-Based Analysis**: Create a new sheet with columns to analyze campaign outcomes based on different goal ranges.
- **Success, Failure, and Cancellation Rates**: Use COUNTIFS() to count outcomes within each goal range and calculate percentages.
- **Goal vs. Outcome Line Chart**: Create a line chart to show the relationship between campaign goals and their success rates.

#### Statistical Analysis

- **Summary Statistics for Backers**: Create a table to summarize the number of backers for successful and unsuccessful campaigns, including mean, median, minimum, maximum, variance, and standard deviation.
- **Comparison of Variability**: Analyze whether there is more variability in the number of backers for successful or unsuccessful campaigns and interpret the findings.

### Tools and Technologies

- **Software**: Microsoft Excel
- **Techniques**: Data cleaning, conditional formatting, pivot tables, statistical analysis

### Conclusion

This project will provide a comprehensive analysis of crowdfunding campaign data, highlighting key trends and insights that can help identify factors contributing to the success or failure of campaigns. By leveraging data-driven analysis, we aim to uncover strategies that can improve the chances of success for future crowdfunding projects.

### Future Work

Future analyses could expand to include:
- Longitudinal studies tracking campaign performance over time
- Additional metrics such as social media engagement and project updates
- Predictive modeling to forecast campaign success based on current trends

