# Netflix Movie Data Analysis

Exploratory data analysis (EDA) on a dataset of 9,800+ movies to uncover
trends in genres, ratings, popularity, and release years.

## What this project does
- Cleans the data: datetime conversion, null handling, duplicate checks, dropping irrelevant columns
- Categorizes vote averages into four quartile-based popularity tiers
- Splits multi-genre entries into one genre per row using `explode()`
- Visualizes genre frequency, vote distribution, popularity extremes, and releases per year

## Tech stack
Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

## Key questions answered
- Which genre appears most often?
- How are ratings distributed?
- Which movies are the most and least popular?
- Which year had the most releases?

## How to run
1. Clone the repo
2. Install dependencies: `pip install pandas numpy matplotlib seaborn`
3. Open `Netflix_Dataset.ipynb` and run all cells
