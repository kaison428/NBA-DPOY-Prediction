# 🏀NBA Defensive Player of the Year (DPOY) Prediction Model
Training and validating regression models based on historical data on NBA players to predict future DPOY award winners

## Data

The data used in this model includes:

1. DPOY candidates' statistics
2. Individual player statistics
3. Team statistics

## Feature Selection

The features selected for the model were chosen based on domain knowledge, mutual information scores, and iterative model performance checks. The selected features include:

- 'G' (Games Played)
- 'MP' (Minutes Played)
- 'STL' (Steals)
- 'BLK' (Blocks)
- 'WS/48' (Win/Share per 48 Minutes)
- 'DRB' (Defensive Rebounds)
- 'PF' (Personal Fouls)
- 'VORP' (Value Over Replacement Player)
- 'DWS' (Defensive Win Share)
- 'DBPM' (Defensive Box Plus Minus)
- 'Team_W/L' (Team Win Percentage)
- 'Team_PL' (Team Points Lost)
- 'Team_DRtg' (Team Defensive Rating)

## Modeling

Three different tree-based regression models were tested:

- Random Forest Regressor
- XGBoost (XGB) Regressor
- LightGBM (LGBM) Regressor

The model performance was evaluated using cross-validation with 5 K-folds and three different metrics: Root-Mean Squared Error (RMSE), Mean Absolute Error (MAE), and Coefficient of Determination (R2).

## Results

The models predicted Rudy Gobert to have the highest share in 2022, followed by Giannis. The models seemed to favor forwards and centers to win the DPOY, which aligns with the historical trend of the award winners.

## Medium Article

We have published a [Medium Article](https://medium.com/@sammy.restrepo/predicting-the-nbas-defensive-player-of-the-year-dpoy-through-machine-learning-1b44c0eab1b/) about this project. Feel free to check it out!

## Contribution

- [Samuel Restrepo](https://www.linkedin.com/in/samuel-restrepo-6a5132180/)
- [Kaison Cheung](https://github.com/kaison428)
- [Bryan Nguyen](linkedin.com/in/bryan-nguyen-b4329917b)
- [Muhammad Abdullah](https://www.linkedin.com/in/abdullahim/)

