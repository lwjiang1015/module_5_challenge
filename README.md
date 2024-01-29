# module_5_challenge

## Prepare the Data

The datasets were merged into a single DataFrame "pymaceuticals_df". 

Displayed the number of unique mice IDs in the merged data "pymaceuticals_df". 

Each duplicate mice is found based on the Mouse ID and Timepoint.

A clean DataFrame is created with the dropped duplicate mice. 

The number of mice are shown from the clean DataFrame. 

## Generate Summary Statistics

Calculated the summary statistics, using groupby, including mean, median, variance, standard deviation and SEM for the variable "Tumor Volume".

Created a new DataFrame to hold all the calculated summary statistics.

## Create Bar Charts and Pie Charts
Generated a bar plot showing the total number of timepoints for all mice tested for each drug using Pandas and pyplot, respectively.

Generated a pie plot showing the distribution of female versus male mice using Pandas and pyplot, respectively.

## Calculated Quartiles, find outliers, and create a box plot
Created a DataFrame that has the last timepoint for each Mouse ID using groupby.

The index was reset for merging with original dataset.

Retrieved the maximum timepoint for each mouse by merging with original DataFrame.

Put the four treatment groups in a list as required.

Created an empty list to fill with tumor volume data. 

Calculated IQR, found the outlier, and displayed them for each treatment group.

Generated a box plot showing the distributions of the final tumor volume for each treatment group with the outlier highlighted.

## Create a line plot and a scatter plot
Generated a line plot showing the tumor volume vs. time point for one mouse treated with Capomulin

Generated a scatter plot showing average tumor volume vs. mouse weight for the Capomulin regimen.

## Calculate correlation and regression
Calculated the correlation coefficient and linear regression model for average tumor volume and mouse weight for the Capomulin regimen.

## References/acknowledgement
This assignment has been completed primarily with reference to the course materials for Module 5. The help from the teaching team and from the Xpert Learning Assistant at Datacampspot are acknowledged. 

Matplotlib documentation page [https://matplotlib.org/stable/gallery/statistics/boxplot_demo.html]
