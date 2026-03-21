# DataScienceProject-P2
DS 4002: Data Science Project

## Section 1: Software and platform section
The software used for this project was Visual Studio Code (VS Code) and GitHub. The language used was Python (3.12.4). Additionally, the platform that was used was Windows, and the following packages were installed for this project:
* numpy
* pandas
* matplotlib
* seaborn
* statsmodels.api 

## Section 2: Map of the documentation

**README.md**  
- Overview of the project, software and platform used, documentation map, and instructions for reproducing results

**LICENSE.md**  
- Terms for citing and reproducing the repository

**REFERENCES.md**  
- References to the nflfastR site where the data was obtained from

**SCRIPTS/**  
- nfl_weekly_analysis_notebook.ipynb contains EDA and OLS scripts

**DATA/**  
- nfl_weekly_dataset.csv: final dataset which contains computed variables (pass rate and plays per game) used to perform EDA and and OLS
- pbp_clean.csv: cleaned version of data that was used to create the finalized dataset: nfl_weekly_datasdet.csv

**OUTPUT/**  
- `correlation_matrix.png` – Correlation matrix results
- `ols_results.png` – Results after performing OLS (R-squared, F-statistic, etc)
- `weekly_average_points_per_game.png` – Line graph of time vs. average points
- `weekly_pass_rate.png` – Line graph of time vs. pass rate
- `weekly_plays_per_game.png` – Line graph of time vs. average plays 

## Section 3: Instructions for reproducing the results
1. Download the pbp_clean.csv file
2. Compute the variables pass rate and plays per game by following the script in the nfl_weekly_analysis_notebook.ipynb. Note: the new csv file should match the nfl_weekly_datset.csv.
3. Perform the EDA and OLS by running the coded in the nfl_weekly_analysis_notebook.ipynb.
4. Analyze results
