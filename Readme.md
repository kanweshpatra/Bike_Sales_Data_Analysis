Problem statement:
Doing some exploratory data analysis on the bike sales data.
Step-by-step walkthrough of the mini-project.

Step 1:
Downloading the dataset

Step 2:

![Pivot_table_2](https://github.com/AashayBharadwaj/Bike_Sales_Data_Analysis/blob/main/Creating_4_sheets.jpg)



>Creating 4 different sheets
>Main sheet(where all the original data is kept intact)
>Working sheet(you do your workings on this sheet)
>Dashboard
>Pivot tables

Step 3:
Data Exploration

![Pivot_table_2](https://github.com/AashayBharadwaj/Bike_Sales_Data_Analysis/blob/main/Exploring_data.jpg)



(ID
Marital status
Income
Children
Education
Occupation
Homeowner
Cars
Commute distance
Region 
Age
Purchased bike?)



Step 4:
Data Cleaning

![Pivot_table_2](https://github.com/AashayBharadwaj/Bike_Sales_Data_Analysis/blob/main/Modifying_Data.jpg)



>Remove duplicates(Go to data pane and click on remove duplicates)
>Replace the “M’s” & “S’s” in the Married/Single column with Married and Single.
(Use CTRL + H for using the find and replace command)
>Repeat the same process for the gender column and replace M’s with male and F’s with Females
>Adding a new column called AgeBracket for having age groups(otherwise the data will be too complex to visualize)
>We can use the If statement to do this.
>Nested If statement to get this formula.(We create a range for adolescents,Middle Aged and Old people.)

Step 4:
>Create Pivot tables
>Insert Pivot Table from the working sheet with all the available data
>In the first step you create a table to see the average income for males and females
>Here we can see the average income of the Females and Male who have and have not purchased a bike.

# Bike_Sales_Data_Analysis
![Pivot_table_1](https://github.com/AashayBharadwaj/Bike_Sales_Data_Analysis/blob/main/Pivot_Table_1.jpg)



![Pivot_table_2](https://github.com/AashayBharadwaj/Bike_Sales_Data_Analysis/blob/main/Pivot_table_2.2.jpg)




Step 5:
>Creating dashboard

![Pivot_table_2](https://github.com/AashayBharadwaj/Bike_Sales_Data_Analysis/blob/main/FInal_Dashboard.jpg)



>Drag all the charts to the new sheet called dashboards
>Blur the gridlines
>Arrange the charts


![Pivot_table_1](https://github.com/AashayBharadwaj/Bike_Sales_Data_Analysis/blob/main/Adding_Filters.jpg)


Step 6:
>Add filters to the pivot tables by 
>Selecting the chart
>Going to the pivot chart analyze pane
>Inserting slicers
>Here we added married or single filter on this chart to see how many married or single males and females have purchased the bikes.
We can also add the same filter to other charts by selecting the slicer, going to the slicer pane and reporting connections to all the pivot tables.

Step 7:

As an analyst a few insights that can generated for a potential stakeholder can be:
1)Bikes are more preferred by people in their middle age than adolescents and old people.

2)The average commute for the people buying most bikes is between 0-1 mile. After this the trend is somewhat declining and flat betweek 1 miles to 10 miles.It falls drastically beyond 10 miles of commute.

3)In general, for both males and females, the ones with a higher income tend to buy bikes as against the ones with a relatively lower income.


