# Apache-spark-data-analysis-project

This project involves analyzing the Indian Premier League (IPL) dataset of 2017 using Apache Spark on a Databricks environment. The data is stored on Amazon S3, and have utilized Spark SQL for data transformation and analysis. The project aims to find insights and visualize various aspects of the IPL data.

Project Overview
Performed the following steps in project:

1. Data Storage: Upload the IPL dataset to Amazon S3 for storage.
2. Data Processing: Use Databricks workspace to write Spark code for data transformation.
3. Data Analysis: Write SQL queries to analyze the data and uncover insights.
4. Visualization: Create visualizations to better understand the dataset and present the findings.

Project Architecture:

  <img width="1464" alt="architecture" src="https://github.com/Heet09/Apache-spark-data-analysis-project/assets/64312275/588cc7fe-61c2-4e59-bb2f-3cc0faa136bd">


Data Files
Ball_By_Ball.csv
This file contains detailed information about each ball, batting strike rate, wickets information, match number, innings number and much more.

Match.csv
This file contains match-level information such as match ID, teams, date, venue, season yearmatch winner, toss winner and match outcome.

Player.csv
This file contains information about the players including player ID, name, date of birth, batting and bowling skills, role description and country.

Player_match.csv
This file combines individual match and player information to provide details on player performance in each match.

Team.csv
This file contains information about the teams participating in the IPL.

Data source: https://data.world/raghu543/ipl-data-till-2017

