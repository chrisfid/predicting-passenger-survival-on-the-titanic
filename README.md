# Logistic Regression Model for Predicting Titanic Passenger Survival

# Requirements

- Windows
- Python 3.11

# Getting Started

Activate the virtual environment
`source .venv/Scripts/activate`

Then:
`pip install -r requirements.txt`

Open Jupyter Notebook:
`Titanic_Logistic_Regression.ipynb`

`Python: Select interpreter` - select venv
& `Install interpreter` (in Jupyter file after running a cell)
& Install smh like epykernel

# Data source

`tested.csv`: https://www.kaggle.com/datasets/brendan45774/test-file

# Developer Setup

(used to create the env)

Create your virtual environment
`py -3.11 -m venv .venv`

Warning! Do *not* use the following:
`python3.11 -m venv .venv`
as it will create Unix environment and some deps won't work.

Verify if the version is valid:
`python3 --version`

Install deps:
`pip install pandas`

After installing new deps, freeze them
`pip freeze > requirements.txt`