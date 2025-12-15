# PySocialLab

PySocialLab is a pure Python project for cleaning, exploring, and recommending in social networks. It uses only the Python standard library and Jupyter notebooks to process JSON data describing users, friendships, and liked pages.

## Features

- Clean raw social data (remove duplicates, inactive users/pages)
- Recommend pages based on common user interests
- Recommend people via mutual friend connections
- 100% pure Python — no external dependencies

## Notebooks

- `data_cleaning.ipynb`: Load and clean raw data, output cleaned JSON
- `data_visualization.ipynb`: Display users, connections, and pages from loaded data
- `pages_yml.ipynb`: Recommend pages a user might like based on similar users' interests
- `people_ymk.ipynb`: Recommend people ("People You May Know") via mutual friend connections

## Getting Started

Prerequisites: Python 3.7+ and Jupyter (`jupyterlab` or `notebook`).

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install jupyter
jupyter lab
```

## Usage

1. Run `data_cleaning.ipynb` to clean raw JSON data and output `cleaned_data2.json`.
2. Run `data_visualization.ipynb` to view users, connections, and pages.
3. Use `pages_yml.ipynb` to get page recommendations for a user ID.
4. Use `people_ymk.ipynb` to get friend recommendations for a user ID.

All work is done in pure Python within notebooks.