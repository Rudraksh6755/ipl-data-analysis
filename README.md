# 🏏 IPL Data Analysis (2008–2023)

A data-driven exploratory analysis of **15+ seasons of Indian Premier League (IPL) cricket** using Python, Pandas, Matplotlib, and Seaborn.

This project analyzes **239,000+ ball-by-ball delivery records** to uncover insights into player performance, team strategies, venue characteristics, scoring patterns, and winning trends.

---

## 📌 Project Overview

The objective of this project is to transform raw IPL ball-by-ball cricket data into meaningful statistical insights using:

* Data Cleaning
* Data Indexing and Selection
* Feature Engineering
* Exploratory Data Analysis (EDA)
* Statistical Analysis
* Data Visualization

The analysis covers batting, bowling, team scores, winning trends, IPL records, and venue-level insights.

### 🔍 Key Questions

This project explores questions such as:

* Who are the most consistent run-scorers in IPL history?
* Who are the most impactful wicket-takers?
* How significant is winning the toss on match outcomes?
* Which teams perform better while chasing or defending?
* Which venues show a strong chasing or defending bias?
* How do scoring rates and first-innings totals vary across matches?
* What patterns can be observed in IPL team and player performances?

---

## 📊 Key Highlights & Analytical Findings

### 🏏 Top Run Scorers

* **Virat Kohli** leads with **7,122+ runs**
* **Shikhar Dhawan** follows with **6,573+ runs**
* **David Warner** follows with **6,310+ runs**

### 🎯 Top Wicket-Takers

* **Dwayne Bravo** and **Yuzvendra Chahal** share the top position with **183 wickets each**
* **Piyush Chawla** follows with **177 wickets**

### 🏆 Most Successful Franchises

* **Mumbai Indians** – **138 wins**
* **Chennai Super Kings** – **131 wins**

These teams demonstrate strong long-term performance across the analyzed IPL seasons.

### 🏟️ Venue Insights

The analysis examines venue-level scoring patterns, chasing tendencies, and match outcomes to understand how different grounds can influence match strategies and results.

### 📈 Scoring Trends

The project also investigates first-innings scores, scoring rates, team totals, and match situations to identify patterns associated with successful outcomes.

---

## 📊 Dashboard Insights

| ⚡ Fastest Fifty                                 | 🟠 Orange Cap Winners                                     |
| ----------------------------------------------- | --------------------------------------------------------- |
| ![Fastest Fifty](screenshots/fastest-fifty.png) | ![Orange Cap Winners](screenshots/orange-cap-winners.png) |

| 🟣 Purple Cap Winners                                     | 🏆 IPL Titles Won by Each Team                   |
| --------------------------------------------------------- | ------------------------------------------------ |
| ![Purple Cap Winners](screenshots/purple-cap-winners.png) | ![IPL Titles](screenshots/ipl-title-winners.png) |

| 🏟️ Venue Insights                                | 📈 Winning Trends                                 |
| ------------------------------------------------- | ------------------------------------------------- |
| ![Venue Insights](screenshots/venue-insights.png) | ![Winning Trends](screenshots/winning-trends.png) |

| 💥 Batsmen with Highest Sixes                   |   |
| ----------------------------------------------- | - |
| ![Highest Sixes](screenshots/highest-sixes.png) |   |



## 📁 Repository Structure

```text
ipl-data-analysis/
│
├── README.md
│
├── Data_Cleaning.ipynb
│   └── Data cleaning, standardization, missing values, and data preparation
│
├── Indexing_and_Selection.ipynb
│   └── Pandas indexing, filtering, selection, and slicing techniques
│
├── Feature_Engineering.ipynb
│   └── Creation and transformation of analytical features
│
├── Batting_Analysis.ipynb
│   └── Batting performance, run-scoring, boundaries, and strike rates
│
├── Bowling_Analysis.ipynb
│   └── Bowling performance, economy rates, dot balls, and wickets
│
├── Team_Score_Analysis.ipynb
│   └── Team totals, innings scores, and scoring-rate analysis
│
├── Winning_Trends.ipynb
│   └── Toss impact, toss decisions, match outcomes, and victory margins
│
├── IPL_Records.ipynb
│   └── Major IPL player and team records
│
├── Venue_Insights.ipynb
│   └── Venue statistics, scoring patterns, and match outcomes
│
└── ball_by_ball_ipl.zip
    └── Compressed ball-by-ball IPL dataset
```

> **Note:** Notebook filenames can be adjusted to match the exact filenames uploaded to the repository.

---

## 🛠️ Tech Stack

| Category                | Technologies                  |
| ----------------------- | ----------------------------- |
| Programming Language    | Python 3.8+                   |
| Data Analysis           | Pandas, NumPy                 |
| Data Visualization      | Matplotlib, Seaborn           |
| Development Environment | Jupyter Notebook / JupyterLab |
| Dataset                 | IPL Ball-by-Ball Cricket Data |

---

## 🧹 Data Cleaning

The data preparation process includes operations such as:

* Handling missing values
* Identifying and removing duplicate records
* Standardizing categorical values
* Cleaning team, player, and venue names
* Converting columns to appropriate data types
* Preparing the dataset for further analysis

The dataset contains detailed delivery-level information including match, date, venue, teams, innings, batter, non-striker, bowler, runs, extras, wickets, winner, and other derived fields.

---

## 🔢 Pandas Indexing & Selection

The project also demonstrates practical Pandas techniques for working with structured cricket data, including:

* Column selection
* Row selection
* Conditional filtering
* Boolean indexing
* `.loc[]`
* `.iloc[]`
* Data slicing
* Selecting specific subsets of data

These operations form the foundation for the subsequent IPL analysis.

---

## ⚙️ Feature Engineering

Feature engineering is used to create and transform variables required for deeper analysis.

Examples include:

* Batting performance metrics
* Bowling performance metrics
* Runs and scoring rates
* Wicket-related metrics
* Ball and over-based calculations
* Match-level indicators
* Chase-related metrics

---

## 🏏 Batting Analysis

The batting analysis investigates player-level performance using the available ball-by-ball data.

Areas explored include:

* Total runs
* Top run scorers
* Balls faced
* Strike rates
* Boundary contribution
* Player performance trends

---

## 🎯 Bowling Analysis

The bowling analysis focuses on evaluating bowling performances across IPL matches.

Areas explored include:

* Wickets
* Runs conceded
* Economy rates
* Dot balls
* Bowling performance
* Top wicket-takers

---

## 🏆 Team Score Analysis

Team-level scoring patterns are analyzed to understand how teams perform across innings and match situations.

The analysis includes:

* Team totals
* First-innings scores
* Scoring rates
* Innings-level trends
* Team performance patterns

---

## 📈 Winning Trends

The project examines different factors associated with winning IPL matches.

Analysis includes:

* Toss results
* Toss decision vs. match outcome
* Batting first vs. chasing
* Successful chases
* Victory margins
* Team winning patterns

---

## 🏅 IPL Records

The IPL records analysis explores notable player and team achievements from the analyzed dataset.

This section includes statistical comparisons of:

* Batting records
* Bowling records
* Team wins
* Match performances
* Other IPL-related records

---

## 🏟️ Venue Insights

Venue-level analysis is used to understand how different grounds influence match characteristics.

The analysis explores:

* Matches played at different venues
* Team performance by venue
* First-innings scoring
* Chasing trends
* Venue-based winning patterns
* Scoring behavior across grounds

---

## 📊 Analysis Workflow

```text
Raw IPL Data
     │
     ▼
Data Cleaning
     │
     ▼
Data Validation & Preparation
     │
     ▼
Pandas Indexing & Selection
     │
     ▼
Feature Engineering
     │
     ▼
Exploratory Data Analysis
     │
     ├── Batting Analysis
     │
     ├── Bowling Analysis
     │
     ├── Team Score Analysis
     │
     ├── Winning Trends
     │
     ├── IPL Records
     │
     └── Venue Insights
     │
     ▼
Statistical Insights & Visualizations
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Rudraksh6755/ipl-data-analysis.git
cd ipl-data-analysis
```

### 2. Extract the Dataset

The ball-by-ball dataset is provided as a compressed ZIP archive.

Extract:

```text
ball_by_ball_ipl.zip
```

#### Windows

Right-click the ZIP file and select:

**Extract All...**

#### Linux / macOS

```bash
unzip ball_by_ball_ipl.zip
```

After extraction, place the CSV dataset in the project directory or in the location expected by the notebooks.

---

### 3. Install Dependencies

Make sure Python 3.8 or later is installed.

Install the required Python packages:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

Alternatively:

```bash
pip install -r requirements.txt
```

if a `requirements.txt` file is included in the repository.

---

### 4. Launch Jupyter Notebook

Run:

```bash
jupyter notebook
```

or:

```bash
jupyter lab
```

Open the required `.ipynb` notebook and run the cells sequentially.

---

## 📦 Required Python Libraries

```text
pandas
numpy
matplotlib
seaborn
jupyter
```

---

## 📂 Dataset

The project uses **ball-by-ball IPL cricket data covering the analyzed period from 2008 to 2023**.

The dataset contains fields related to:

* Match information
* Date
* Venue
* Batting teams
* Innings
* Overs and balls
* Batter
* Non-striker
* Bowler
* Batter runs
* Extra runs
* Total runs
* Wickets
* Dismissal information
* Match winner
* Chase information
* Balls remaining
* Other derived performance metrics

---

## 💡 What This Project Demonstrates

This project demonstrates practical skills in:

* Python for data analysis
* Pandas data manipulation
* NumPy
* Data cleaning
* Missing-value handling
* Data filtering and selection
* Feature engineering
* Exploratory Data Analysis
* Statistical analysis
* Data visualization
* Cricket data analysis
* Extracting business-style insights from raw data

---

## 📌 Future Improvements

Possible extensions to this project include:

* Building an interactive **Power BI dashboard**
* Adding advanced player performance metrics
* Creating predictive models for match outcomes
* Developing team win-probability models
* Adding season-wise interactive visualizations
* Creating an automated data-analysis pipeline
* Deploying the analysis as a web application

---

## 👨‍💻 Author

**Rudraksh Kawale**

Computer Engineering Graduate | Data Analytics & Full Stack Development

### 🔗 Connect With Me

* GitHub: [Rudraksh6755](https://github.com/Rudraksh6755)
* LinkedIn: [Rudraksh Kawale](https://www.linkedin.com/in/rudraksh-kawale/)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).



---

⭐ **If you find this project useful, consider giving the repository a star!**
