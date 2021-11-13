# SuperBowl_Squares

## Overview
Using historical super bowl data, create a 10x10 grid of super bowl squares that displays the expected payout for each
square using payouts of 25% per quarter.

Eventually:
1- add all playoff games instead of just super bowls.
2- allow for user input for the payouts

## Files
**squares_scraping**: creates the cleaned data (**data.csv**) for **squares_stats**


## Instructions
Click **squares_stats.ipynb** to see outputs of analysis on GitHub

Alternatively, download **squares_scraping.ipynb** and run to get **data.csv** (or just download **data.csv**)
Then run **squares_stats.ipynb**


**playoff_squares_stats.ipynb** is the same analysis but with all NFL playoff data. Instead of AFC vs NFC the data is Away vs Home. Note: Super Bowl host switches conferences every year

**vikings_playoffs_stats.ipynb** is similar analysis but with Minnesota Vikings on the x-axis, and Opponents on the y-axis

**playoff_stats_functions** (not ready yet and I didn't feel like creating a new branch)will be a notebook where the user can input their team and see the results from vikings_playoffs_stats but with their team.
