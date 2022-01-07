# Kickstarter-Challenge
## Module 1 Challenge assignment

### This project was designed to figure out the most successful kickstarter programs using specific categories and variables. Our first challenge was to create a pivot table and a pivot chart to analyze the "theater" category by month. The second challenge was an analysis using the countifs function to find the percentage of successful, failed, and canceled projects based on the goal.

## Analysis of Outcomes Based on Launch Date

### This analysis was carried out resulting in the chart "Theater Outcomes Vs Launch". In order to get the data needed in a Pivot table the YEAR() function was used to further sort the "Date Created Conversion" column. A pivot table was then created. The "filter" field contained "Years" and "Parent category", the "Columns" field contains "outcomes", the "Rows" field contains "Date Created Conversion", and the "Values" field contains "Count of outcomes". The data set was then further sorted by "Parent category" "theater". 	
## Analysis Based on Goals Chart

### This analysis was carried out resulting in the chart labeled "Outcomes Based on Goal". Using the function =COUNTIFS(Kickstarter!F:F, "successful",Kickstarter!D:D,"<1000",Kickstarter!R:R, "plays"). I was able to sort the data and count how many "successful", "failed", and "canceled" "plays" kickstarter programs were carrried out. After getting the count of each "plays". The Sum() Function was used to find the Total amount of projects. The percentage of "successful" and "failed" programs was calculated and charted vs the "Goal" ranges.

## Challenges and Difficulties Encountered

### Between the two challenges there were a few difficulties. In the first challenge there was a slight amount of difficulty sorting the data by months instead of by year. It was resolved using the "Row Label" Filter. In the second challenge the COUNTIFS() function was difficult to impliment at first using a seperate sheet and multiple perameters. Using slack and google I was able to extract the correct data from the data set.

## Results

### After analysing the data in chart "Theater Outcomes vs Launch" we can see several patterns in the data. The most successful theatrical kickstarter projects are launched in May and June. The month in which projects failed the most is October. This could have a correlation with the falling number of successful campaigns going into the winter. The successful campaigns fall from Oct and remain low through March.

### Looking at the pattern on the chart "Outcomes Based on Goal" a few things can be surmised about the "plays" "Subcategory". The failed vs successful %data is inverse to eachother as there was a 0% cancelation percentage accross the board. The play projects with the most successful outcomes are "less than 1000" to "15000 to 19999" where it becomes 50% success/failed. Another successful outcome are from projects between "$35000 to $39999" to "$40000 to $45999". Therefore any play projects will have the best results if they can set their goal in the aformentioned ranges.

### In Summation the data set could be improved upon there are several outliers as some of the goals set were very high and not met. Another table and chart could be used showing Goal vs Pledged data and be refined by country or by type of "Subcategory"
