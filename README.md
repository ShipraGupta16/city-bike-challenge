# city-bike-challenge

This challenge is on the largest bike-sharing program in the United States. As a lead data analyst, we are expected to generate regular reports for city officials looking to publicize and improve the city program. Since 2013, the Citi Bike program has implemented a robust infrastructure for collecting data on the program's utilization. Each month, bike data is collected, organized, and made public on the Citi Bike DataLinks to [City Bike Data](https://citibikenyc.com/system-data).

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have questions about the program, so our first task on the job is to build a set of data reports to provide the answers.

The data is downloaded from the City Bike website from Aug 2022 - July 2023 to answer the questions below. The size of all the data are more than 100 MB and can't be uploaded to the repo so, here are the names of the file.

JC-202208-citibike-tripdata.csv <br>
JC-202307-citibike-tripdata.csv <br>
JC-202306-citibike-tripdata.csv <br>
JC-202305-citibike-tripdata.csv <br>
JC-202304-citibike-tripdata.csv <br>
JC-202303-citibike-tripdata.csv <br>
JC-202302-citibike-tripdata.csv <br>
JC-202301-citibike-tripdata.csv <br>
JC-202212-citibike-tripdata.csv <br>
JC-202211-citibike-tripdata.csv <br>
JC-202210-citibike-tripdata.csv <br>
JC-202209-citibike-tripdata.csv <br>

#### Tech stack: Python, Tableau
I used to Python (jupyter notebook) to read all the csv files, concatenate them, and extract the starting time and ending time of the journey to use it in Tableau. The final merged filename is citi_bike_2022_2023.csv

### Questions:

1. What are the top 10 stations in the city for starting a journey?
2. What are the top 10 stations in the city for ending a journey?
3. What are the bottom 10 stations in the city for starting a journey?
4. What are the bottom 10 stations in the city for ending a journey?
5. What are the peak months when bikes are used during a time period (August 2022 - July 2023)?
6. What are the peak time during the day when bikers ride?
7. Do bikers use annual membership to ride bikes?
8. What is their preference over classic bike, electric bike and docked bike?

#### Dashboard 1:
showing the top 10 starting stations and ending stations. The density map represent the heatmap of starting locations labeled with zip code. There are two hotspots areas which shows the starting prime locations in the 07030 and 07302 zip code. 

https://public.tableau.com/app/profile/shipra1168/viz/citybike_16964763213050/Dashboard1?publish=yes

![Screenshot 2023-10-10 at 12 05 55 AM](https://github.com/ShipraGupta16/city-bike-challenge/assets/25715747/97d53c88-1d3f-4406-a889-eec5c9a831ea)

#### Dashboard 2:
showing the bottom 10 starting stations and ending stations. The density map represent the heatmap of ending locations labeled with zip code. There are two prime hotspot locations for ending the journey in the 07030 and 07302 zip code which is similar to the above starting journey. These represent the frequent bikers location. 

https://public.tableau.com/app/profile/shipra1168/viz/citybike_16964763213050/Dashboard2?publish=yes

![Screenshot 2023-10-10 at 12 06 21 AM](https://github.com/ShipraGupta16/city-bike-challenge/assets/25715747/50e8657c-bc11-4001-bcba-09aab30d1989)

#### Dashboard 3:
represent the peak hours during the day. Throughout this time period (Aug 2022 - July 2023), August is the peak month for highest bike ride with starting time in the morning around 8 am and ending time in the evening around 6 pm. Bikers prefer classic bike ride way more than electric or docked bike.

https://public.tableau.com/app/profile/shipra1168/viz/citybike_16964763213050/Dashboard3?publish=yes

![Screenshot 2023-10-10 at 12 06 52 AM](https://github.com/ShipraGupta16/city-bike-challenge/assets/25715747/8b2bb544-8a33-4ee5-a389-880e7eb27922)

#### Story 1:
represent bike types, members and its popularity. Summers have more riders with August as the peak month popular with classic bike rides followed by electric bikes. There are more annual members riding the bike than casual riders. 

https://public.tableau.com/app/profile/shipra1168/viz/citybike_16964763213050/Story1?publish=yes

<img src="https://github.com/ShipraGupta16/city-bike-challenge/assets/25715747/b9be5ade-c7b8-496e-bfe7-cdedbacb4ecd" width=70% height=50%>

<img src="https://github.com/ShipraGupta16/city-bike-challenge/assets/25715747/1af75b09-10bc-4d18-b2ed-26a59b0cf42c" width=70% height=50%>

<img src="https://github.com/ShipraGupta16/city-bike-challenge/assets/25715747/b3ef9d06-22d2-480b-9032-a66f38706a07" width=70% height=50%>

### Summary
1. Biker services are remarkably in demand during the summer months (August specially). Bikers like to ride classic bikes and use their membership. 

2. The starting and ending locations are in the same neighborhood (based on zip code).

3. Main usage of the bike services are during the office hours morning 8 am and evening 6 pm which indicates that people like to use bikes to commute to offices.

### References
[City Bike](https://en.wikipedia.org/wiki/Citi_Bike)

[City Bike Wiki](https://citibikenyc.com/system-data) 
