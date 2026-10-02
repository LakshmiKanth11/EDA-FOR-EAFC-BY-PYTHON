# EDA for EA FC by Python

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10%2B-3776AB?logo=python&logoColor=white" alt="Python 3.10+" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white" alt="Jupyter Notebook" />
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white" alt="Pandas" />
  <img src="https://img.shields.io/badge/Seaborn-Visualization-5C7CFA?logo=seaborn&logoColor=white" alt="Seaborn" />
  <img src="https://img.shields.io/badge/Scikit--Learn-ML-FF6F00?logo=scikitlearn&logoColor=white" alt="Scikit-learn" />
</p>

<p align="center">
  <a href="https://github.com/LakshmiKanth11/EDA-FOR-EAFC-BY-PYTHON/blob/main/ANALYSIS_OF_EA_FC.ipynb">
    <img src="https://img.shields.io/badge/Open%20Notebook-%20Google%20Colab-FF6F61?logo=googlecolab&logoColor=white" alt="Open in Colab" />
  </a>
</p>

A portfolio-style exploratory data analysis project focused on the EA Sports FC player dataset. This repository analyzes player attributes, team distribution, league representation, and rating patterns using Python, Pandas, Matplotlib, Seaborn, and Scikit-learn.

## Overview

This project was built to explore how player quality, skill attributes, age, club, and league interact across a large football dataset. The notebook applies a full EDA workflow and highlights key patterns that can guide further predictive modeling and deeper sports analytics.

## What this project covers

- Data upload and preprocessing
- Dataset overview and quality checks
- Distribution analysis by league, club, and nationality
- Attribute correlations with overall rating
- Position-wise performance comparisons
- Visual storytelling with charts and summaries
- Predictive modeling workflow using player features

## Dataset summary

The notebook explores a dataset with the following characteristics:

- 19,789 players
- 61 columns
- 702 clubs
- 63 leagues
- 164 nationalities
- Men and women’s football profiles included

## Notebook

The main analysis notebook is:

- `ANALYSIS_OF_EA_FC.ipynb`

This notebook contains the complete exploratory workflow, including:

1. Loading the EA FC dataset
2. Initial inspection and schema review
3. Age and profile calculations
4. Visual analysis of distributions and trends
5. Key findings from rating patterns
6. Feature-based predictive modeling steps

## Key insights captured

This analysis focuses on identifying patterns such as:

- Which clubs and leagues dominate top-performing players
- The strongest attributes correlated with high overall ratings
- Differences in player profiles by position and role
- Trends in national and international representation
- How physical, technical, and mental attributes influence performance

## Tech stack

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Repository structure

```text
EDA-FOR-EAFC-BY-PYTHON/
├── ANALYSIS_OF_EA_FC.ipynb
├── README.md
├── EA FC PLAYERS DATA.csv   # dataset used in the notebook
└── other generated outputs, if available
```

## Setup

Install the required dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

## Run the notebook

### Option 1: Local Jupyter environment

```bash
jupyter notebook
```

Then open `ANALYSIS_OF_EA_FC.ipynb` and run the cells sequentially.

### Option 2: Google Colab

Open the notebook directly in Colab using the badge above or upload the notebook into your Colab environment and run it.

## Example workflow

```python
import pandas as pd

# Load dataset
df = pd.read_csv('EA FC PLAYERS DATA.csv')
print(df.head())
```

## Portfolio-style highlights

This project demonstrates:

- exploratory data analysis fundamentals
- business/football analytics thinking
- data cleaning and preparation skills
- insight generation from structured datasets
- application of machine learning concepts in a real-world context

## Project status

Status: Complete exploratory analysis and modeling workflow implemented in the notebook.

## License

This project currently does not include a dedicated license file. If you plan to share or commercialize the project publicly, consider adding an open-source license.

## Author

Lakshmi Kanth

## Notes

This repository is designed as an educational and portfolio project to showcase analysis, visualization, and predictive modeling using a real-world football dataset.

## Preview section

If you want to add visual screenshots later, this is the ideal place to include them:

```md
## Analysis snapshots

![Top-rated players by league](path/to/league_chart.png)
![Attribute correlation heatmap](path/to/correlation_heatmap.png)
![Player rating distribution by position](path/to/position_distribution.png)
```

You can replace those with actual screenshots once the charts are exported from the notebook.
