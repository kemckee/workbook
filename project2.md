# Project 2

## Question 1

Continuous data is numerical data that provides quantitative information about a variable. Continuous data can be further broken down into interval and ratio variables. Interval variables are measured along a continuum where 0 is just another number along the continuum (ex. temperature in celsius). Ratio variables are the same as interval variables with the exception that 0 indicates there is none of that variable (ex. weight). Nominal variables are essentially categories or bins that split up the data set by some characteristic of interest (ex. parrots, songbirds, hawks). Ordinal data is similar to nominal data with the exception that the categories have a distinct order (ex. 1st, 2nd, 3rd place in a race). 

To illustrate these types of data imagine a dataset providing information about the yields of every potato farmer in Idaho. This dataset might include which types of potato each farmer chose to grow that year. Different types of potatoes are an example of nominal data. There might also be information about the weight in pounds of each farmer's yield, which would be an example of continuous data. The data set could also have subjective evaluations of the growing conditions for a given year as reported by the farmers on a scale from 1 to 5 (1 being very poor and 5 being very good). This is an example of ordinal data because the values represent a distinct rank for the growing conditions. The features might be the different types of potato and growing conditions and the targets could be the yield for each type of potato. The goal of the analysis would then to be determine if certain potato types and self reported growing conditions correlated with higher yield. 


## Question 2

The first plot uses alpha and beta of 5 with a sample of 10000 data points, which yields a relatively normal distribution with a mean of 0.49650898128794346 and a median of 0.4967548121582548.

![](normal.png)

The second plot uses alpha of 0.5 and beta of 5 to produce a right skewed distribution. The mean is 0.08387259091317668 and the median is 0.040367671522080234.

![](rightskew.png)

The third plot uses alpha of 5 and beta of 0.5 to produce a left skewed distribution. The mean is 0.9117711226108247 and the median is 0.9540031869608877.

![](leftskew.png)

# Question 3

This first plot shows the change in life expectancy from 1952 to 2007 with the raw data. 

![](rawlifeExp.png)

This plot shows the life expectancy data transformed to a logarithmic scale with base 10 using np.log10().

![](loglifeExp.png)

The log10 plot is more helpful in this case because it more clearly shows the trend upward in life expectancy that occurred over time. The raw data plot still conveys this information but it is  less clear because of the overlap and similar height of the bars from 1952 and 2007.

# Question 4

The first plot shows the box and whiskers plot for population in each year of the gapminder data set using the raw data.

![]()

This plot shows the same information but with the population variable transformed using the np.log10() method.

![]()

The log10 plot communicates the information much better than the raw data plot because there are fewer outliers after the transformation so the scale makes the graph much more readable. 