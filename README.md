
# Citi-Bike-Analytics

![alt text](https://d21xlh2maitm24.cloudfront.net/nyc/Annual-Membership-Image.png?mtime=20170331121650)

<p align="center">
  <a href="#data-source">Data Source</a> •
  <a href="#findings">Findings</a> •
  <a href="#technology-Used">Technology Used</a>
</p>

A analysis for the New York Citi Bike Program, in which responsible for overseeing the largest bike sharing program for 200,000+ data points in the United States
 in order to generate business insights in terms of visulize the peak time in both summer and winter period and the top start location in New York City and Jersey City, New Jersey
 
* Click [here](https://public.tableau.com/profile/nicholas.amoroso#!/vizhome/TableauHomework_16058223224350/bikeusagetime?publish=yes) to view complted dashboard

![alt text](https://raw.githubusercontent.com/AmorosoData/Tableau-Challenge/main/image/top_location.png)

![alt text](https://raw.githubusercontent.com/david880110/Citi-Bike-Analytics/master/image/avg_bike_distance.png)

![alt text](https://raw.githubusercontent.com/david880110/Citi-Bike-Analytics/master/image/popularity_over_time.png)

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
<td>Feb 11th 2019, 06:43:41 am</td>
<td>506 KB</td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201902-citibike-tripdata.csv.zip">JC-201902-citibike-tripdata.csv.zip</a></td>
<td>Mar 4th 2019, 08:21:48 am</td>
<td>480 KB</td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201903-citibike-tripdata.csv.zip">JC-201903-citibike-tripdata.csv.zip</a></td>
<td>Apr 15th 2019, 11:34:52 am</td>
<td>609 KB</td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201904-citibike-tripdata.csv.zip">JC-201904-citibike-tripdata.csv.zip</a></td>
<td>May 6th 2019, 12:07:33 pm</td>
<td>847 KB</td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201905-citibike-tripdata.csv.zip">JC-201905-citibike-tripdata.csv.zip</a></td>
<td>Jun 11th 2019, 12:37:55 pm</td>
<td>910 KB</td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201906-citibike-tripdata.csv.zip">JC-201906-citibike-tripdata.csv.zip</a></td>
<td>Jul 15th 2019, 10:42:09 am</td>
<td>1.02 MB</td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201907-citibike-tripdata.csv.zip">JC-201907-citibike-tripdata.csv.zip</a></td>
<td>Aug 5th 2019, 02:34:01 pm</td>
<td>1.13 MB</td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201908-citibike-tripdata.csv.zip">JC-201908-citibike-tripdata.csv.zip</a></td>
<td>Sep 18th 2019, 01:33:15 pm</td>
1.26 MB
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201909-citibike-tripdata.csv.zip">JC-201909-citibike-tripdata.csv.zip</a></td>
<td>Oct 11th 2019, 12:42:04 pm</td>
<td>1.27 MB</td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201910-citibike-tripdata.csv.zip">JC-201910-citibike-tripdata.csv.zip</a></td>
<td>Nov 5th 2019, 02:10:56 pm</td>
<td>1.09 MB</td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201911-citibike-tripdata.csv.zip">JC-201911-citibike-tripdata.csv.zip</a></td>
<td>Dec 20th 2019, 10:44:56 am</td>
<td>781 KB</td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201912-citibike-tripdata.csv.zip">JC-201912-citibike-tripdata.csv.zip</a></td>
<td>Jan 21st 2020, 01:23:33 pm</td>
<td>505 KB</td>
<td>ZIP file</td>
</tr>
</tbody>
</table>

* Limitation
I was unable to get most of the Gender demographics to work correctly.


## Findings 


### (1) The current major citi bike riders fall into younger population group between 18 - 20 as there is also an increases over time as they are showing interest to start riding during the weekend

![alt text](https://raw.githubusercontent.com/david880110/Citi-Bike-Analytics/master/image/femal_ridership.png)

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

