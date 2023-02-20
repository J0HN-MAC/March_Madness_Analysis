

dataset credit https://www.kaggle.com/datasets/nishaanamin/march-madness-data?select=Tournament+Team+Data.csv




## Does defense win championships?
- slide with hangover meme for transforming and cleaning data
- plot season defensive statistics vs round finished
- plot tournament defensive statistics vs round finished
- group by seed to see if defense is important compared to similar teams

## Cleaning Data
- tourney_game_df:
    - drop round of 68 teams?
    - change "TEAM" to include year (individual team), 
    - change "TEAM" to school?
    
    - change "ROUND" to wins in tourney. wins = 64=0, 32=1, 16=2, 8=3, 4=2, 2=5, 1=6
    - consider dropping stats 

- tourney_team_df:
    - drop ID
    - drop score

    - drop 2023 teams
    - drop round of 68 teams
    - change "TEAM" to include year
    




slides: 











suggestions for future: find distance from school to game location