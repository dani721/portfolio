# This is Danli Zheng's portfolio
###### Davis, CA, 95616 |(510)-918-1202 | Danzheng@ ucdavis.edu
##### Bachelor of Science in Statistics with a minor in Economics Expected Graduation: June 2019

Here is my [RESUME](https://github.com/dani721/portfolio/blob/master/Copy%20of%20Danli%20Zheng%20resume.pdf)


Related Class: 
- Statistics: 
  * :chart_with_upwards_trend:[Sampling Theory of Surveys](https://github.com/dani721/STA-144)
  * Applied Time Series Analysis
  * Analysis of Categorical Data  
  * :bar_chart:[Fundamentals of Statistical Data Science](https://github.com/dani721/STA141A) 
  
- Economic: 
  * :memo:Economics 134 - Financial Economics
  * Economics 122 - Game Theory
  * Economics 151B - Economics of Human Resources
  * Economics 103 - Economics of Uncertainty and Information

  
scatterplot sample
```
rm(list=ls())
library(readxl)
question3 <- read_excel("ucd 19spring/STA144/144 hw/hw3/question3.xlsx")
names(question3)<- c('tree','x','y')

### draw a scatterplot
library(ggplot2)
 
# The iris dataset is proposed by R
head(question3)
 
# basic scatterplot
ggplot(question3, aes(x=x, y=y)) + 
    geom_point()
```
