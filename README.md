# World Cup Database
This project is the second project in the freeCodeCamp Relational Database Certification. In this project I build a relational PostgreSQL database to store and query data from the 2014 and 2018 World Cup games. The project involves writing Bash scripts to insert data and extract insights through SQL queries.

## Overview
- Design and build a PostgreSQL database named `worldcup`
- Create and populate `teams` and `games` tables from a csv file
- Write SQL queries to analyze the 2014 and 2018 World Cup statistics

## Description
- teams: Information about the names of the teams.
- games: Information about the games in the World Cup (year, round, winner, opponent, number of goals from the winning team, number of goals from the opposing team).
- insert_data.sh: Adds each unique team to the teams table (24 total rows). Adds a row for each match in games.csv (32 total rows) using the team_id values from the teams table.
- queries.sh: Includes SQL queries for each prompt using a single-line echo structure. Matches the expected output format (including decimal precision).
