# group_project_1


Prevalence and Patterns of Mental Health Disorders 
Final Analysis



Using the most recent 5 years of prevalence percentage data, the mean of each disease per country was calculated and a new frame of top 50 countries for each disorder was created. From there the disorder correlation was calcualted and any “r” value  above 0.6 was deemed meaningful based on discipline ( social sciences ). Anxiety and bipolar disorder had positive correlation with an “r ” of 0.65 while anxiety and eating disorders had an “r” of 0.67. Between the disorders associated with anxiety, there was a positive correlation between eating disorders and bipolar disorder, “r” value 0.70. In conclusion, anxiety positivley coreelated with bipolar disorder and eating disorders, suggesting those who suffer from one might suffer from another as well. 

From the last 5 years of  orignal study data, the mean percentage per country of anxiety and depression were taken and normalized. These noramlized values were then compared to the historical average high temperatures pulled from  meteostat API. Plotted on a map, with plot size relating to temperature and opacity relating to disorder prevalence, we see some patterns. This showed hotter climates did not have higher anxiety percentages, but colder climates did have higher anxiety and depression percentages.

Over the last 10 years, is there a correlation between an increase in the Population size and an increase in the Prevalence of the disorder around the world ?

We analyzed mental health disorder prevalence and population across 196 countries for the 
period 2012-2017. We compared the Prevalence of these disorders against the population. 
Calculated the correlation between Population and Prevalence of depressive 
disorder and prepared a scatter plot.  We found  a positive correlation between population and 
prevalence of depressive disorders i.e, equal to 1.So it is prominent that the depression % will 
keep increasing over the period as the population keeps increasing exponentially and other 
factors affect the same.Found the top 10 and bottom 10 countries having the most/least 
prevalence of depressive order by taking the mean for each country from the data for the last 
5 years. Included the same inference in the bar chart as well.  Also analyzed the percentage
 of male vs female population impacted and see that in most countries this group of disorders
 is more common for women than for men.In 2017, an estimated 264 million people in 
 The world experienced depression. The share of the population with depression ranges 
mostly between 2% to 6% around the world today. The data shown in our dataset 
demonstrates that health disorders are common everywhere.Improving awareness,  recognition,support and treatment for this range of disorders should therefore be an essential
focus on global health.



Do countries with high anxiety rates also have high dpression rates? Does population have an impact to mental health disorders? Is there any relationship between income and rates of anxiety and depression?

From the dataset, data from the most recent 5 years of the study was used for analysis (2013- 2017)
Plotting anxiety rate against depression rate for all countries and years with availabe data yielded a mild correlation with an r-squared value of 0.35
Comparing the rates of depression between the 5 largest countries by population and the 5 smallest countries, there was no corrleation in the rates of depressive disorders.

Using the Worldbank API, data was gathered for GNI (Gross National Income) per capita for the year 2017 for each country. There did not appear to be any correlation between GNI per capita and depression rate with an r squared value of 0.13, however there was a positive correlation between GNI per capita and anxiety with an r squared value of 0.54


Data source: https://www.kaggle.com/datasets/thedevastator/uncover-global-trends-in-mental-health-disorder?resource=download
