# march_madness

Done:
 - Stats for each team (i.e. offensive rebounding ability for year 2015)
 
 Potential to-dos:
  - Elo/Glicko/Massey/Colley ratings
  - Modeling (stack all below):
    - predict both score diff and win %
    - train on only regular season games, only tournament games, both
    - NN, XGB, RF, LR, NB
    - 5(?) Fold oof predictions for all tournament games
    - Should probably keep csv or google sheets of all methods used (data, model type, feature type) to coordinate
      - Save all oof predictions to repo, in msgpack
        - Do we need to standardize folds?
   - Data:
     - Preseason rankings
     - Location of tournament games/proximity to teams involved
