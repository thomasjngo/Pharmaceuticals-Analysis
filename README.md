# Summary

## Data Preparation
- Imported necessary packages and data.
- Merged `mouse_metadata` and `study_results` DataFrames into a single DataFrame.
- Identified and removed any duplicate entries based on mouse ID and time points.
- Displayed the updated count of unique mice IDs.

## Summary Statistics
- Generated a DataFrame containing summary statistics for tumor volume across different drug regimens.
- Statistics included: mean, median, variance, standard deviation, and SEM.
- Regimen names were used as the index.

## Bar Charts and Pie Charts
- Created two bar charts (using both Pandas and Matplotlib) showing the total number of rows (Mouse ID/Timepoints) for each drug regimen.
- Produced two pie charts (using both Pandas and Matplotlib) displaying the distribution of male versus female mice.

## Quartiles, Outliers, and Box Plot
- Calculated quartiles and IQR for final tumor volumes in four key treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin.
- Identified potential outliers.
- Generated a box plot for each regimen, highlighting outliers.

## Line Plot and Scatter Plot
- Selected a mouse treated with Capomulin and created a line plot of tumor volume versus time point.
- Produced a scatter plot of mouse weight versus average tumor volume for the Capomulin regimen.

## Correlation and Regression
- Calculated the correlation coefficient and performed linear regression between mouse weight and average tumor volume for the Capomulin regimen.
- Plotted the regression model on the scatter plot.
