# Matplotlib-Challenge
Module 5 Homework - matplotlib - Pymaceuticals

### Instructions
This assignment is broken down into the following tasks:

* Prepare the data.
* Generate summary statistics.
* Create bar charts and pie charts.
* Calculate quartiles, find outliers, and create a box plot.
* Create a line plot and a scatter plot.
* Calculate correlation and regression.
* Submit your final analysis.

## Pymaceuticals Code Theory
1. Ensured all the dependencies were loaded - matplotlibl.pyplot, pandas, scipy.stats, and numpy
2. Pulled the CSVs in from the dta folder
3. Combined the data into a single DataFrame
4. Cleaned the data: removed duplicate entries.
5. Calculated the summaries: mean, median, tumor stats(volume, vol. variance, vol. standard deviation, vol. standard error of mean).
6. Formatted the same summary table with one line of code.
7. Created bar and pie charts using Pandas and pyplot for the distribution of female and male mice.
8. Added some additional color and formatting for flair.
9. Calculated quartile results for the top 4 drug treatments used - Capomulin, Ramicane, Infubinol and Ceftamin.
10. Created box plots with the quartile info from the previous step.
11. Calculated the tumor volume over time for mouse l509.
12. Created a scatter plot to see if there was a correlation between mouse weight and average tumor volume.
13. Added a regression line to show the estimated outcomes based on the scatter plot results.
14. Added my observations at the top of the notebook, also shown below.


## Observations

1. There were almost an equal number of male to female mice tested.
2. Mice on Naftisol and Stelasyn had a higher average Tumor volume than those that had a placebo.
3. Capomulin had the highest # of mice tested while Propriva had the lowest #.
4. Ramicane's and Infubinol's median are fairly closer to the IQR's midrange than Capomulin's and Ceftamin's.
5. While on Capomulin, mouse l509 had tumor growth until the 20th day. The tumor started to shrink and then it started to grow again after around 35 days.
6. Tumor volume seems to be higher in heavier mice.
