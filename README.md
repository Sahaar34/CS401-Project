# FIFA 2026 World Cup Winner Predictor

## Overview
A project that predicts the 2026 FIFA World Cup winner by analyzing recent match data from (2022-2025).

## How It Works

1. Load recent World Cup matches (2022-2025)
2. Count total wins for each team
3. Calculate each team's win rate (wins / total matches)
4. Rank teams by win rate
5. Predict winner = team with highest win rate
6. Visualize top 10 teams with a bar chart


### Run the Analysis

1. Open `ML.ipynb` in VS Code
2. Click "Run All" or press Ctrl+Shift+D
3. Results save to `predictions_2026.csv`

## Files

- `ML.ipynb` - Main notebook
- `recent_wc_matches.csv` - Data: 930 matches from 2022-2025
- `worldcup_predictor_teams.csv` - List of 32 teams
- `predictions_2026.csv` - Ranked teams

## How to Run

- Open 'ML.ipynb' in VS Code or Jupyter Notebook
- Click Run All
- The notebook will generate:
  - predictions_2026.csv
  - predictions_2026_full.csv

## Output
- The notebook displays:
  - Each team’s matches, wins, and win rate
  - The ranked list of top teams
  - The final predicted 2026 World Cup winner

## Clone the Repository
git clone https://github.com/your-username/FIFA-2026-Predictor.git
cd FIFA-2026-Predictor