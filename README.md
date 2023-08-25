# top-selling-albums
Analysis of the Top 10 Selling Albums from 1990-2021.
# Top 10 Selling Albums Chart  Analysis
#Using SQL and Power BI
Scenario: <br>

In this project, I did an analysis of the trend in album sales over the years. The dataset used was posted on Kaggle. It includes the data about the top 10 best selling albums each year, from 1990 to 2021. The data about the album name, artist name, album length, total sales and genre is included. 
<br><br>

Dataset Used: <br>
[Best Selling Albums By Duration (1990-2021)
](https://www.kaggle.com/datasets/nickadair44/top-10-annual-best-selling-albums-by-length)
<br><br>

Tasks:<br>
1.	Which are the Top Selling Albums from 1990-2021
2.	Who are the Top Selling Artists?
3.	Was there a rise or a fall in sales over the years?
4.	How does genre affect sales?
5.	How many CDs are generally included in the top sellers?
6.	How does number of tracks affect sales? <br><br>

Process:<br>
The analysis was does using SQL, in BigQuery. See [queries]( https://github.com/sayalisa2li7/top-selling-albums/tree/main/analysis-queries). The query [outputs]( https://github.com/sayalisa2li7/top-selling-albums/tree/main/analysis-results) were stored as CSV files and then imported into Power BI to create [dashboards]( https://github.com/sayalisa2li7/top-selling-albums/tree/main/analysis-dashboards) and [visualizations]( https://github.com/sayalisa2li7/top-selling-albums/blob/main/analysis-visualizations.pdf).
<br><br>

Key Findings: 
* The total worldwide sales estimate has gone down over the years, peaking at 202M in 1991. The total sales dropped down to about 30M in 2021.
* The top 10 artists with the most entries on the chart are not the same as the top 10 artists with most sales. This could be because albums are differently priced. 
* Albums with 12 tracks have sold the most units. As the number of tracks in an album increases, the total sales increases. The most selling albums have 10-14 tracks. This shows that the audience does not prefer too long or even too short albums.
* Pop was the best selling album genre during the years 1990-2021, accounting for 41.4% of the total sales. Out of the 32 Number 1 Best Selling Albums, 19 (59.38%) were Pop Albums. The 'Genre Sales Over The Years' Chart shows that Pop and Rock are the most stable genres in terms of sales.

* Out of the 320 Top 10 Selling Albums, 308(96.25%) include only 1 CD. All of the Rank 1 Top Selling Albums include only 1 CD. The sum of sales for albums with only 1 CD is much more than the sum of sales for albums with 2 CDs and 4 CDs combined.

<br><br>

See [Dashboards]( https://github.com/sayalisa2li7/top-selling-albums/tree/main/analysis-dashboards). <br><br>

See [Visualizations]( https://github.com/sayalisa2li7/top-selling-albums/blob/main/analysis-visualizations.pdf). 
