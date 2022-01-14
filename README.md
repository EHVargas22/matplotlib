**Summary:**

Completed analysis on the data from an animal study in which 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of one drug of interest versus the other treatment regimens. 


**Data Cleanup:**

Checked the data for any mouse ID with duplicate time points and removed any data associated with that mouse ID.


**Used the cleaned data to generate the following:**
- A summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen. 
- A bar plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the total number of timepoints for all mice tested for each drug regimen throughout the course of the study.
- A pie plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study.
- Calculation of the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. 
- Calculation of the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.
- A box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style using Matplotlib.
- A line plot of tumor volume vs. time point for one mouse treated with Capomulin.
- A scatter plot of tumor volume versus mouse weight for the Capomulin treatment regimen.
- The correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. - Linear regression model on top of the previous scatter plot.

**Conclusion:**

Listed three observations/inferences made from the data.
