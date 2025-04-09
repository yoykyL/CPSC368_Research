# Research Topic

California's healthcare quality change between different presidencies in 2016 vs 2020

## Research Questions

- How does the change in voting patterns (2016 vs. 2020) across California counties correlate with changes in hospital readmission rates, and does this suggest the impact of federal healthcare policies under different presidencies?
- Are there significant differences in readmission rates between counties that consistently voted for one party in both 2016 and 2020, compared to counties that switched parties, and what factors might explain these differences?
- How do readmission rates differ between Republican-leaning ("red") and Democrat-leaning ("blue") counties in California in 2016 vs. 2020? (Using ‘mean()’ as the aggregator to represent the average level of readmission rates)


## Getting Started

### Dependencies

Required Packages and Libraries:
* `os`
* `pandas`
* `altair`
* `pipe`
* `sqlite3`

### Files

* `Codes1.ipynb` : Contains the data cleaning of original datasets, EDA, and the codes that dynamically generate the SQL "INSERT" statements.
* `SQL.ipynb` : The code used to pull data from the database, contaning SQL queries.
* `Results.ipynb` : The code used for the subsequent handling of that to tabulate your results and create the figures used in the final research paper.
* `rq1_voting_readmit_change.csv`: the data table used to solve question 1
* `rq2_avg_change_bar_chart.html`: the chart to answer question 2
* `rq2_consistency_vs_rate_change.csv`: the data table to solve question 2
* `rq3_avg_readmit_by_party_chart.html`: the chart to answer question 3
* `rq3_avg_readmit_by_party_year.csv`: the data table to answer question 3
* `allcauseunplanned30-dayhospitalreadmissionratecalifornia2011_2023.csv`: original dataset 1
* `presidential.csv`: the dataset with cleaned data from the original xlsl file of dataset 2
* `primary.csv`: cleaned dataset 1
* `presidentialResult.csv`: cleaned dataset 2

### Executing Queries

`SQL.ipynb`
* cell[11]: the queries to pull data for question 1
* cell[12]: the queries to pull data for question 2
* cell[13]: the queries to pull data for question 3

`Result.ipynb`
* cell[13]: the codes to plot the visualizations for question 1
* cell[14]: the codes to get the statistics for question 2
* cell[15]: the codes to plot the visualizations for question 3

## Notice

Any advise for common problems or issues.
```
command to run if program contains helper info
```

## Authors

**CPSC 368 - Group AAA**

* Kunyue Liu
* Aryan Jain
* Chrysta Luo


## Acknowledgments

The GitHub repository that stores all the required files and tracks the project process. 
[Group Repository](https://github.com/yoykyL/CPSC368_Research#)

