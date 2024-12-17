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
