# Football_tournament_analysis
All the data in this dataset where scraped from https://www.worldfootball.net/
UEFA Champions League (UCL) is one of the biggest football competition conducted by Union of European Football Association. Started in 1955, UCL is one of most viewed and anticipated football tournaments in the world.

Content
This dataset contains teams, players details, player stats and records, team managers, matches and their results, goals stadiums and more.

Project Summary

This project is an end-to-end SQL-based analysis of UEFA Champions League matches (2016–2022). The work involved cleaning raw data, designing a normalized relational schema, inserting consistent records, and writing queries for meaningful football insights.

The database design includes relational tables for players, teams, stadiums, managers, matches, tournaments, and goals, with proper keys and constraints to ensure data integrity. After structuring the data, I inserted cleaned records and wrote queries to enable match analysis, player statistics, team performance insights, and tournament-level trends.

This work demonstrates skills in data cleaning, relational database design, and SQL-based sports analytics

1. Data Cleaning & Preparation

The original dataset contained duplicate entries, inconsistent naming conventions, and missing values.

I manually corrected errors in team names, stadium details, and player attributes.

Null or inconsistent records (e.g., missing heights/weights, wrong foreign key mappings) were standardized to ensure referential integrity.

2. Database Design

Created a new database: uclbuzz.

Designed 7+ relational tables (players, player_stats, teams, managers, stadiums, tournaments, matches, goals, match_report) with primary keys, foreign keys, and constraints.

Ensured proper normalization to avoid redundancy and allow complex analytical queries.

Example features:

Foreign keys linking players ↔ teams ↔ matches.

Constraints on attributes (e.g., left/right foot, penalty shootout flag).

Stadium capacity data linked directly with team home grounds.

3. Data Insertion

Inserted cleaned and structured records for:

Tournaments (Champions League seasons from 2016–2022).

Teams with stadium associations.

Stadiums with city, country, and capacity details.

Players and their corresponding attributes (height, weight, position, foot preference).

Match details including attendance, scores, and goals.

4. Analysis Goals (via SQL Queries)

After cleaning and inserting data, SQL queries were designed to extract football insights, such as:

Player-level analysis: Most goals, assists, average player stats per season.

Team-level analysis: Performance trends across seasons, home vs away performance, goal-scoring patterns.

Tournament-level analysis: Stadium attendances, seasonal goal distributions, most competitive matches.

Manager and squad insights: Impact of managers on performance, player distribution by nationality and position.

5. Key Skills Demonstrated

 Data Cleaning & Processing (removing inconsistencies, handling missing data).
 Database Normalization & Relational Schema Design.
 Writing advanced SQL queries for performance analysis and insights.
 Sports Analytics using SQL.
