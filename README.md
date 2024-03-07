# Mobile-Games-A-B-Testing-with-Cookie-Cats
Cookie Cats is a fun and addictive mobile puzzle game that has gained immense popularity. In this classic "connect three" style game, the player must connect tiles of the same color to clear the board and win the level. One of the unique features of the game is the presence of singing cats. 

As players progress through the levels of the game, they will occasionally encounter gates that force them to wait a non-trivial amount of time or make an in-app purchase to progress. In addition to driving in-app purchases, these gates serve the important purpose of giving players an enforced break from playing the game, hopefully resulting in that the player's enjoyment of the game being increased and prolonged.

# AB Test Analysis
But where should the gates be placed? Initially the first gate was placed at level 30, but in this notebook we're going to analyze an AB-test where we moved the first gate in Cookie Cats from level 30 to level 40. In particular, we will look at the impact on player retention , which is a critical metric for the success of any mobile game. But before we get to that, a key step before undertaking any analysis is understanding the data.

Our analysis is presented in the form of a Jupyter notebook, where we use Python and various data visualization libraries to explore and visualize the data. We also perform statistical analysis to determine the significance of the observed differences in player retention.

# Contents
The repository contains the following files:

README.md: This file provides an overview of the repository.

notebook.ipynb: This is the Jupyter notebook where we analyze the AB-test results.

datasets/cookie_cats.csv: This file contains the raw data used in the analysis.

# Conclusion
The analysis shows that there is strong evidence that 7-day retention is higher when the gate is at level 30 than when it is at level 40. 

The conclusion is: If we want to keep retention high — both 1-day and 7-day retention — we should not move the gate from level 30 to level 40. There are, of course, other metrics we could look at, like the number of game rounds played or how much in-game purchases are made by the two AB-groups. But retention is one of the most important metrics. If we don't retain our player base, it doesn't matter how much money they spend in-game.
