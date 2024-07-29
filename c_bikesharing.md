---
title: 'Bike-Sharing Services'
layout: landing
description: 'Google Data Analytics Certificate <br />Data Analytics, SQL and Visualisation project'
image: assets/images/imgmain/bike_shark_zh_mb.jpeg
nav-menu: true
---

<!-- Main -->
<div id="main">

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h2>Brief Overview</h2>
		</header>
		<p> This Case Study on Bike-sharing services was a Capstone Project prepared during my Google Data Analytics Certificate studies in Coursera. Maximising the number of annual members is considered the key to the company’s future success which is why the marketing team is interested in analysing Cyclistic historical bike trip data to identify trends. The goal of this project is to understand how casual riders and annual members use Cyclistic (a fictional company) bikes differently. Data-backed recommendations are needed to create a new marketing strategy to convert casual riders into annual members.  </p>
	</div>
</section>

<!-- Two -->
<section id="two" class="spotlights">
	<section>
		<a href="https://github.com/MihaelaBr/Bike-sharing-project" class="image">
			<img src="{{ site.baseurl }}/assets/images/imgsmall/SQL_BQ_Bikesharing_Flow.png" alt="" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Pre-processing and Data Wrangling</h3>
				</header>
				<p> Historical trip data was downloaded for the period of 1 year, one file for each month. Data, in CSV format, was ingested into Google BigQuery using Google Cloud Storage buckets as most files were larger than 100MB. 
Data quality and structure was assessed using SQL on a sample 1 month of the data. Data was then cleaned removing incomplete records, making sure there are no duplicates. All 12 months data was combined in one table (~1GB) . Then new columns for ride duration as time and ride duration in seconds were added as well as a column for day of the week, extracted from the time existing field for ride start. Finally all rides bellow 60sek duration, including negative ones, as clear errors were excluded from the final file. The prepared data was then uploaded in Tableau Public for further data analysis and visualisation.  </p>
			</div>
		</div>
	</section>
	<section>
		<a href="embedded_tableau_cyclistic.html" class="image">
			<img src="{{ site.baseurl }}/assets/images/imgsmall/Cyclistic_Page1_small.png" alt="" data-position="top center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Results</h3>
				</header>
				<p>After preparing and cleaning the data I ingested it into Tableau for further analysis and visualisations preparation. Published in the project GitHub repo are data quality checks and cleaning process in SQL, along with a 1000 rows samples in CSV format for the raw and cleaned data respectively and a Tableau Public Dashboard with two separate pages for Stations Analysis and Time-series Analysis. The project finishes with recommendations for the marketing campaign to be created by the marketing team in order to convert more casual riders into members. Click on the picture for a more detailed interactive view of the dashboards.</p>
				<ul class="actions">
					<li><a href="https://github.com/MihaelaBr/Bike-sharing-project" class="button" target="_blank">GitHub Repo</a></li>
					<li><a href="https://public.tableau.com/views/CyclisticCaseStudy_17210605199230/CyclisticCaseStudy?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link" class="button" target="_blank">Tableau</a></li>
				</ul>
			</div>
		</div>
	</section>
</section>
