# How bike-sharing has been evolving since 2013 in San Francisco?

<p> <strong>The origin of data sets</strong><br>
We came across the 'old' data sets of two years (2013 - 2014, 2014 - 2015) on the <a href = 'https://www.kaggle.com/benhamner/sf-bay-area-bike-share'> Kaggle </a> datasets.
Upon doing a little research, we found the original site, the <a href = 'http://www.bayareabikeshare.com/open-data'> Bay Area Bike Share company </a>,  that makes regular open data releases and maintain a real-time API. Now, we have data sets for three distinct years <strong>(2013 - 2014, 2014 - 2015, and 2015 - 2016)</strong> in 'sqlite' and 'csv' formats, and if need be, we can always retreive current data too through their API.
</p>
<p>
	
	<strong>The data files</strong><br>
	There are 4 different data sets for each year:
	<ol>
		<li>"Station" with about 100 rows and 7 columns: <br>
		id, name, lat, long, dock_count, city, installation_date</li>
		<li>"Status" with about <strong>100 Million</strong> rows and 4 columns:<br>
		station_id, bikes_available, docks_available, time</li>
		<li>"Trip" with about <strong>1 Million</strong> rows and 1 columns<br>
		id, duration, start_date, start_station_name, start_station_id, end_date, end_station_name, end_station_id, bike_id, subscription_type, zip_code</li>
		<li>"Weather" with about 5000 rows and 24 columns:<br>
		date, max_temperature_f, mean_temperature_f, min_temperature_f, max_dew_point_f, mean_dew_point_f, min_dew_point_f, max_humidity, mean_humidity, min_humidity, max_sea_level_pressure_inches, mean_sea_level_pressure_inches, min_sea_level_pressure_inches, max_visibility_miles, mean_visibility_miles, min_visibility_miles, max_wind_Speed_mph, mean_wind_speed_mph, max_gust_speed_mph, precipitation_inches, cloud_cover, events, wind_dir_degrees, zip_code</li>
	</ol>
</p>

<p> 
	<h4><strong>Bike Sharing 101</strong><br></h4>
	<img src="http://www.sfbike.org/wp-content/uploads/2014/03/BikeShare-diagram.jpg">
	Similar to car sharing, "bicycle sharing" is a membership-based system for short trips throughout the city. Members can check out a bicycle from a network of automated stations, ride to the station nearest their destination, and leave the bicycle safely locked for someone else to use.<br>
	Bike sharing promotes and markets bicycles as transportation that has many benefits. Biking is a clean, affordable, healty and fun way to travel around. Public bike sharing is appealing because it offers 24/7 self-service access to bikes for short trips without the hassle of maintenance or storage.
</p>

<p>
	<strong>The questions that we would like to tackle from</strong>
	<ul><h4>operator/transporation planner point of view:</h4>
		<li>
			<ol>
				<li>How does weather affect usage? This is useful in case the company plans to scale-up and invest in other cities.</li>
				<li>Are there differences in usage between lower income neighborhoods and middle-higher income neighborhoods?
				Where should we do more marketing? Is bike-sharing both affordable and accessible for everyone, not just affluent people in nice neighborhoods, or tourists?</li>
				<li>What are the patterns of usage by day of the week? Time of the day? Month? Season? Hence, how can we resolve issues such as scarcity of bikes? When we should put bike riding time limits so that everyone can use it? Which month and season we need to make more bikes affordable?</li>
				<li>Are the above patterns any different by neighborhood? Again, it boils down to marketing strategy</li>
				<li>What has changed year to year? Is bike-sharing becoming more popular? Are we progressig toward our goal?</li>
				<li>What are the most popular stations and destinations? Most traveled routes? These are important to know to build more stations and invest into more bikes in those areas.</li>

			</ol>
		</li>
		<h4>customer point of view:</h4>
		<li>
			<ol>
				<li>From my home area, where do other people travel to?</li>
				<li>How likely will I find an available dock at a nearby station? Is it different day by day?</li>
				<li>If I want to go to particular place, which trip I should follow? Probably the one that has the densest biking trips since it might mean more safety.</li>
			</ol>
		</li>
	</ul>
</p>

<p>
	<strong>Approach</strong><br>
	In this project, we will perform an Exploratory Data Analysis (EDA) to summarize the data, have a better insight about the dataset, extract important variables, and find any potential relationships between them. The results, will be presented using data visualization techniques. However, prior to these steps, we will need to clean the dataset by eliminating incomplete and inaccurate data through utilizing data wrangling tools.<br>

</p>
<p>

This <a href = 'https://code.tutsplus.com/articles/team-collaboration-with-github--net-29876'> tutorial </a> is very useful to review how to do collaboration on Github. Check it out.

</p>












