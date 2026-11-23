League of Legends: What Drives Winning?

Status: Work in Progress

Project Overview

This project explores which in-game factors are associated with winning professional League of Legends matches.
Using 2026 professional match data from Oracle's Elixir, I analyze how early gold advantages and dragon control relate to match outcomes.
The goal is to identify meaningful patterns through data analysis and visualization using Python.

Research Questions

How does gold advantage at 15 minutes relate to win rate?
Are larger gold leads associated with higher win rates?
How important is securing the first dragon?
Does first dragon control matter when a team is behind in gold?

Dataset

This project uses the 2026 professional League of Legends match dataset provided by Oracle's Elixir.
The dataset contains professional match statistics, including team performance, gold differences, objective control, and match outcomes.
For this analysis, I focused on team-level data to investigate how early-game advantages and dragon control relate to winning.
The original dataset is not included in this repository and can be downloaded from Oracle's Elixir.

Tools and Technologies

Python — Data cleaning, manipulation, and analysis
Pandas — Filtering, grouping, and aggregating match statistics
Matplotlib — Visualizing win rates and gameplay trends
Jupyter Notebook — Organizing code, visualizations, and findings
GitHub — Version control and project documentation

Key Findings

The analysis revealed several patterns in professional League of Legends matches:
Early Gold Advantage: Teams ahead by 3,000 or more gold at 15 minutes won approximately 92.4% of their matches.
First Dragon: Teams that secured the first dragon had a 61.7% win rate.
Elder Dragon: Teams that secured Elder Dragon won approximately 83.7% of their matches.
Comeback Difficulty: Teams trailing by 3,000 or more gold at 15 minutes won only 7.6% of their matches.
Gold Advantage and Dragon Control: Teams ahead in gold at 15 minutes that also secured the first dragon had an 80.1% win rate, compared with 66.1% for teams ahead without the first dragon.
Overall, early gold advantages showed a strong relationship with winning. Dragon control was also associated with higher win rates, although these relationships do not necessarily imply causation.

Limitations

Correlation vs. Causation: The relationships identified in this analysis do not establish that gold advantages or dragon control directly cause teams to win.
Dragon Soul Data: The dataset does not explicitly identify which Dragon Soul each team secured, limiting the ability to compare win rates across different soul types.
Elder Dragon Timing: Elder Dragon is a late-game objective, so its association with winning should not be interpreted as an early-game prediction.
Dataset Scope: The analysis focuses on professional League of Legends matches from 2026, so findings may not generalize to other seasons or levels of play.

How to View the Analysis

The complete analysis is available in the LeagueAnalysis.ipynb Jupyter Notebook.
The notebook includes data cleaning, exploratory analysis, visualizations, and explanations of the findings.
To explore the project, open the notebook directly on GitHub or download it and run it locally using Jupyter Notebook. The original dataset is available from Oracle's Elixir.
