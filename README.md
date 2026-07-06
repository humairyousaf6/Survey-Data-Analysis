# Survey Data Analysis

An exploratory data analysis project examining respondent demographics and preferences using a structured survey-style dataset (the Seaborn Titanic dataset used as example data).

## Dataset

Uses a CSV dataset containing respondent records with fields such as age, sex, class, and survival status (used here as a proxy for satisfaction). The data is loaded directly from a public URL.

## Steps Covered

- Loading the dataset and inspecting its structure
- Handling missing values using forward fill
- Converting the sex column to a categorical type
- Visualizing age distribution of respondents
- Visualizing gender distribution of respondents
- Visualizing class preference among respondents
- Visualizing satisfaction levels (using survival as a proxy)
- Creating an age group feature by binning ages into ranges
- Cross-tabulating age group against satisfaction
- Cross-tabulating gender against class preference
- Visualizing both cross-tabulations as stacked bar charts

## Result

The analysis highlights patterns in respondent demographics, including how age group and gender relate to class preference and satisfaction outcomes.

## Requirements

- Python 3
- pandas
- seaborn
- matplotlib

Install with:

```
pip install pandas seaborn matplotlib
```

## Usage

1. Open the notebook in Jupyter or Google Colab.
2. Run all cells in order. The dataset is loaded automatically from its source URL.

## Possible Improvements

- Replace the example dataset with an actual survey dataset relevant to the target use case
- Add statistical tests to confirm whether observed differences are significant
- Include additional demographic breakdowns, such as age and class combined
- Export summary tables and charts to a report format
