# Anime Data Analysis with Pandas

A beginner-friendly data analysis project using Python and Pandas on an anime dataset. It cleans messy text data, creates new columns from it, and answers a few questions about the data.

## What this project does

- Extracts the **episode count** from the `Title` column (e.g. "Naruto (220 eps)") into a new `Episodes` column
- Extracts the **airing period** from the `Title` column into a `Time_stamp` column
- Calculates how many **months** each anime ran (`Months` column)
- Answers questions such as:
  - Which anime has the highest score?
  - Which anime has the most episodes?
  - Which anime ran the longest?

## Tech used

- Python 3
- Pandas
- NumPy
- python-dateutil
- Jupyter Notebook

## Dataset

`anime.csv` has [number] anime with columns such as `Title`, `Score`, [other columns]. Source: [where you downloaded it, e.g. Kaggle link].

## How to run

1. Clone the repo:
```bash
   git clone https://github.com/YOUR-USERNAME/anime-analysis-pandas.git
   cd anime-analysis-pandas
```
2. Install the libraries:
```bash
   pip install pandas numpy python-dateutil jupyter
```
3. Open the notebook:
```bash
   jupyter notebook
```
4. Run `project1_pandas_.ipynb` from top to bottom. Make sure `anime.csv` is in the same folder.

## What I learned

- Cleaning and extracting data from text columns with `apply()`
- Creating new columns and converting data types
- Working with dates using `datetime` and `relativedelta`
- Filtering data with boolean conditions

## Author

Arpita Singh | 
