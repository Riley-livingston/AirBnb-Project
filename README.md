<img src="https://i.imgur.com/KAKciod.jpg" height = "100%" width="100%" alt = ">Airbnb Analysis for Cleaning Services"/>

<h1>Airbnb Analysis for Cleaning Services in NYC - Active Directory </h1>
<h2>Key Findings</h2>
Put key findings in this space. Shoert and sweet explanatoin of what you found and why it matters in the context of the business problem


<h2>Authors</h2>

<a href="https://github.com/Riley-livingston"> @RileyLivingston</a>

<h2>Description</h2>
This project consists of exploritory analysis of publicly available Airbnb data. This directory will guide you through the steps I took and thought process in formulating a client list for an Airbnb cleaning service in New York City.

<br />

<h2>Languages and utilities used</h2>

- <b>MySQL</b> 
- <b>Tableau</b>

<h2>Environments used </h2>

- <b>DBeaver 22.2.2</b>

<h2>Data source</h2>

- <a href="https://drive.google.com/drive/folders/1Q2yFaDajfJ6hALKMCmrQbHnFhsti44bO?usp=sharing"> Airbnb detailed listings and reviews data NYC 09-07-2022</a>
- <a href="https://docs.google.com/spreadsheets/d/1iWCNJcSutYqpULSQHlNyGInUvHg2BoUGoNRIGa6Szc4/edit#gid=1322284596"> Data dictionary</a>

<h2>Methods</h2>

- <b>Exploratory data analysis</b>

<h2>Data Analysis Process:</h2>

<p align="left">
 <u>Business task</u>:
 
- <b>Determine a high conversion rate client list that can be utulized by airbnb cleaning services in NYC using exploratory analysis.</b>
 
  -<b> KEY METRICS: 
    - <b>number of distinct reviews that contain words signaling uncleanliness grouped by host
    - <b>number of distinct reviews that contain words signaling uncleanliness per listing grouped by host
 

<br />
<br />
<p align="left">
 <u>Data preparation</u>: 
 
 -<b> PRIVACY AND ACESSABILITY:
 
   - Data for this analysis was scrapped directly from Airbnb's website by third party <a href="https://insideairbnb.com"> insideairbnb</a>.
   - All data present in this repository as well as findings derived from analysis is publicly available information and falls under fair use. No private         information is being used including names, listings, and review details as it is all publicly displayed on Airbnb’s website.
 
<br />
<br />
Documentation of data processing and cleaning: <br/>
  - <a href="https://github.com/Riley-livingston/AirBnb-Project/blob/main/clean_and_filtered_airbnb_mysql_script_v1.sql"> SQL script to clean and filter the data.sql</a>
<br />
  - <a href="https://github.com/Riley-livingston/AirBnb-Project/blob/main/clean_and_filtered_airbnb_data_v2.csv"> Cleaned and filttered data.csv</a>
 <br />
 <br />
<img src="https://i.imgur.com/ZkfqMyt.png" height = "100%" width="100%" alt = ">SQL select statement with explaination"/>
   </b>- dsfdsfdsfdsfsd</b>
 <br />
 <br />
<img src="https://i.imgur.com/Fr7ChSk.png" height = "100%" width="100%" alt = ">SQL Join statement and conditions for dirty reviews with explaination"/>
   - dfdsfdgdfgfdg
 <br />
 <br />
<img src="https://i.imgur.com/Q31eJA5.png" height = "100%" width="100%" alt = ">SQL more filtering and group by order by conditions with explaination"/>
  - dfdfdgfdgdfgdf
<br />
<br />
<br />
Analysis:  <br/>

<br />
<br />
 <u> key findings</u>:
<br/>
<br/> 
 - <b>VIZ PREVIEW:
   <img src="https://i.imgur.com/hs9FuEm.png" height = "100%" width="100%" alt = "Results Snapshot: Top 25 Hosts sorted by dirty reviews per listing"/>
 - <a href="https://public.tableau.com/app/profile/riley.livingston/viz/Airbnbdirtyreviewproject/Dashboard1?publish=yes"> Tableau | Dashboard</a>
<br />
<br />
 - <b>VIZ PREVIEW:
   <img src="https://i.imgur.com/lOKLiWT.png" height = "100%" width="100%" alt = "Results Snapshot: Distribution and percentiles of Dirty Reviews per listing grouped by host"/>
 - <a href="https://public.tableau.com/app/profile/riley.livingston/viz/Airbnbdirtyreviewproject/Dashboard2?publish=yes"> Tableau | Dashboard </a>
<br />
<h2>Limitations and what can be improved </h2>
 - <b>The data and results of the analysis are a snapshot of listings available on Airbnb on September 7th 2022. Hosts may remove or add listings at anytime and renters may post or delete reviews at anytime which may impact the results of the analysis. Seasonality bias may be present in the number of reviews that contain 'dirty' words indicating uncleanliness.</b>
<br />
<br />
 - The words used to measure dirty reviews are all weighted the same but each dirty review may differ in the severity of the uncleanliness which would impact bookings and be of greater interest to a cleaning service looking for clients.
<br />
<br />
 - A list of 15 words was selected to search for dirty reviews in the communts column of the reviews table. This list may not represnted all of the ways a person would describe unclenliness and leading to some reviews not being counted anf included in the analysis.

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
