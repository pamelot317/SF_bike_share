# SF_bike_share
STA 141 final project

<p> <strong>The origin of data sets</strong><br>
We came across the 'old' data sets of two years (2013 - 2014, 2014 - 2015) on the <a href = 'https://www.kaggle.com/benhamner/sf-bay-area-bike-share'> Kaggle </a> datasets.
Upon doing a little research, we found the original site, the <a href = 'http://www.bayareabikeshare.com/open-data'> Bay Area Bike Share company </a>,  that makes regular open data releases and maintain a real-time API. Now, we have data sets for three distinct years in 'sqlite' and 'csv' formats, and if need be, we can always retreive current data too through their API.
</p>
<p>
	
	<strong>The data files</strong><br>
	There are 4 different data sets for each year:
	<ol>
		<li>"Station" with about 100 rows and 7 columns</li>
		<li>"Status" with about <strong>100 Million</strong> rows and 4 columns</li>
		<li>"Trip" with about <strong>1 Million</strong> rows and 1 columns</li>
		<li>"Weather" with about 5000 rows and 24 columns</li>
	</ol>
</p>

<p> <img src="http://www.sfbike.org/wp-content/uploads/2014/03/BikeShare-diagram.jpg">
	<strong>Bike Sharing 101</strong><br>
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

This <a href = 'https://code.tutsplus.com/articles/team-collaboration-with-github--net-29876'> tutorial </a> is very useful to review how to do collaboration on Github. Check it out.

</p>












