# matplotlib-challenge

## Background

Pymaceuticals Inc. is a burgeoning pharmaceutical company based out of San Diego that specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. You have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results.


## Observations and Insights
The following observations were made:

1) After calculating a summary statistics table of mean, median, variance, standard deviation, and SEM of the tumor volume for each regimen, it appears that Ramicane slightly outperformed Capomulin because it statistically had the lowest values for each of the statistical measures. In other words, Ramicane was more effective of reducing the size of the tumors in the subject mice. Ramicane and Capomulin were the most successful drugs and Ketapril was the least successful.

2) After plotting bar charts to display the number of data points per Drug Regimen, it appears that Capomulin and Ramicane were the two most tested drugs with 230 and 228 data points, respectively. Propriva was the least tested with only 161 data points. The remaining seven drugs were evenly tested with an average of 182 data points.

3) There was a near identical number of male and female mice tested with 50.2% males and 49.8% females. However, further analysis would need to be conducted in order to determine if gender played a role in the success of each treatment regimen.

4) The boxplots visually confirmed that out of the four promising drug regimens (Capomulin, Ramicane, Infubinol, and Ceftamin), Ramicane followed by Capumolin had the most successful outcomes with the median tumor volume of 36.56 mm3 and 38.13 mm3, respectively. Infubinol was the only drug out of the four with an outlier.

5) After charting a line graph observing how the Capomulin drug impacted one mouse (l509) over the entire 45 days, it appears that the mouse had the highest tumor volume of 48.07 mm3 at 20 days and the highest tumor volume of 40.21 mm3 at 35 days. At the end of the 45-day study, this particular mouse had a final tumor volume of 41 mm3. Generally-speaking, the longer the mouse was being treated with the Capomulin drug, the tumor volume reduced in size.

6) The Correlation (R) between Mouse Weight and the Average Tumor Volume is 0.84 which indicates a strong correlation. Generally, a value of r greater than 0.7 is considered a strong correlation. Therefore, the more that the mice weighed, then the higher their average tumor volume grows in size.