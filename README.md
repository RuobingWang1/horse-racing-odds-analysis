# Horse Racing Odds Analysis

## Overview

This project analyzes horse racing betting data to evaluate whether betting odds accurately reflect true winning probabilities.

Specifically, it investigates the presence of the favorite–longshot bias, a well-documented phenomenon in which favorites tend to yield higher returns than longshots, suggesting potential inefficiencies in betting markets.

## Author
### Ruobing Wang
	•	Organized project structure and workflow 
	•	Contributed to interpretation of results and final conclusions 
	•	Performed data analysis and visualization    
	•	Developed research hypothesis and analytical framework  
	•	Conducted ethical analysis of the study

* This project was completed as part of a team of five.

## Research Question

Do betting odds accurately reflect the true probability of winning in horse racing, or do systematic biases exist in the betting market?

## Methodology
	•	Exploratory data analysis (EDA)
	•	Correlation analysis (Pearson and Spearman)
	•	Data binning and aggregation
	•	Regression analysis
	•	Visualization (linear and logarithmic scales)

## Key Findings
	•	A strong negative relationship exists between betting odds and average returns
	•	Both Pearson and Spearman correlations confirm this relationship
	•	Evidence supports the presence of the favorite–longshot bias
	•	Betting markets may not be fully efficient

## Data

The dataset used in this project is too large to be hosted directly on GitHub.

You can download it here:
👉 https://docs.google.com/spreadsheets/d/1nGyuTvNUiw8fk0SEu64N7uJY1LiqELlp/edit?usp=sharing&ouid=116590361119788269185&rtpof=true&sd=true

After downloading, place the data in the data/ directory before running the analysis.

## How to Run
	1.	Download the dataset from the link above
	2.	Place it in the project folder (data/)
	3.	Open and run FinalProject.ipynb


## Project Structure
	•	FinalProject.ipynb
	•	data(external download required)

## Limitations
	•	The dataset is limited to Saga Racecourse, reducing generalizability
	•	The analysis is cross-sectional and does not capture temporal dynamics
	•	Some potentially relevant variables are not included

## Conclusion
This analysis demonstrates that betting odds are systematically related to returns, with higher odds associated with lower average returns.

The results consistently support the existence of the favorite–longshot bias, indicating that betting markets may exhibit structural inefficiencies.

## Future Work
	•	Extend analysis to multiple racecourses
	•	Incorporate additional variables (e.g., race conditions, horse attributes)
	•	Analyze how betting behavior evolves over time
