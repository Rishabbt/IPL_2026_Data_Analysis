
# IPL_2026_Data_Analysis

IPL 2026 Data Analysis

About the Project

This project is a simple data analysis of the IPL 2026 season using Python.

The main goal was to take the match data and explore it from a few different angles, such as team wins, toss decisions, player performances, bowling figures, and venues. I used Pandas for working with the data and Seaborn/Matplotlib to create visualizations.

This is mainly a practice project for understanding how real-world sports data can be cleaned, grouped, compared, and visualized with Python.

Dataset

The dataset contains 74 IPL 2026 matches and includes 20 columns covering match details, team results, player performances, and bowling information.

Some of the main columns are:

date – Match date

venue – Stadium where the match was played

team1, team2 – Teams playing the match

stage – Stage of the tournament

toss_winner – Team that won the toss

toss_decision – Decision made after winning the toss

first_ings_score – Score in the first innings

second_ings_score – Score in the second innings

match_winner – Winning team

won_by – Whether the match was won by runs or wickets

margin – Winning margin

player_of_the_match – Player receiving the award

top_scorer – Highest run scorer in the match

highscore – Highest individual score

best_bowling – Best-performing bowler

best_bowling_figure – Bowling figure

Tools and Libraries

The analysis was done in Python using:

Python — the language everything runs in
Jupyter Notebook — the environment (cells, markdown + code mixed)
pandas — data loading, cleaning, and analysis (read_csv, groupby, value_counts, sort_values, etc.)
NumPy — imported for numerical operations
Plotly — new visualization layer, specifically:
  plotly.express (px) — the one actually used for every chart (bar charts of wins, toss trends, top scorers, venues, etc.)
  plotly.graph_objects (go) — imported but unused right now; available if you want more custom/manual chart control later

Analysis Covered

Team Performance

The notebook looks at:

Which team won the most matches

How often matches were won by runs or wickets

The relationship between toss winners and match winners

Toss Analysis

I also looked at the distribution of toss decisions to see whether teams preferred to bat or field after winning the toss.

Player Performance

The player analysis includes:

Most Player of the Match awards

Top run scorers

Highest individual scores

Best bowling figures

Venue Analysis

The project also checks which venues hosted the most matches during the season.

Key Questions Explored

Some of the questions answered in the notebook are:

Which team won the most matches?

What was the most common toss decision?

How often did the toss winner also win the match?

Were matches more often won by runs or wickets?

Which players received the most Player of the Match awards?

Who were the top run scorers?

Which bowlers had the strongest bowling figures?

Which venue hosted the most matches?

What was the largest winning margin by runs?

Who had the highest individual score?

Who recorded the best bowling figure?

Project Structure

IPL-2026-Data-Analysis/
│
├── IPL.ipynb
├── IPL_2026.csv
└── README.md

How to Run the Project

1. Clone or download the project

Open the project folder in VS Code.

2. Install the required libraries

Open the VS Code terminal and run:

pip install numpy pandas seaborn matplotlib

3. Open the notebook

Open:

IPL.ipynb

in VS Code and select your Python/Jupyter kernel.

4. Run the cells

Run the notebook cells from top to bottom to reproduce the analysis and visualizations.

What I Learned

Through this project, I practiced using Pandas for:

Loading CSV data

Checking dataframe information

Counting values with value_counts()

Filtering rows

Grouping data with groupby()

Sorting results

Creating new columns

Extracting values from text

Finding maximum values

I also got hands-on practice creating charts with Seaborn and Matplotlib.

Note About the Dataset

This project is intended for learning and data-analysis practice. The dataset should not be treated as an official statistical source for IPL records. Some fields were populated for analysis practice where detailed verification was not available.

Conclusion

This project gave me a practical way to work with a sports dataset instead of only practicing Pandas and visualization functions with small examples.

By analyzing the IPL data, I was able to combine data cleaning, aggregation, basic statistics, and visualization into one project. It also helped me understand how to turn questions about a dataset into actual Python analysis.
