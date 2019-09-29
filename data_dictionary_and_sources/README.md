# Data Dictionary and Sources

## Sources

All my ELO scores were scraped using the api from [Club Elo](http://clubelo.com/).

The bookmakers odds were downloaded from [Football-Date](http://www.football-data.co.uk/).

The xG was downloaded from [Five38](https://github.com/fivethirtyeight/data/tree/master/soccer-spi).

## Data Dictionary

- date: The date the game was played
- team1: Home Team
- team2: Away Team
- score1: Home Team Score
- score2: Away Team Score
- xg1: Expected Goals from the match for the Home Team
- xg2: Expected Goals from the match for the Away Team
- FTR: Full Time Result (the y)
- season_period: When the game was played in the season (Season was split into Thirds)
- home_elo: ELO score of the Home Team
- away_elo: ELO score of the Away Team
- FTR_alpha: Non-numerical values of the Full Time Result for ease of reading
- xg1_5g_avg: Avergage XG for the home team over the passed home five games
- xg2_5g_avg: Average XG for an away team over the passed five games against the specific home team
- gd_5g_avg: Avergae Goal Difference for the home team for the past 5 home games
- game1: Result from the last home game
- game2: Result from the second last home game
- game3: Result from the third last home game
- game4: Result from the fourth last home game
- game5: Result from the fifth last home game
- elo_diff: The difference in ELO score between the home team and the away team
