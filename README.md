# Analyzing-English-Premier-League-Standings
Analyzing English Premier League Standings: A Comprehensive R Function for Dynamic Match Data Processing

### Background
The English Premier League (EPL) is one of the most popular and competitive soccer leagues globally, featuring 20 teams that compete from August to May each year. Each team plays 38 matches per season, resulting in a total of 380 matches. Teams earn 3 points for a win, 1 point for a draw, and no points for a loss. This project focuses on developing an analytical understanding of EPL match results by creating a function in R that retrieves and processes match data to generate league standings for a specific date and season.

### Executive Summary
This project entails the creation of a custom R function named EPL_Standings, which generates the league standings based on user-specified date and season inputs. The function is designed to handle data variations and inconsistencies and includes data cleaning, transformation, aggregation, and sorting to provide a comprehensive summary of team performance up to the specified date. The analysis specifically uses data from the three most current seasons of the English Premier League.

### Goals of Analysis
- Develop a function (EPL_Standings) to retrieve EPL match results from the web 
- Process the data to calculate key statistics for each team.
- Display the league standings based on points per match and other tie-breaking criteria.
- Ensure the function handles the most recent three seasons of EPL data accurately.

### Methodology
- Data Retrieval: The function accesses EPL game results from online sources for the specified season. The analysis is limited to the three most current seasons: 2021/22, 2022/23, and 2023/24.
- Data Cleaning: Ensures consistency in date formats and column names across different seasons.
- Data Transformation: Filters the dataset to include only matches played up to the specified date.
- Data Aggregation: Combines home and away results, calculates wins, losses, draws, goals scored, goals allowed, points, and other relevant statistics.
- Data Sorting: Arranges the final standings based on points per match, wins, goals scored per match, and goals allowed per match.

### Key Insights
- Performance Metrics: The function calculates essential performance metrics such as points per match, point percentage, goals scored per match, and goals allowed per match.
- Team Comparison: Provides a detailed comparison of team performance, enabling a clear view of standings based on multiple criteria.
- Dynamic Updates: The function can handle current season data dynamically, updating standings as new matches are played.
  
### Recommendation
- Data Validation: Regularly validate and clean the dataset to maintain accuracy.
- Feature Expansion: Consider adding more features to the function, such as trend analysis over multiple seasons or player-specific performance metrics.
- User Interface: Develop a user-friendly interface to allow non-technical users to easily access and interpret the league standings.


