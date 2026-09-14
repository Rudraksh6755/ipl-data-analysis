🏏 IPL Data Analysis (2008 – 2023)

A data-driven exploratory study analyzing over 15 seasons of Indian Premier League (IPL) cricket matches. This project leverages Python, Pandas, Matplotlib, and Seaborn to process over 239,000+ ball-by-ball delivery records, extracting statistical insights across player performances, team strategies, venue biases, and winning trends.

📌 Project Overview

The goal of this project is to convert raw ball-by-ball cricket data into actionable insights through data cleaning, feature engineering, and exploratory data analysis (EDA).

Key questions addressed:

Who are the most consistent run-scorers and impactful wicket-takers in IPL history?

How significant is the impact of winning the toss on overall match outcomes?

Which teams perform best when defending totals vs. chasing targets?

How do different venues and pitch conditions affect match scores and scoring rates?

📊 Key Highlights & Analytical Findings

Top Run Scorers: Virat Kohli leads with 7,122+ runs, followed by Shikhar Dhawan (6,573+ runs) and David Warner (6,310+ runs).

Top Wicket-Takers: Dwayne Bravo and Yuzvendra Chahal share the top spot with 183 wickets each, closely followed by Piyush Chawla (177 wickets).

Most Successful Franchises: Mumbai Indians (138 wins) and Chennai Super Kings (131 wins) remain the most dominant franchises in the league.

Match Venue Insights: Specific grounds demonstrate strong chasing biases, whereas standard first-innings totals near 170+ significantly increase winning probabilities.

📁 Repository Structure

├── README.md                                          # Project documentation
├── Data_Cleaning.ipynb                                # Data standardization & null value handling
├── Feature_Engineering.ipynb                          # Custom metrics creation (wickets, overs, rates)
├── Batting_Analysis.ipynb                             # Top batters, boundary percentages, & strike rates
├── Bowling_Analysis.ipynb                             # Economy rates, dot balls, & top wicket-takers
├── Team_Score_Analysis.ipynb                          # Team totals, innings trends, & scoring rates
├── Winning_Trends.ipynb                               # Toss impact, toss decision vs outcome, victory margins
├── IPL_Records_&_Venue_Insights.ipynb                 # Stadium stats, pitch behavior, & venue records
├── Exploratory Data Analysis (EDA) of IPL Matches...  # Comprehensive overall EDA summary
├── indexing_and_selection.ipynb                       # Code reference for data selection & slicing
└── ball_by_ball_ipl.zip                               # Compressed ball-by-ball IPL dataset


📓 Notebook Descriptions

Data_Cleaning.ipynb

Standardizes venue names (e.g., merging Feroz Shah Kotla into Arun Jaitley Stadium), handles missing values (Method, Player Out), cleans string formatting for players, and unifies updated franchise names (e.g., Delhi Daredevils to Delhi Capitals).

Feature_Engineering.ipynb

Extracts date/year components, computes cumulative runs, calculates overs bowled, isolates bowler-credited wickets, and derives run-rate indicators for both chasing and defending phases.

Batting_Analysis.ipynb

Focuses on individual batting contributions: top run scorers, strike rates across powerplay and death overs, boundary hitters, and consistency metrics.

Bowling_Analysis.ipynb

Evaluates bowling performance: economy rates, top wicket-takers, dot-ball counts, and performance in different phases of an innings.

Team_Score_Analysis.ipynb

Examines team-level metrics: highest and lowest team totals, average first-innings vs second-innings scores, and score distributions.

Winning_Trends.ipynb

Analyzes match outcomes: win percentages, toss decisions (batting vs. fielding first), win margins (by runs vs. by wickets), and head-to-head records.

IPL_Records_&_Venue_Insights.ipynb

Investigates ground dynamics: high-scoring grounds, pitch behaviors, victory rates by stadium, and host city advantages.

Exploratory Data Analysis (EDA) of IPL Matches (2008-2023).ipynb

A consolidated notebook combining high-level summary charts, distributions, and core statistical takeaways.

🛠️ Tech Stack & Dependencies

Language: Python 3.8+

Data Manipulation: pandas, numpy

Data Visualization: matplotlib, seaborn

Environment: Jupyter Notebook / JupyterLab

🚀 How to Run Locally

1. Clone the Repository

git clone https://github.com/YOUR-USERNAME/ipl-data-analysis.git
cd ipl-data-analysis


2. Extract the Dataset

Since the dataset exceeds 25 MB, it is stored as a .zip archive in the repository. Extract ball_by_ball_ipl.zip into your working directory:

Linux/Mac: unzip ball_by_ball_ipl.zip

Windows: Right-click ball_by_ball_ipl.zip and select Extract All...

3. Install Dependencies

Make sure you have Python installed, then install the required libraries:

pip install pandas numpy matplotlib seaborn jupyter


4. Launch Jupyter Notebook

jupyter notebook


Open any of the .ipynb files in your browser to run the cells and explore the analysis.

🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page if you'd like to suggest improvements or additional analyses.

📜 License

This project is open-source and available under the MIT License.
