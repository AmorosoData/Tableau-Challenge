
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

![alt text](https://raw.githubusercontent.com/AmorosoData/Tableau-Challenge/main/image/miles.png)

![alt text](https://raw.githubusercontent.com/AmorosoData/Tableau-Challenge/main/image/populartime.png)

## Data Source
![alt text](https://raw.githubusercontent.com/AmorosoData/Tableau-Challenge/main/image/citibikeimg.png)

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
<td>1.26 MB</td>
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


## Findings 


### (1) The current major citi bike riders fall into younger population group between 18 - 25. Some data does not make sense as the majority of riders are over 100 years old... Femail ridership for 2019 is at its highest during early spring.

![alt text](https://raw.githubusercontent.com/AmorosoData/Tableau-Challenge/main/image/demo_ride.png)

### (2) The data demostrates that more people are out riding citibike in the summer time versus the winter between the hours of 11pm - 6am. Temperature could potentially be a factor as we all know NY can be quite cold during those winter months. This analysist speculates those bike rides occuring between midnight and 2am would be quite hillarious to witness in person. 

![alt text](https://raw.githubusercontent.com/AmorosoData/Tableau-Challenge/main/image/peakhour.png)

### (3) During winter months people tend not to ride as much because of those cold New York temperatures. For that reason, ridership does not grow during this time.

![alt text](https://raw.githubusercontent.com/AmorosoData/Tableau-Challenge/main/image/Growth.png)

## Map visualization for city officials

* A useful graphic for Citibike logistics. Naturally, they would want to keep more bikes at the top 10 stations to meet the demand, but would need to relocate bikes from the bottom 10 station start locations. 

![alt text](https://raw.githubusercontent.com/AmorosoData/Tableau-Challenge/main/image/planning.png)
