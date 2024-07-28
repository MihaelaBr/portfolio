---
title: 'Spotify Data - EDA'
layout: landing
description: 'Python Programming, Jupyter NB and Visualisation project'
image: assets/images/imgmain/ZOA_concert_2022_mb_bw.jpg
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
		<p>This is a personal project for Exploratory Data Analysis (EDA) and Visualisations created using Python Jupyter Notebooks with the data from my personal Spotify account.</p>
	</div>
</section>

<!-- Two -->
<section id="two" class="spotlights">
	<section>
		<a href="embedded_spotify_ipynb.html" class="image">
			<img src="{{ site.baseurl }}/assets/images/pic08.jpg" alt="" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Data and process</h3>
				</header>
				<p>Data was provided by Spotify after an official request in April 2024. All initial files provided by Spotify came in JSON format, so in order to have a clearer idea of what is inside the data, one main file with my account's music streaming history (StreamingHistory_music_0.json) was converted to XLSX format. It was then assessed and prepared for analysis inside Google Sheets, for example new column named 'Include Song' was added, based on the time a song was played. After that the file's data was loaded in a Jupyter Notebook where it went through several steps of processing and data visualisation using pandas, matplotlib, numpy and seaborn Python Libraries. </p>
			</div>
		</div>
	</section>
	<section>
		<a href="embedded_spotify_ipynb.html" class="image">
			<img src="{{ site.baseurl }}/assets/images/imgsmall/Spotify_top10_songs.png" alt="" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Results</h3>
				</header>
				<p>The Python Jupyter Notebook, the cleaned and ready for analysis file (XLSX) as well as the raw data (JSON) was added to a github repository. It does not contain any PII.</p>
				<ul class="actions">
					<li>
						<a href="https://github.com/MihaelaBr/Spotify-project" class="button" target="_blank">GitHub repo</a>
					</li>
				</ul>
			</div>
		</div>
	</section>
	<section>
		<a href="embedded_spotify_ipynb.html" class="image">
			<img src="{{ site.baseurl }}/assets/images/imgsmall/Spotify_to20_artists.png" alt="" data-position="top center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Inspiration</h3>
				</header>
				<p>The project was inspired by a Women in Data Science (WiDS) Workshop on using Python for Spotify data analysis. I used it as an initial template to work with my own data and built on top of it in terms of visualisations features, metrics used and added, data analysed. Check out the workshop for steps on requesting your Spotify data. </p>
				<ul class="actions">
					<li><a href="https://youtu.be/2zaGRy54SV8?si=QNzIRVmkHMug-Sbx" class="button" target="_blank">WiDS Workshop</a></li>
				</ul>
			</div>
		</div>
	</section>
</section>

</div>
