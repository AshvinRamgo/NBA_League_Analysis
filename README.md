# NBA_League_Analysis and Visualization 

Data Source: <br>
The NBA Overall Team Data from 2000-2023 was pulled as a csv file from: https://www.kaggle.com/datasets/bluedreamv1b3/nba-teams-stat-2000-2023/data
while the NBA 2023 Player data was pulled as a csv file from https://www.kaggle.com/datasets/bluedreamv1b3/nba-teams-stat-2000-2023/data 


Data Cleaning: <br>
Using Pandas and NumPy, the Data was cleaned: 
Taking care of Null Values in the Data Set and also altering some Non-Null Values to my preference, for easier analysis. 
I also changed some of the names of teams and postions which were previously abbreviated to the full names for visualization.
Finally, the data was then formatted, unnecessary columns were removed and sorted to my preference.
(Note each step is explained via comments in the Jupyter Notebook) <br>

After cleaning: <br>
The first row of the NBA Overall Team Data  CSV file contains the headers for the file, with each subsequent row providing details: 
The headers in the file are:
  * Index
  * Rank
  * Team
  * Age
  * Wins
  * Losses
  * Strength of Schedule
  * Simple Rating System
  * Defensive Rating   
  * Offensive Rating
  * Net Rating
  * Pace
  * Free Throw Rate
  * Three-Point Attempt Rate
  * Arena
  * Attendance
  * Venue
  * Year

The first row of the NBA 2023 Player Data  CSV file contains the headers for the file, with each subsequent row providing details: 
The headers in the file are:
  * Name
  * Team
  * Position
  * Age
  * Games Played  
  * Minutes Per Game
  * Usage Percentage    
  * Turnover Percentage   
  * Free Throw Attempts                      
  * Free Throw Percentage  
  * Two-Point Attempts
  * Two-Point Percentage 
  * Three-Point Attempts 
  * Three-Point Percentage 
  * Effective Field Goal Percentage
  * True Shooting Percentage   
  * Points Per Game
  * Rebounds Per Game 
  * Assists Per Game
  * Steals Per Game 
  * Blocks Per Game 
  * Turnovers Per Game 
  * Points and Rebounds per game  
  * Points and Assists per game 
  * Points + Rebounds + Assists per gam
  * Total Points   
  * Total Rebounds  
  * Total Steals 
  * Total Blocks  
  * Total Turnovers
  * Total Points and Rebounds
  * Total Points and Assists  
  * Total Points, Rebounds, and Assists
  * Points, Rebounds, and Assists per game


Data Visualization:
Using Pandas, NumPy, Matplotlib and Seaborn; I explored, analysed and visualized the cleaned data; extracting several useful statistics and creating pivot Tables, plotting barcharts, piecharts, Stripplots etc. 

The entire list of Stats Derived is given below: 

OVERALL: 
(Analysis on teams from 2000-2023 NBA)
1.	List of Seasons
2.	List of Venues
3.	List of Teams
4.	Number of Times Each team played in the NBA (2013-2023)
5.	Number of matches played at Each venue (2013-2023)
6.	Teams with the most wins (2013-2023)
7.	Teams with the most losses (2013-2023) 
8.	The 6 Teams with Highest Average Free Throw Rate (2013 - 2023)
9.	The 6 Teams with Highest Average Three-Point Attempt Rate (2013 - 2023)

2023 NBA SEASON ANALYSIS: 
(Analysis on teams only in 2023 NBA)
1. List of Teams
2. List of Venues
3. Number of matches played at each Venue
4. The 6 teams with the most wins
5. The 6 teams with the most losses
6. The Free Throw Rate for each team
7. The Three Point Attempt Rate for each team

NBA PLAYER SCORING ANALYSIS: 
(Only 2023 Season)
1. The 10 Players with the highest total points
2. The 10 Players with the lowest total points
3. The 10 Players with the players with the most games played
4. The top 10 Players with the Highest Average Points per Game
5. The top 10 Players with the Lowest Average Points per Game
6. The top 10 Players with the most Assists
7. The top 10 Players with the least Assists
8. The top 10 Players with the Highest Number of Free Throw Attempts
9. The top 10 Players with the Highest Number of Three Pointer Attempts

NBA PLAYER DEFENDING ANALYSIS: 
(Only 2023 Season)
1. The top 10 Players with the Most Total Rebounds
2. The top 10 Players with the Most Rebounds per Game
3. The top 10 Players with the Lowest Rebounds Per Game 
4. The top 10 Players with the Most Total Steals
5. The top 10 Players with the Highest Steals per Game 
6. The top 10 Players with the Lowest Steals per Game
7. The top 10 Players with the Most Total Blocks 
8. The top 10 Players with the Highest Blocks per Game 
9. The top 10 Players with the Lowest Blocks per Game 
10. The top 10 Players with the Most Turnovers 
11. The top 10 Players with the Most Turnovers per Game 
12. The top 10 Players with the least Turnovers per Game 


OVERALL PLAYER STATS:
(Only 2023 Season)
1. The top Players with the Most Points and Rebounds
2. The top Players with the Most Points and Assists
3. The top Players with the Most Points, Rebounds, and Assists
4. The top Players with the Most Points and Rebounds Per Game 
5. The top Players with the Most Points and Assists Per Game 
6. The top Players with the Most Points, Rebounds Assists Per Game 





 
  
