Video I followed: https://www.youtube.com/watch?v=_V8eKsto3Ug&list=WL&index=5&t=4950s

I was already introduced to R in Google Data Analytics Certificate but I wanted to get a perspective for R in statistical computing. In a course I refreshed my knowledge on installing R, RStudio and packages. Then we continue with plot() function and moved on with bar charts, histograms, scatterplots, overlaying plots, summary(), describe(), selecting cases. Selecting case like, showing values or graphs that have condition like in SQL WHERE clause.
Then I refreshed memory on data formats. Lists, data frames, matrix... The most useful one for data analysis are dataframes. After that we reviewed how to enter or import data. For importing data we used library rio which stand for r input output, we also used import the data using read.table and read.csv. After that we viewed data with View function.
Then I got familiar with HIERCHICAL CLUSTERING. Using dist and hclust function to compute clusters and then plot them with plot function. That way we get cluster dendrogram. After plotting dendrogram we added boxes to the plot. From k=2 to k=6. That creates 2 big boxes then 3 smaller and so on until 6 box. 
Then followed the PRINCIPAL COMPONENTS AKA DIMENSIONALITY REDUCTION. If you have a scatter plot and two variables and you draw the regression line, you can calculate the perpendicular distance to the regression line. Went from 2D to 1D but maintained the most important information.
REGRESSION - out of many variables, one variable -> out of many scores, one score. The idea of regression is that you use many variables to predict scores on one variable. There are many versions & adaptations to make it flexible and powerful. Example: We have a table of 6 judges listed by name and we have scores on a number of different variables and finishes with are they worth of retention. RTEN.
We created a matrix that consist all of the predicted variables simultaneously. Read data, read all the columns except 12. That was matrix X. Then we created Y that had all the rows but only read the 12th column, that is the one that has RTEN - worthy of retention.
Then we use reg1 <- lm(y~x) and reg1 to see the coefficients. using summary(reg1) we find out that the most important variables/ in sync are integrity and physics (able to physically come to work).

File explanation:
* [Code](https://github.com/rokzupan1/StatisticalComputingInR/blob/main/R%20-%20Basics%20of%20Statistical%20Computing.R)
* [ChatGPTExplanation](https://github.com/rokzupan1/StatisticalComputingInR/blob/main/Interesting.PNG)

Other 3 files are datasets used to demonstrate the importing data from csv,txt and xlsx files.
