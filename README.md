# NBA Player Stats 2022-2023 Season Analysis

## Project Overview

This project uses NBA player stats from the 2022-2023 season to understand how points correlate with overall player performance.

Using Python, I explored patterns in over 670 observations to identify how points correlate with other player performance metrics.

-------

## Dataset

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
  - FG / FGA / FG%: Field goal stats
  - 3P / 3PA / 3P%: 3-point stats
  - 2P / 2PT / 2P%: 2-point stats
  - FT / FTA / FT% Free throw stats
  - ORB / DRB / TRB: Rebounding stats
  - AST: Assists per game
  - STL: Steals per game
  - BLK: Blocks per game
  - TOV: Turnovers per game
  - PF: Personal fouls per game
  - PTS: Points per game

----------
## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Sklearn

----------

## Exploratory Analysis

This project explored the following:
  - Distribution of players by age group
- Relationships between points per game and:
  - Rebounds
  - Assists
  - Minutes
  - Games played
- Predictive modeling of player scoring using:
  - Naive Bayes (classification)
  - K-Nearest Neighbors (regression)

------------
## Key Visualizations

This analysis includes:
- Pie graph showing the distribution of players by age group
- Bar graphs comparing points with:
  - Total rebound
  - Assists
  - Minutes
  - Games played
- Confusion Matrix for predicting points
- Scatter Plot for:
  - KNN predicted vs actual values (k=7 and k=4)

----------
## Key Findings

- The majority of players are in their 20s -> 69%
- Points per game shows a positive relationship with minutes played and usage related metrics
- higher scoring players tend to contribute more across multiple statistical categories, though the stength of relationships varies by metric
- Naive Bayes model achieves a 85% accuracy in classifying scoring levels
- KNN regression performed best at k=7, producing more stable predictions than k=4











