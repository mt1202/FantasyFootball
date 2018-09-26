
# Created by Michael Talbert 
# FantasyFootball

Using historical information provided by the user, this monte carlo simulation predicts the expected winning 
percentage of fantasy football scores.

Our league has two games per week.  The first game is "Head-to-Head", where you play one other randomly selected
player each week and the high score wins.  The second game is "Rank", where you play the against the whole league.  
To win, your score must be in the top 5 (above the median).

Paste historic scores into alltime dictionary.  The more scores you paste, the more accurate your simulation will be.

1. Run.
2. Input the lower bound for an expected score.

   e.g. 100
3. Input the higher bound for an expected score.

   e.g. 175
4. Input how many simulations (weeks) you want to run.  The higher the number, the more accurate (and slower)
   the simulation will be.  
   
   e.g. 100,000
   
5. Output expected winning percentage for each score between lower bound and higher bound.

