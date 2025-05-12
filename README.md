# final-project

This project is about using statistics from the actual NBA 2020 season and using those statistics to see if they have any correlation with the in game rating of the player.

### To do list

---

[x] find kaggle data set

[x] scrape basketball stats from basketball reference

[x] clean both data sets

[x] merge the data sets on the player name

[x] use the merged data to find answers to questions that we made in our proposal

# code

## notebooks

Python jupyter notebooks(.ipynb) files should be prefixed with the order they should run

- 00_nba2k20_scraping.ipynb
- 01_nba2k20_data.ipynb
- 02_wrangling_nba_project.ipynb

# Data folder

## Folders

source data:
https://www.basketball-reference.com/

https://www.kaggle.com/datasets/isaienkov/nba2k20-player-dataset

### raw

Original, unmodified data after downloading, scraping, etc

### final

Data after all cleaning, processing, and analyzing

# Data Dictionary

## Data Dictionary

This dataset contains information about basketball players, their statistics, and associated metrics. Below is the detailed description of each field in the dataset:

| **Field Name**        | **Data Type** | **Source** | **Description**                                   |
| --------------------- | ------------- | ---------- | ------------------------------------------------- |
| **Player_name**       | Text          | Both       | Full name of the player.                          |
| **Team_name**         | Text          | Both       | Basketball team name associated with the player.  |
| **Overall_rating**    | Numeric       | Kaggle     | Overall rating for the player.                    |
| **Height**            | Numeric       | Kaggle     | Height of the player (e.g., in inches or cm).     |
| **Weight**            | Numeric       | Kaggle     | Weight of the player (e.g., in pounds or kg).     |
| **Salary**            | Numeric       | Kaggle     | Salary of the player for the specified year.      |
| **PPG**               | Numeric       | BBRef      | Points per game during the 2019-2020 season.      |
| **Assist_per_game**   | Numeric       | BBRef      | Assists per game during the 2019-2020 season.     |
| **Rebounds_per_game** | Numeric       | BBRef      | Rebounds per game during the 2019-2020 season.    |
| **Minutes Played**    | Numeric       | BBRef      | Total minutes played during the 2019-2020 season. |
| **Position**          | Text          | Both       | Player's position on the basketball court.        |
