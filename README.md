# NYC-311-s-Customer-Service-Requests-Analysis
Tasks to Perform
1. Understand the dataset:
1.1Import the dataset
1.2Visualize the dataset
1.3Print the columns of the DataFrame
1.4Identify the shape of the dataset
1.5 Identify the variables with null values
2. Perform basic data exploratory analysis:
2.1Draw a frequency plot to show the number of null values in each column of the DataFrame
2.2Missing value treatment
2.2.1Remove the records whose Closed Datevalues are null
2.3Analyze the date column,and remove entries that have an incorrect timeline
2.3.1Calculate the time elapsed in closed and creation date
2.3.2Convert the calculated date to seconds to get a better representation
2.3.3View the descriptive statistics for the newly created column
2.3.4Check the number of null values in the Complaint_Typeand Citycolumns
2.3.5Impute the NA value with Unknown City
2.3.6Draw a frequency plot for the complaints in each city
2.3.7Create a scatter and hexbin plot of the concentration of complaints across Brooklyn
3. Find major types of complaints:
3.1Plot a bar graph to show the types of complaints
3.2Check the frequency of various types of complaints for New York City
3.3Find the top 10 complaint types
3.4Display the various types of complaints in each city
3.5Create a DataFrame, df_new, which contains cities as columns and complaint types in rows
4. Visualize the major types of complaints in each city
4.1Draw another chart that shows the types of complaints in each city in a single chart, where different colors show the different types of complaints
4.2Sort the complaint types based on the average Request_Closing_Timegrouping them for different locations
5.See whether the average response time across different complaint types is similar (overall)
5.1Visualize the average ofRequest_Closing_Time
6.Identify the significant variables by performing statistical analysis using p-values
