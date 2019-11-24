# EECS 731 Project 4

This is Andre Kurait's third project for EECS 731, Data Science in Fall 2019.
For this project, I analyzed several clustering models to link similar movies.

## Project Requirements
### NFL, MLB, NBA and Soccer scores
1. Set up a data science project structure in a new git repository in your GitHub account
2. Pick one of the game data sets depending your sports preference
https://github.com/fivethirtyeight/nfl-elo-game 
https://github.com/fivethirtyeight/data/tree/master/mlb-elo 
https://github.com/fivethirtyeight/data/tree/master/nba-carmelo 
https://github.com/fivethirtyeight/data/tree/master/soccer-spi 
3. Load the data set into panda data frames
4. Formulate one or two ideas on how feature engineering would help the data set to establish additional value using exploratory data analysis
5. Build one or more regression models to determine the scores for each team using the other columns as features
6. Document your process and results
7. Commit your notebook, source code, visualizations and other supporting files to the git repository in GitHub

## Project structure
```bash
.
├── MovieLens.ipynb
├── README.md
└── data
    ├── README.txt
    ├── links.csv
    ├── movies.csv
    ├── ratings.csv
    └── tags.csv
```

## Data
I got the data from https://www.kaggle.com/kingburrito666/shakespeare-plays 

## Conclusion
Overall, I was able to achieve over 80% accuracy with a Random Forrest and almost 80% accuracy with a Decision Tree indicating that this is an easy classification problem.