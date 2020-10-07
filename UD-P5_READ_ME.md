## Project 5 - Communicate Data Findings

### Ford GoBike Analysis Project


## Dataset

Data for this project was derived from the Ford GoBike data link [here](https://www.lyft.com/bikes/bay-wheels/system-data).

The dataset used for this project required some extensive data wrangling at the end of which I removed eleven columns and created six, the final shape of my dataset was as follows:

5124358 entries, 0 to 174729
19 columns

duration_sec - Trip Duration (seconds)
start_time - Start Time and Date
end_time - End Time and Date
start_station_id - Start Station ID
start_station_name - Start Station Name
start_station_latitude - Start Station Latitude
start_station_longitude - Start Station Longitude
end_station_id - End station ID
end_station_name - End station Name
end_station_latitude - End station Latitude
end_station_longitude - End station Longitude
bike_id - Bike ID
user_type - User Type (Customer or Subscriber)
duration_min - Trip Duration (mins)
start_hour - Start Time by Hour
start_day_of_week - Start Day of the Week
start_month - Start Month
year - Year of Trip
distance_km - Distance (km)



## Summary of Findings

> Summarize all of your findings from your exploration here, whether you plan on bringing them into your explanatory presentation or not.

Before I relay my findings I must point out that although the data was by and large tidy I think the content was lacking in detail.  It would have been nice to be able to view the users by age and gender but this information was not available in the download, as such the analysis that I could carry out was limited to some degreee.




## Key Insights for Presentation
> Select one or two main threads from your exploration to polish up for your presentation. Note any changes in design from your exploration step here.
Questions

1. What is the most popular day of the week for hiring a bike
* When are most trips taken in terms of time of day, day of the week, or month of the year?
* What is the most most popular start station?
* What is the most popular destination (end) station?
* How long is average journey?
* What is breakdown of subscriber and customer hires?
* In general do subscribers ride longer than customers?
* Has bike hires grown in popularity since Ford GoBike first launched in 2017?


##  Attributation
I used the following resources in the completion of this project:
* **1. Stack Overflow** | website | How to print number with commas as thousands separators? | Link: https://stackoverflow.com/questions/1823058/how-to-print-number-with-commas-as-thousands-separators

* **2. cmdlinetips** | website | How To Move a Column to First Position in Pandas DataFrame? | Link: https://cmdlinetips.com/2020/03/move-a-column-to-first-position-in-pandas-dataframe/

* **3. cmdlinetips** | YouTube | Create presentation slides from Jupyter | Link: https://www.youtube.com/watch?v=utNl9f3gqYQ

