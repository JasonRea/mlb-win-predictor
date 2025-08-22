# MLB Team Wins Prediction

This repository contains a machine learning model to predict MLB team wins I built a random forest regression model to predict the number of wins for an MLB team in a season using full-season team batting, pitching, and fielding statistics.

## Dataset

- Source: [Lahman Baseball Database](https://sabr.org/lahman-database/)
- Format: CSV files containing seasonal team stats (e.g., `teams.csv`).
- Key features:
  - Offensive: `R`, `H`, `2B`, `3B`, `HR`, `BB`, `SB`, `SF`
  - Defensive: `RA`, `ER`, `HA`, `HRA`, `BBA`
  - Fielding: `E`, `FP`
  - Team-level: `W`, `L`

## Project Structure

- **csv**: raw csv files from lahman db
- **images**: evaluation reports and plots
- **src**:
  - `prediction.ipynb` - main workspace for this project
- **requirements.txt**: project dependencies
- **README.md**: this documentation file

## Accuracy Improvements

Currently measuring model accuracy within plus/minus 5 wins. Currently 3x better than pythagorean win percentage.

- (6/5/25) - 60%
- (7/5/25) - 74%