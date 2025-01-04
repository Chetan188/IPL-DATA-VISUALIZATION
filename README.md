# IPL Match Data Analysis

This repository contains a Python script for exploratory data analysis (EDA) of an IPL (Indian Premier League) match dataset. The script uses Pandas and Matplotlib to clean the data and generate various visualizations.

## Data

The analysis uses a CSV file named `data.csv`.  This file should be placed in the root directory of the repository.  The expected data includes information about IPL matches, such as dates, teams, venues, winning teams, and other relevant statistics.

## Analysis and Visualizations

The script performs the following operations:

1. **Data Cleaning:**
    - Handles missing values.
    - Converts data types where necessary (e.g., date columns to datetime objects).
    - Drops irrelevant or mostly empty columns.

2. **Exploratory Data Analysis (EDA):**
    - Generates various visualizations using Matplotlib, providing insights into different aspects of the dataset:
        - Matches per season
        - Most successful teams (total wins)
        - Cities hosting the most matches
        - Toss decision trends
        - Distribution of wins (by runs and wickets)
        - Matches played and won by each team
        - Matches with the D/L method applied
        - Player of the match awards
        - Venues hosting the most matches
        - Season winners
        - Toss winner vs match winner
        - Winning margin analysis (runs vs wickets)
        - Umpire analysis (if umpire data is available)
        - Team Losses


## Usage

1.  **Prerequisites:**
    - Python 3.x
    - pandas
    - matplotlib
    - numpy

    You can install these using pip:
    ```bash
    pip install pandas matplotlib numpy
    ```

2.  **Running the Script:**
    ```bash
    python your_script_name.py
    ```
    Replace `your_script_name.py` with the actual name of your Python file.

## Output

The script generates a series of visualizations as PNG images, providing insights into different aspects of the dataset.
