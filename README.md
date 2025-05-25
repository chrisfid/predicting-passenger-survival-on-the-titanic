# predicting-passenger-survival-on-the-titanic

# Requirements

- Windows
- Python 3.11

# Usage

Create your virtual environment
`py -3.11 -m venv .venv`

Warning! Do *not* use the following:
`python3.11 -m venv .venv`
as it will create Unix environment and some deps won't work.

Activate the virtual environment
`source .venv/Scripts/activate`

Then:
`pip install -r requirements.txt`

Open Jupyter Notebook:
`Titanic_Logistic_Regression.ipynb`

`Python: Select interpreter` - select venv
& `Install interpreter` (in Jupyter file after running a cell)
& Install smh like epykernel

Verify if the version is valid:
`python3 --version`

Install deps:
`pip install pandas`

After installing new deps, freeze them
`pip freeze > requirements.txt`

# Data source

`tested.csv`: https://www.kaggle.com/datasets/brendan45774/test-file