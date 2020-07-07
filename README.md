# First Innings Score Prediction - Indian Premier League (IPL)
![Python 3.6](https://img.shields.io/badge/Python-3.6-brightgreen.svg) ![NLTK](https://img.shields.io/badge/Library-sklearn-orange.svg)

### Problem statement:
Build a model to predict the score (in terms of range) of any IPL match.

### Dataset:
The dataset _'ipl.csv'_ consists of ball-to-ball informations about every match of IPL from __Season 1 to 10__ ie: (2008 to 2017)<br/>
Dataset consists following columns:<br/>
_• mid: Unique match id._<br/>
_• date: Date on which the match was played._<br/>
_• venue: Stadium where match was played._<br/>
_• bat_team: Batting team name._<br/>
_• bowl_team: Bowling team name._<br/>
_• batsman: Batsman who faced that particular ball._<br/>
_• bowler: Bowler who bowled that particular ball._<br/>
_• runs: Runs scored by team till that point of instance._<br/>
_• wickets: Number of Wickets fallen of the team till that point of instance._<br/>
_• overs: Number of Overs bowled till that point of instance._<br/>
_• runs_last_5: Runs scored in previous 5 overs._<br/>
_• wickets_last_5: Number of Wickets that fell in previous 5 overs._<br/>
_• striker: max(runs scored by striker, runs scored by non-striker)._<br/>
_• non-striker: min(runs scored by striker, runs scored by non-striker)._<br/>
_• total: Total runs scored by batting team at the end of first innings._<br/>

Algorithms Used:
• Linear Regression_<br/>
• Ridge Regression_<br/>
• Lasso Regression_<br/>
• Grid SearchCV for hyper parameter tuning_<br/>
