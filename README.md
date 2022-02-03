# R_BearlyAsleep_Repo

This file is to show my knowledge of R.

**First Project:** 
I installed "Gapminder" to grab data from.

I then installed "dplyr" to manipulate datasets.

I created a dataframe as "df1" to select couuntry and life expectancy. I then filted the selection for countries to only be South Africa and Ireland. The purpose of this analysis is to see if there is a difference in life expectancy and if it is statistically significant or if it is just due to chance.

I then ran a t.test, which gave me a 95 percent confidence interval with a p value of nearly 0, which shows that there is a statistical difference between life expectancies. We can reject the null hypothesis that there is no difference in the average life expectancies in Ireland and South Africa.

**Second Project**
In the second project, I used ggplot2 to plot life expectancies (y-axis) against gdp per capita (x-axis). I separated my plots by continents and made the size of the dots in the scatterplots proportional to the size of the population. 

I also ran a linear regression for each scatter plot using the life expectancy (response variable) and gdp per capita (explantory variable) and population (explantory variable). The p variable for these analyses was nearly 0 meaning it is statistically significant.
