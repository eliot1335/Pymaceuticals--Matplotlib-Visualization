# The Power of Plots - Matplotlib

## Pymaceuticals Inc.

In this activity, I will be practicing how to utilize Matplotlib to visualize our data analysis, presenting findings using bar charts, pie charts, scatter plots, boxplots, and doing linear regression calculations. My given tasks are:

### Cleaning The Data:
We are given two cvs files to begin with, there are duplicate data entries in the Study_results.csv file. We need to merge the two data files, clean up the duplicate entries, and create a new table base on that.

We will be left with 249 unique mice and 1888 data entries after data cleaning.

### Summary Statistics:
In this task, I will be using two different practices to create these statistical summary tables. One would be using summary statistical methods for the calculations, and then using pd.DataFrame to assembly the summary table. The second one would be using .agg() to create a new table from the original table.

### Bar and Pie Charts
In this task, I will try to create bar charts using pandas.plot() and plt.bar() on the total number of unique mice tested on each drug regimen. *I am aware of how depends on the wording interpretation, we will be either focusing on "# of unique mcie" or "# of data entries on each regimen".*

Then we will be doing the same for pie charts, using pandas and pyplot on the distribution of female versus male mice.

### Quartiles, Outliers and Boxplots
In this task, we need to isolate the four regimens of interests (Capomulin, Ramicane, Infubinol, and Ceftamin) and extract the data of last timepoint to compare the result of each regimen, which is the tumor volume. Do the quartiles calculations, gather needed info for outliers calculations, and plot it with boxplots. It is showing one lower bound outlier for Infubinol.

### Line and Scatter Plots
In this task, I will need to select a mouse treated with Capomulin, and use line chart to showcase its whole treatment progress, tumor volume vs. timepont to be exact. It is showing a promising treatment result.

Also, I will try to generate a scatter plot of average tumor volume vs. mouse weight for the Capomulin regimen.

### Correlation and Regression
In this task, we need to calculate the correlation coefficient and linear regression model, and then insert the regression line into the scatter plot of average tumor volume vs. mouse weight for the Capomulin regimen to visualize the correlation between tumor volume and weight.
