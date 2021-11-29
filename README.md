# ANA515-Assignment3

This is assignment 3 for ANA 515. The data set used in this assignment is from NOAA’s Storm Events Database and it lists major weather-related storm events in 1991. 

The following steps were peformed on the dataset "StormEvents_details-ftp_v1.0_d1991_c20210803.csv":

1. load data into R

2. Limit the dataframe to the following columns: 
•	the beginning and ending dates and times 
•	the episode ID
•	the event ID
•	the state name and FIPS
•	the “CZ” name
•	type
•	FIPS
•	the event type 
•	the source
•	the beginning latitude and longitude and ending latitude and longitude 

3. Convert the beginning and ending dates (BEGIN_DATE_TIME and END_DATE_TIME) to a “date-time” class 

4. Change state and county names to title case 

5.	Limit to the events listed by county FIPS (CZ_TYPE of “C”) and then remove the CZ_TYPE column

6.	Pad the state and county FIPS with a “0” at the beginning and then unite the two columns to make one fips column with the 5 or 6-digit county FIPS code 

7.	Change all the column names to lower case 

8.	There is data that comes with base R on U.S. states (data("state")). Use that to create a dataframe with these three columns: state name, area, and region 

9.	Create a dataframe with the number of events per state in the year of your birth. Merge in the state information dataframe you just created in step 8. Remove any states that are not in the state information dataframe

10. Creat a plot
