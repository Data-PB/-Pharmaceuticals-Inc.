
# Pharmaceuticals-Inc.

## Background 

A pharmaceutical company specializing in anti-cancer pharmaceutical began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of drug of interest, Capomulin, versus the other treatment regimens. 

## Summary 

* Overall, Capomulin is a viable drug regimen to reduce tumor growth.
* Capomulin had the highest number of mice complete the study, except for Remicane, all other regimens observed several mice deaths across the duration of the study. 
* There is a strong correlation between mouse weight and tumor volume, indicating that mouse weight may be contributing to the effectiveness of any drug regimen.
* There was one potential outlier within the Infubinol regimen. While most mice showed tumor volume increase, there was one mouse that had a reduction in tumor growth in the study.
* Remicane and Capomulin were successful at reducing tumor volume. Remicane and Capomulin reduced average tumor volume by roughly 11%-12%, whereas other treatments increased average tumor volume by roughly 16%-22% after 45 days of treatment.
* Capomulin yielded the highest mouse survival rate, which was about 84%, whereas Propriva yielded only 28% based on the number of mice on day 1 versus day 45 of the treatment duration.

![Scatter_Plot](Images/Scatter plot Capomulin.png)

![Correlation and Regression](Images/Correlation and Regression.png)


## Data Analysis  
* Generated a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.
* Generated a bar plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the number of data points for each treatment regimen.
* Generated a pie plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study.
* Calculated the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Remicane, Infubinol, and Ceftamin. Calculated the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.
* Using Matplotlib, generated a box and whisker plot of the final tumor volume for all four treatment regimens and highlighted any potential outliers in the plot by changing their color and style.
* Generated a line plot of time point versus tumor volume for a single mouse treated with Capomulin.
* Generated a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.
* Calculated the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.
