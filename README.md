# Soccermetrics
Exploring historical soccer data and predicting the World Cup 2018 results

This repository contains three parts:

a.) Data - "results.csv"

b.) Data Exploration & Visualization - "Soccermetrics- Visualization.ipynb"

c.) Predicting the winner of the 2018 World Cup - " "


## Data:
This dataset contains 39,054 results of international soccer matches from 1872 onwards. 
Mart Jurisoo was kind enough to post this dataset on Kaggle after pulling it from wikipedia, fifa.com, rsssf.com and individual associations' websites: [https://www.kaggle.com/martj42/international-football-results-from-1872-to-2017] 

results.csv includes the following columns:

date - date of the match

home_team - name of the home team

away_team - name of the away team

home_score - full time home team score including extra time, not including penalty-shootouts

away_score - full time away team score including extra time, not including penalty-shootouts

tournament - name of the tournament

city - name of the city/town/administrative unit where the match was played

country - name of the country where the match was played

neutral - TRUE/FALSE column indicating whether the match was played at a neutral venue


## Data Exploration & Visualization:
I wanted a explore the "International football results from 1872 to 2018" dataset and examine how the game has changed over the years in terms of goals scored, nation participation, which countries were dominating different eras, and more.

To begin with, I checked that the dataset was complete (it was) and added a few columns that would aid with my analysis:
Winning team, Losing Team, Total Goals Scored, Year and Decade


In the current version of the notebook I have the following visualizations: 
Top 10 Countries with Most Games Won, 
Top 10 Countries with Most Competitive Games Won (no friendlies), 
Top 10 Countries by Decade, 
Goals per Game Ratio by Year


In the future, I am planning on:
Breaking down matches won by tournament type, 
Tracking win percentages by team through the years, 
Adding geographical analysis (continents), 
Looking at statistical differences results for teams playing home vs away


## Predicting the winner of the 2018 World Cup:
