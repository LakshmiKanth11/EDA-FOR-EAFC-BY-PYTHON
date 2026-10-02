# EDA for EA FC by Python

A Python-based exploratory data analysis (EDA) project for the EA Sports FC player dataset. This repository contains a Jupyter notebook that loads player data, cleans and explores it, visualizes key patterns, and demonstrates a predictive modeling workflow.

## Project Overview

This project analyzes a large FIFA/EA FC-style dataset containing player-level information such as:

- Player name and identity
- Club, league, and nationality
- Position and playing style
- Overall rating and attribute scores
- Age, gender, and other profile details

The notebook explores the dataset to answer questions like:

- Which clubs and leagues dominate the dataset?
- Which player attributes correlate most with overall rating?
- How do ratings differ by position, nationality, and gender?
- What patterns emerge from the player distribution across teams and leagues?

## Notebook

- `ANALYSIS_OF_EA_FC.ipynb`

This is the main analysis notebook. It includes:

- Data upload and loading
- Initial dataset inspection
- Feature engineering and derived metrics
- Exploratory visualizations
- Summary statistics and insights
- Predictive modeling steps

## Dataset

The notebook is designed to work with an EA FC player dataset, such as a CSV like:

- `EA FC PLAYERS DATA.csv`

The project currently uses a dataset with:

- 19,789 rows
- 61 columns
- 702 clubs
- 63 leagues
- 164 nationalities

## Tech Stack

- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Requirements

Install the dependencies with:

```bash
pip install pandas matplotlib seaborn scikit-learn jupyter
```

## How to Run

1. Open the notebook in Jupyter or Google Colab.
2. Upload the EA FC player CSV file when prompted.
3. Run the notebook cells sequentially.
4. Review the exploratory analysis and generated visualizations.

## Example Workflow

```python
import pandas as pd

# Load dataset
# df = pd.read_csv('EA FC PLAYERS DATA.csv')
# df.head()
```

## Key Findings

The notebook highlights a range of insights from the dataset, including:

- Strong concentration of top-rated players in major leagues
- Clear differences in ratings by position
- The effect of key attributes like shooting, pace, passing, and defending on overall performance
- Trends across clubs, nationalities, and player profiles

## Repository Structure

```text
EDA-FOR-EAFC-BY-PYTHON/
├── ANALYSIS_OF_EA_FC.ipynb
├── README.md
└── (uploaded dataset file, if present)
```

## License

This project does not currently include a license file. If you plan to share or reuse the notebook publicly, consider adding an open-source license.

## Author

Lakshmi Kanth

## Notes

This project is intended for educational and exploratory analysis purposes. The analysis can be extended with additional machine learning models, dashboards, or a cleaner reproducible pipeline.
