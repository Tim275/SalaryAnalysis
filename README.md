# SolaryAnalysis

## Introduction: The Goal about this Project, is  to seperate the given csv. (SQL Table) with the data to  charts to Visualize and analize them.

i learned before:

•	basics oft he Mathematical calculations in Nympy

•	evaluate data in pandas	

•	create  visual  graphics in seaplot

# In This Project i achieved those skills:

•	How to visualize Data (sealab/panda)

•	How to filter out relevant Information (panda)

•	calculate statistics (average income) (panda)

In general it can develop important data analysis and visualization skills that can help spot trends and patterns in the data and make informed decisons.


# Summary
1) First attempt i tryed to create a Dataframe from the Solary.csv file.
The result was the error, but it seems like the file loaded. Why then the Error?

It turned out out that some of the colums that contained numbers, are declared as strings.
To cast the datatype to a number, we need to specify it explicitly.
The function ‚convert_to_float‘ does it for each value.
 
So the code compiled without any errors and right declared columbs.

2) Now ist time to Visualize the distribution

 We extract the Series  Year of 2014 from the Dataframe df and deplox the it




task 2:
We want to move to San Francisco. What public job should we take to earn as much money as possible?
So determine the 10 most common jobs (grouped by the `JobTitle` column) and plot the average total income (TotalPayBenefits) for the year 2014 for each JobTitle in a bar chart. What job should we apply for?

For this task we need the groupby function, because we want to extract data by using one or more columns for a group-based analysis:
 
Only the JobTitle is down.
Lets fix it with…



Now everything visual is right

For the Visualize part I use seaborn,  because the countplot` function is particularly useful for visualizing the counts of categorical variables, which can be helpful when working with the results of a `groupby` operation.

3) Task 3
See solution. Goes everything fine there
