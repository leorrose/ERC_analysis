# ERC_analysis

Analyzing Granted Projects of the European Research Council (ERC) to Understand Where Science Money Goes

## Repository Contents
This repository contains code for the Ben Gurion University "The Art of Analyzing Big Data - The Data Scientist’s Toolbox (372.2.5401)" course project. This code was created with <b> Python(3.10), pandas, numpy and more libraries</b>.

- Data - [ERC data](https://github.com/leorrose/ERC_analysis/blob/main/data/erc_data.csv),  [ERC dates](https://github.com/leorrose/ERC_analysis/blob/main/data/erc_dates.csv), [google scholar publications per year](https://github.com/leorrose/ERC_analysis/blob/main/data/publications_per_year.csv), [google scholar citations per year](https://github.com/leorrose/ERC_analysis/blob/main/data/cites_per_year.csv), [google coauthors](https://github.com/leorrose/ERC_analysis/blob/main/data/coauthors.csv)

- Code - [project notebook](https://github.com/leorrose/ERC_analysis/blob/main/project.ipynb), [grants dates scrapping](https://github.com/leorrose/ERC_analysis/blob/main/date_scraper.ipynb), [google scholar scrapping](https://github.com/leorrose/ERC_analysis/blob/main/scholar_scrapper.ipynb).

- Report - [Report](https://github.com/leorrose/ERC_analysis/blob/main/report.pdf).

## Project Setup and Run:

1. Clone this repository.
2. Open cmd/shell/terminal and go to project folder: `cd ERC_analysis`
3. Create conda environment: `conda env create -f environment.yml`
4. Activate conda environment `conda activate env`
5. Install dependencies `while read requirement; do conda install --yes $requirement; done < requirements.txt`
6. Run each notebook in the environment.

Please let me know if you find bugs or something that needs to be fixed.

Hope you enjoy.
