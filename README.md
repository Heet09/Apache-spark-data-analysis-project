# Apache-spark-data-analysis-project

This project involves analyzing the Indian Premier League (IPL) dataset of 2017 using Apache Spark on a Databricks environment. The data is stored on Amazon S3, and have utilized Spark SQL for data transformation and analysis. The project aims to find insights and visualize various aspects of the IPL data.

Overview of Apache Spark
Apache Spark is an open-source unified analytics engine designed for large-scale data processing. It provides an interface for programming entire clusters with implicit data parallelism and fault tolerance. Spark is known for its speed and ease of use, offering APIs in Java, Scala, Python, and R. Key components of Spark include:

Spark Core: The underlying execution engine for the Spark platform, responsible for memory management, fault recovery, scheduling, and interacting with storage systems.
Spark SQL: Enables users to run SQL queries and perform data transformations on structured data.
Spark Streaming: Allows for real-time data processing.
MLlib: A library for scalable machine learning.
GraphX: For graph processing.
Project Overview
Performed the following steps in project:

1. Data Storage: Upload the IPL dataset to Amazon S3 for storage.
2. Data Processing: Use Databricks workspace to write Spark code for data transformation.
3. Data Analysis: Write SQL queries to analyze the data and uncover insights.
4. Visualization: Create visualizations to better understand the dataset and present the findings.

Project Architecture:

  <img width="1464" alt="architecture" src="https://github.com/Heet09/Apache-spark-data-analysis-project/assets/64312275/588cc7fe-61c2-4e59-bb2f-3cc0faa136bd">

# Use of Databricks and Apache Spark in this Project

In this project analyzing the IPL dataset of 2017 using Apache Spark on Databricks, I utilized Amazon S3 for scalable storage of the dataset. 
Within the Databricks environment, I wrote Spark code to transform the data, performing tasks such as cleaning, filtering, and aggregating to prepare it for analysis. 
Spark SQL was instrumental for running SQL queries on the transformed data, enabling insights like total runs scored by each team, top wicket-takers, and match outcomes based on various factors. 
Finally, I used Matplotlib and Seaborn to create visualizations like bar charts for team performance, line graphs tracking player stats, and pie charts illustrating win/loss ratios to effectively present my findings.

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

