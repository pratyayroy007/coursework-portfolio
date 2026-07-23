# Pandas / NumPy / Seaborn Practice

Short, runnable exercise notebooks covering core data-handling operations in
pandas and NumPy, categorical encoding with scikit-learn, and Seaborn
visualization basics.

| Notebook | Topic |
|---|---|
| `numpy-basics.ipynb` | Array creation, boolean masking, and array manipulation with NumPy |
| `pandas-series-basics.ipynb` | Creating/indexing `pandas.Series`, plus set operations (intersect, union, symmetric difference) |
| `pandas-assignment.ipynb` | Building and indexing DataFrames from dicts, nested dicts, and NumPy arrays |
| `census-data-analysis.ipynb` | Exploring a real census dataset and a GDP/life-expectancy dataset (`groupby`, filtering, charts) — **requires `census.csv` and `life.csv`**, not included here |
| `categorical-encoding.ipynb` | Label, ordinal, and one-hot encoding with scikit-learn, including a combined-encoding pipeline |
| `seaborn-visualization.ipynb` | Exploring the built-in Titanic dataset: histograms, bar/scatter/violin plots, pair plots, facet grids, heatmaps |

All notebooks except `census-data-analysis.ipynb` run end-to-end with no
external data files — `census-data-analysis.ipynb` needs `census.csv` (US
Census county-level data) and `life.csv` (a gapminder-style GDP/life
expectancy dataset) placed alongside it.

## Setup

```bash
pip install -r requirements.txt
jupyter notebook
```
