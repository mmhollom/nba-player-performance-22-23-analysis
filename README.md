# NBA Player Stats 2022-2023 Season Analysis

## Project Overview

This project uses NBA player stats from the 2022-2023 season to understand how points correlate with overall player performance.

Using Python, I explored patterns in over 670 observations to identify how points correlate with other player performance metrics.

-------

## Datatset

Dataset: NBA Player stats dataset for the 2022-2023
Source: Kaggle

https://www.kaggle.com/datasets/bryanchungweather/nba-players-data-2022-2023?select=nba_2022_2023.csv

The dataset includes:
  - Player: Player's Name
  - Pos: Position
  - Age: Player's Age
  - Tm: Team
  - G: Games Played
  - MP: Minutes played per game
  - FG: Field goals per game
  - FGA: Field goal attempts per game
  - FG%: Field goal percentage
  - 3P: 3-point field goals per game
  - 3PA: 3-point field goal attempts per game
  - 3P%: 3-point field goal percentage
  - 2P: 2-point field goals per game
  - 2PA: 2-point field goal attempts per game
  - 2P%: 2-point field goal percentage
  - eFG%: Effective field goal percentage
  - FT: Free throws per game
  - FTA: Free throw attempts per game
  - FT%: Free throw percentage
  - ORB: Offensive rebounds per game
  - DRB: Defensive rebounds per game
  - TRB: Total rebounds per game
  - AST: Assists per game
  - STL: Steals per game
  - BLK: Blocks per game
  - TOV: Turnovers per game
  - PF: Personal fouls per game
  - PTS: Points per game

----------
## Tools Used

- python
- pandas
- numpy
- matplotlib
- seaborn
- sklearn

----------

## Exploratory Analysis

This project explored the following:
  - Distribution of players by age group
  - Points vs other key player performance metrics including rebounds, assists, minutes, and games played
  - How well can Naive Bayes and KNN predict player performance

------------
## Key Visualizations

This analysis includes:
- Pie graph showing the distribution of players by age group
- Bar graphs for:
  - Total rebounds per game vs points
  - Assists per game vs points
  - Minutes per game vs points
  - Games played ve points
- Confusion Matrix for predicting points
- Scatter Plot for:
  - Original KNN predicted vs actual (k=7)
  - New KNN predicted vs actual (k=4)

----------
## Key Findings

- Most players (69%) are in their 20s
- Players who average 30+ points per game also lead in total rebounds, assists, minutes, and games played
- Naive Bayes model yielded a 85% accuracy and preformed well for classification
- K=7 is the preffered regression model for predicting points compared to when k=4











