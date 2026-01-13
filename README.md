AI ML Project on IPL Data Analysis

## Project Overview
This project performs an exploratory data analysis (EDA) on Indian Premier League (IPL) match data to identify winning trends, player performance patterns, winning margins, and home vs away advantages across multiple seasons.

The analysis demonstrates practical data handling, feature engineering, visualization, and insight generation using Python.


## Dataset Description
The dataset contains season-wise IPL match information including:
- Season
- Team 1 and Team 2
- Match City
- Player of the Match
- Runs Scored

Additional features such as match outcome, winning margin, and home/away indicators were derived during analysis.


## Tools & Technologies Used
- Python
- Pandas (Data manipulation)
- Matplotlib (Data visualization)
- Seaborn (Advanced visualizations)


## Key Analysis Performed

### 1. Match Outcome Analysis
- Identified the number of matches won by Team 1 vs Team 2.
- Visualized match outcomes using bar charts.

**Insight:**  
Team 2 won slightly more matches compared to Team 1 across the observed seasons.


### 2. Winning Margin Distribution
- Calculated winning margins based on run differences.
- Analyzed statistical distribution (mean, median, max, min).
- Visualized using histograms.

**Insight:**  
The average winning margin is approximately 23 runs, indicating moderately competitive matches with occasional large victories.


### 3. Player of the Match Performance
- Grouped player awards across seasons.
- Created a season-wise performance matrix.
- Visualized using a heatmap.

**Insight:**  
Key players such as Rohit Sharma, MS Dhoni, and Andre Russell consistently appeared as match winners across different seasons.


### 4. Home vs Away Performance
- Analyzed match outcomes based on home and away conditions.
- Compared win distributions.

**Insight:**  
Away wins slightly outweigh home wins in the dataset, suggesting home advantage is not always decisive.


## Feature Engineering
The following derived columns were created:
- `match_outcome` – Identifies the winning team
- `winning_margin` – Run difference between competing teams
- `home_away` – Indicates home or away status (example-based logic)


## Visualizations Included
- Bar chart for match outcomes
- Histogram for winning margin distribution
- Heatmap for player performance across seasons


## Conclusion
This project showcases the ability to:
- Perform exploratory data analysis
- Engineer new features from raw data
- Create meaningful visualizations
- Extract actionable insights from sports data

The analysis approach can be extended to larger, real-world IPL datasets for deeper insights.


## Future Improvements
- Use official IPL datasets with full match-level statistics
- Implement team-based home/away logic
- Add predictive modeling for match outcomes
- Deploy insights using interactive dashboards
