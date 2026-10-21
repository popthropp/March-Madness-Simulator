# March-Madness-Simulator

Predicting NCAA men’s basketball tournament outcomes using historical performance, engineered matchup features, and machine learning.

The project compares game-level predictions against a seed-based baseline and uses predicted winners to construct and score complete tournament brackets.

## Problem

**Can machine learning outperform a strategy that always selects the better-seeded team?**

March Madness prediction involves both estimating individual game outcomes and choosing winners across an entire bracket. These objectives differ because later-round selections earn more points and depend on earlier predictions.

This project explores both objectives, providing a framework for sports analytics and historical bracket comparisons.

Developed in BA576 (Business Focused Machine Learning)

## Data

Source: Kaggle’s 2026 March Madness competition dataset 

The saved notebook loads 122,775 regular-season games and 2,585 tournament games before filtering for individual experiments.

MRegularSeasonDetailedResults.csv

- Regular-season scores and box-score statistics

MNCAATourneyCompactResults.csv

- Historical tournament outcomes

MNCAATourneyDetailedResults.csv

- Detailed tournament results

MNCAATourneySeeds.csv

- Tournament seeds

MNCAATourneySlots.csv

- Bracket structure

MTeams.csv

- Team identifiers and names

## My Contribution

Feature Cleaninig/Engeneering as well as predictive model creation
