# Tableau-Homework


![alt text](https://d21xlh2maitm24.cloudfront.net/nyc/IMG_6903.jpg?mtime=20190327132908)

<p align="center">
  <a href="#data-source">Data Source</a> •
  <a href="#findings">Findings</a> •
  <a href="#technology-Used">Technology Used</a>
</p>

A analysis for the New York Citi Bike Program, in which responsible for overseeing the largest bike sharing program for 200,000+ data points in the United States
 in order to generate business insights in terms of visulize the peak time in both summer and winter period and the top start location in New York City and Jersey City, New Jersey
 
* Click [here](https://public.tableau.com/profile/lina.ma3495#!/) to view complted dashboard

![alt text](https://raw.githubusercontent.com/lina3362/Tableau-Homework/main/Dashboards/Dashboard-Trips%20Compare.png)

![alt text](https://raw.githubusercontent.com/lina3362/Tableau-Homework/main/Dashboards/Dashboard-%20Summer%20%26%20Winter%20Peak%20Hours%20Compare.png)

![alt text](https://raw.githubusercontent.com/lina3362/Tableau-Homework/main/Dashboards/Dashboard%20-Map.png)

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
<th>Size</th>
<th>Type</th>
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
There were 7% user did not provide gender information and most of them (14%) are weekend users so we will not be able to tell if female are more willing to ride
on the weekend then they do on weekdays, but we may still determine that male user are the dominant customer at all time

![alt text](https://raw.githubusercontent.com/david880110/Citi-Bike-Analytics/master/image/limitation.png)


## Findings 


### (1) The current major citi bike riders fall into young male group between 18 -20 but number of femal reiders increases over time as they are showing interest to start riding during the weekend

![alt text](https://raw.githubusercontent.com/david880110/Citi-Bike-Analytics/master/image/customer_base.png) ![alt text](https://raw.githubusercontent.com/david880110/Citi-Bike-Analytics/master/image/femal_ridership.png)

### (2) The 1st and 2nd peak hours during a day would usually be 7-8 AM and 5-6 PM season-regardless 

![alt text](https://raw.githubusercontent.com/david880110/Citi-Bike-Analytics/master/image/peakhours.png)

### (3) As the temperature gets cold as winter begins, people tend not to ride as well because of the lack of comfort individuals face when riding in low temperatures. Therefore, at some point the ridership does not grow. However, the total amount of annual member have been kept increased over time in 2017

![alt text](https://raw.githubusercontent.com/david880110/Citi-Bike-Analytics/master/image/2017_growth.png)

## Map visualization for city officials

* More and more people choose to live in Jersey City and work in Manhathan

![alt text](https://raw.githubusercontent.com/david880110/Citi-Bike-Analytics/master/image/popular_location.png)

## Technology Used

<img src="https://raw.githubusercontent.com/david880110/tech-logo/master/python%20logo.png" width="240" height="50"/>

<img src="https://raw.githubusercontent.com/david880110/tech-logo/master/tableau%20logo.png" width="240" height="60"/>


