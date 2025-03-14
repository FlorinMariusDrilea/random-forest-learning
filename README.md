# Prediction of EPL games based on data scrapped from fbref website
- Using scraping-football.ipynb, I scraped football data stats that are transformed in random-forest-learning.ipynb and using one of the 2 prediction algorithms (XGBOOST or Rnadom Forest), we predict the results.
- Using a data set splitted by date we have the following results:

Accuracy predicted at the moment: 57% 

Index of data used:
- Date
- Time
- Home Team
- XGH (expected goals home team)
- Away Team
- XGA (expected goals away team)
- Score
- FTHG (full time home goals)
- FTAG (full time away goals)
- HTGDIFF (home team goal difference)
- ATGDIFF (away team goal difference)
- Result (target value)
- Referee
- STH (shoots on target home team)
- STA (shoots on target away team)
