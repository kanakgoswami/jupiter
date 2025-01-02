Definition
An outlier is a data point that is far outside the average value of a group of statistics. 
Causes
Outliers can be caused by variability in measurement, experimental error, or novel data. 
Impact
Outliers can have a disproportionate effect on statistical results, such as the mean, which can result in misleading interpretations. 
How to find outliers
There are several ways to find outliers, including sorting values from low to high, using a box plot, and using the interquartile range (IQR): 
Box plot: Outliers are shown outside of the “whiskers” of the plot, which represent the minimum and maximum values of the dataset. 
IQR: Outliers are often defined as values that fall below Q1 - 1.5(IQR) or above Q3 + 1.5(IQR), where Q1 is the first quartile and Q3 is the third quartile. 

IQR Steps:
Calculate quartiles:
Sort your data in each numerical column from lowest to highest.
Find the median (Q2): This is the middle value of your data.
Find the first quartile (Q1): This is the median of the lower half of your data.
Find the third quartile (Q3): This is the median of the upper half of your data.

Calculate the IQR:
IQR = Q3 - Q1

Identify potential outliers:
Calculate the lower boundary: Q1 - (1.5 * IQR)
Calculate the upper boundary: Q3 + (1.5 * IQR)

Any data point falling outside these boundaries is considered a potential outlier. 