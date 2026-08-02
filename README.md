# afl-disposal-modelling
Sports analytics project predicting AFL player disposals using historical performance data — exploring feature engineering and regression/ML models from a baseline up.

## Live Demo
[AFL Disposal Edge Matrix](https://raymonxian-collab.github.io/afl-disposal-model/afl_edge_matrix_standalone%20(45).html)

## Dashboard guide

- Select two teams and a venue from the top dropdowns to load a position-by-position edge matrix showing how each position performs against that opponent at that venue, adjusted for game pace
- Click any position row to expand it and see individual players — season average, recent form, predicted disposals, and recent game history
- Click "+ Add to slip" under a player's probability chart to add them to a same-game slip (only players from the two selected teams can be added)
- Click the green tab, top right, to view your slip
- Click "Run Monte Carlo" to simulate thousands of outcomes and get the realistic combined probability of every player in the slip hitting their target together, accounting for correlation between players in the same game
