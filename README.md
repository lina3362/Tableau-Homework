# Tableau-Homework


![alt text](https://d21xlh2maitm24.cloudfront.net/nyc/IMG_6903.jpg?mtime=20190327132908)

<p align="center">
  <a href="#data-source">Data Source</a> •
  <a href="#findings">Findings</a> •
  <a href="#technology-Used">Technology Used</a>
</p>

A analysis for the New York Citi Bike Program, in which responsible for overseeing the largest bike sharing program for 200,000+ data points in the United States
 in order to generate business insights in terms of visulize the peak time in both summer and winter period and the top start location in New York City and Jersey City, New Jersey. I was interested to find out how COVID impacted Citi Bike via this project, so I selected 2019 and 2020 data, compared 2019 vs 2020 from total riders, gender distribution, tripduration, etc. aspects.
 
* Click [here](https://public.tableau.com/profile/lina.ma3495#!/) to view complted dashboard



![alt text](https://raw.githubusercontent.com/lina3362/Tableau-Homework/main/Dashboards/Dashboard-Trips%20Compare.png)



![alt text](https://raw.githubusercontent.com/lina3362/Tableau-Homework/main/Dashboards/Dashboard-%20Summer%20%26%20Winter%20Peak%20Hours%20Compare.png)



![alt text](https://raw.githubusercontent.com/lina3362/Tableau-Homework/main/Dashboards/Dashboard%20-Map.png)



![alt text](https://raw.githubusercontent.com/lina3362/Tableau-Homework/main/Dashboards/Dashboard-%20Gender%20%26%20Tripduration.png)


![alt text](https://raw.githubusercontent.com/lina3362/Tableau-Homework/main/Dashboards/Dashboard-%20Stations%20%26%20Miles.png)



## Data Source
![alt text](https://raw.githubusercontent.com/david880110/Citi-Bike-Analytics/master/image/citibikedata.png)

This [Citi Bike Data](https://www.citibikenyc.com/system-data) has been processed to remove trips that are taken by staff as they service and inspect the system and any trips that were below 60 seconds in length 
(potentially false starts or users trying to re-dock a bike to ensure it's secure).

<table class="hide-while-loading table table-striped">
<tbody id="tbody-content">
<thead>
<tr>
<th>Name</th>
<th>Date Modified</th>
</tr>
</thead>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201901-citibike-tripdata.csv.zip">JC-201901-citibike-tripdata.csv.zip</a></td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201902-citibike-tripdata.csv.zip">JC-201902-citibike-tripdata.csv.zip</a></td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201903-citibike-tripdata.csv.zip">JC-201903-citibike-tripdata.csv.zip</a></td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201904-citibike-tripdata.csv.zip">JC-201904-citibike-tripdata.csv.zip</a></td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201905-citibike-tripdata.csv.zip">JC-201905-citibike-tripdata.csv.zip</a></td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201906-citibike-tripdata.csv.zip">JC-201906-citibike-tripdata.csv.zip</a></td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201907-citibike-tripdata.csv.zip">JC-201907-citibike-tripdata.csv.zip</a></td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201908%20citibike-tripdata.csv.zip">JC-201908 citibike-tripdata.csv.zip</a></td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201909-citibike-tripdata.csv.zip">JC-201909-citibike-tripdata.csv.zip</a></td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201910-citibike-tripdata.csv.zip">JC-201910-citibike-tripdata.csv.zip</a></td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201911-citibike-tripdata.csv.zip">JC-201911-citibike-tripdata.csv.zip</a></td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201912-citibike-tripdata.csv.zip">JC-201912-citibike-tripdata.csv.zip</a></td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-202001-citibike-tripdata.csv.zip">JC-202001-citibike-tripdata.csv.zip</a></td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-202002-citibike-tripdata.csv.zip">JC-202002-citibike-tripdata.csv.zip</a></td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-202003-citibike-tripdata.csv.zip">JC-202003-citibike-tripdata.csv.zip</a></td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-202004-citibike-tripdata.csv.zip">JC-202004-citibike-tripdata.csv.zip</a></td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-202005-citibike-tripdata.csv.zip">JC-202005-citibike-tripdata.csv.zip</a></td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-202006-citibike-tripdata.csv.zip">JC-202006-citibike-tripdata.csv.zip</a></td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-202007-citibike-tripdata.csv.zip">JC-202007-citibike-tripdata.csv.zip</a></td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-202008%20citibike-tripdata.csv.zip">JC-202008 citibike-tripdata.csv.zip</a></td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-202009-citibike-tripdata.csv.zip">JC-202009-citibike-tripdata.csv.zip</a></td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-202010-citibike-tripdata.csv.zip">JC-202010-citibike-tripdata.csv.zip</a></td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-202011-citibike-tripdata.csv.zip">JC-202011-citibike-tripdata.csv.zip</a></td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-202012-citibike-tripdata.csv.zip">JC-202012-citibike-tripdata.csv.zip</a></td>
<td>ZIP file</td>
</tr>
</tbody>
</table>

* Limitation
There were 7% user did not provide gender information in 2019 and 15% did not provide in 2020. Some users seem like did not provide true age info as we show there are riders were over 100 years old. 


### Findings 


(1) Total trips in 2020 is roughly 70,000 lower than the total trips in 2019 due to COVID. September is the busiest month in 2019, totaling 49,244. But in 2020, October was the busiest month, totaling only 26,149.

(2) 2019 Weekday trips, Tuesday had the highest trips (64,857). In 2020, Saturday had the highest rides (57,061). A lot of people were ordered working from home during COVID which may caused this differences. 

(3) NY Citi Bike programs had more subscribers in 2019 (362,921 in 2019 vs 231,531 in 2020), and more customers buy short-term passes in 2020 (105,271 in 2020 vs 43,026), might be the same reason as above.

(4) Summer peak hour in 2019 is 8am and 6pm, summer peak hour in 2020 is 6pm and 7pm. Winter peak hour in 2019 is 8am and 6pm, winter peak hour in 2020 is 5pm and 6pm.

(5) Popular start locations in 2019 and 2020 are in the same/similar spots.

(6) Based on the bike ids, 2020 added new bikes in the city.

(7) More people did not enter their gender info in 2020.

(8) There may be false age information both in 2019 and 2020, according to the graghs, some of the trips were rider by people over 100 years old. 



## Technology Used

![alt text](https://www.python.org/static/community_logos/python-logo.png)

![alt text](https://linksinternational.com/wp-content/uploads/2020/09/Tableau-Logo-300x200.png)


