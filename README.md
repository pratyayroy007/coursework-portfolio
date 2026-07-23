# Pandas / NumPy / Seaborn Practice

Short, runnable exercise notebooks covering core data-handling operations in
pandas and NumPy, categorical encoding with scikit-learn, and Seaborn
visualization basics.

| Notebook | Topic |
|---|---|
| `numpy-basics.ipynb` | Array creation, boolean masking, and array manipulation with NumPy |
| `pandas-series-basics.ipynb` | Creating/indexing `pandas.Series`, plus set operations (intersect, union, symmetric difference) |
| `pandas-assignment.ipynb` | Building and indexing DataFrames from dicts, nested dicts, and NumPy arrays |
| `census-data-analysis.ipynb` | Exploring a real census dataset and a GDP/life-expectancy dataset (`groupby`, filtering, charts) |
| `categorical-encoding.ipynb` | Label, ordinal, and one-hot encoding with scikit-learn, including a combined-encoding pipeline |
| `seaborn-visualization.ipynb` | Exploring the built-in Titanic dataset: histograms, bar/scatter/violin plots, pair plots, facet grids, heatmaps |

All six notebooks run end-to-end with no errors, outputs included.

- `census.csv` — US Census Bureau county-level population estimates (2010–2015), as used in University of Michigan's *Applied Data Science with Python* course. Source: https://raw.githubusercontent.com/sidsriv/Introduction-to-Data-Science-in-python/master/census.csv
- `life.csv` — the Gapminder dataset (country, continent, year, life expectancy, population, GDP per capita). Source: https://raw.githubusercontent.com/kirenz/datasets/master/gapminder.csv (CC0-licensed via the `gapminder` R/Python package)

## Setup

\`\`\`bash
pip install -r requirements.txt
jupyter notebook
\`\`\`
