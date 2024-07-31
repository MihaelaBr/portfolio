---
layout: post
title: Capstone project - Bike-Sharing Services
description: Data Analytics, SQL and Visualisation project
image: assets/images/imgmain/Cyclistic_Case_Study_Page1.png
href: c_bikesharing.html
---

This Case Study on Bike-sharing services was a Capstone Project prepared during my Google Data Analytics Certificate studies in Coursera. Maximising the number of annual members is considered the key to the company’s future success which is why the marketing team is interested in analysing Cyclistic historical bike trip data to identify trends. The goal of this project is to understand how casual riders and annual members use Cyclistic (a fictional company) bikes differently. Data-backed recommendations are needed to create a new marketing strategy to convert casual riders into annual members.

Historical trip data was downloaded for the period of 1 year, one file for each month. Data, in CSV format, was ingested into Google BigQuery using Google Cloud Storage buckets as most files were larger than 100MB. Data quality and structure was assessed using SQL on a sample 1 month of the data. Data was then cleaned removing incomplete records, making sure there are no duplicates. All 12 months data was combined in one table (~1GB) . Then new columns for ride duration as time and ride duration in seconds were added as well as a column for day of the week, extracted from the time existing field for ride start. Finally all rides below 60sec duration, including negative ones, as clear errors were excluded from the final file. The prepared data was then uploaded in [Tableau Public](https://public.tableau.com/views/CyclisticCaseStudy_17210605199230/CyclisticCaseStudy?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link) for further data analysis and visualisation.

The project concludes with recommendations for the marketing campaign:

- Places with good pedestrian visibility and traffic around the top 10 most used stations should be targeted for physical ads placement
- Digital ads based on device location (matching these stations) of the app users should also be used to inform casual riders of the benefits of becoming members
- These efforts could be further enhanced by releasing ads in the specific peak hours, days and months discovered during the analysis

Published in the project [GitHub repo](https://github.com/MihaelaBr/Bike-sharing-project) are data quality checks and cleaning process in SQL, along with samples (CSV format) for the raw and cleaned data.

