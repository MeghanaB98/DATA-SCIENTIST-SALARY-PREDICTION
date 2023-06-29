<h1 align="center">Data Scientist Job Dataset Analysis</h1>

## Abstract

The major purpose of this project is to examine the data scientist job dataset and extract useful information about the technologies required in the data science business, as well as the compensation ranges for various positions.

## Data

The dataset includes the following information:

- Company
- Job title
- Salary
- Rating
- Size
- Founded
- Type of ownership
- Industry
- Revenue
- Average salary
- Age
- Technologies
- Degree

## Analysis

Visualizations are drawn to show the relationship between each category as mentioned with inference.

### Sunburst Visualization

<p align="center">
  <img src="path/to/sunburst_visualization.png" alt="Sunburst Visualization">
</p>

The sunburst represents the relation between different ownership sectors and different types of jobs in the market. We can observe that the private sector dominates the world, followed by the public sector. In all sectors, data scientist is a demanding job.

### Scatterplot Visualization

<p align="center">
  <img src="path/to/scatterplot_visualization.png" alt="Scatterplot Visualization">
</p>

The scatterplot depicts various industries around the world in terms of different ownership sectors. If we look at various jobs, industries such as manufacturing, mining, accounting, and so on are giving more data scientist jobs. Analyst employments are also in high demand in the market, particularly in businesses such as banks and credit unions, clothing and shoe stores, and gambling.

### Company Rating

<p align="center">
  <img src="path/to/company_rating.png" alt="Company Rating">
</p>

Among all the companies, private and public sectors hold very good ratings with the greatest number of people working in them.

### Technology Demand

<p align="center">
  <img src="path/to/technology_demand.png" alt="Technology Demand">
</p>

We can see from the above bar plot that Python is the most in-demand talent followed by Excel and SQL.

### Average Salaries and Technology Skills

<p align="center">
  <img src="path/to/average_salaries.png" alt="Average Salaries">
</p>

The above KDE visualization for average salaries with Python and SQL demonstrates that those who possess these skills tend to have higher average salaries compared to other technologies.

### Correlation Plot

<p align="center">
  <img src="path/to/correlation_plot.png" alt="Correlation Plot">
</p>

The correlation plot provides insights into the relationships between different variables in the dataset.

### Model Results

After visualizing the dataset, several machine learning models were applied. The following are the results obtained for each model:

- Linear Regression
  - R^2 score for train data: -4.65
  - R^2 score for test data: -9.77
  - RMSE value for train data: 32.61
  - RMSE value for test data: 39.86

- Lasso Regression
  - R^2 score for train data: -15.46
  - R^2 score for test data: -27.17
  - RMSE value for train data: 33.42
  - RMSE value for test data: 39.98

- Ridge Regression
  - R^2 score for train data: -4.86
  - R^2 score for test data: -10.11
  - RMSE value for train data: 32.61
  - RMSE value for test data: 39.86

- Support Vector Regression (SVR)
  - R^2 score for train data: -42.81
  - R^2 score for test data: -66.02
  - RMSE value for train data: 34.0
  - RMSE value for test data: 40.39

- Decision Tree
  - R^2 score for train data: 0.73
  - R^2 score for test data: -0.96
  - RMSE value for train data: 16.21
  - RMSE value for test data: 45.63

- Random Forest
  - R^2 score for train data: 0.33
  - R^2 score for test data: -3.51
  - RMSE value for train data: 19.45
  - RMSE value for test data: 47.35

## Conclusion

Based on all the insights derived from the visualizations and machine learning part, we were able to predict the average salary with respect to the technical stack. This analysis provides valuable information for individuals aspiring to pursue a career in data science and helps companies understand the current trends and demands in the job market.







