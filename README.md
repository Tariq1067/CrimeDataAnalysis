# Crime Data Analysis Project

## Project Overview
This project analyses UK police street crime data across four police forces — Metropolitan, West Yorkshire, Devon & Cornwall and North Yorkshire — covering January 2024 to December 2025. The aim is to identify crime patterns and trends to support property investment decisions.

## Folder Structure

### data/raw
Contains the original monthly crime CSV files downloaded from data.police.uk. Each subfolder represents one month of data across all four police forces, covering January 2024 to December 2025.

### data/processed
Contains the cleaned and merged datasets used for analysis.
- clean_street.csv — the final cleaned dataset produced by the preprocessing notebook
- house_prices.csv — median house prices per police force area
- police_population_2024.csv — ONS 2024 population estimates per police force

## Files
- preprocessing.ipynb — loads, cleans and merges all datasets. Run this first.
- analysis.ipynb — performs EDA and produces all visualisations. Run after preprocessing.
- CrimeDataFlowchart.png — data processing flowchart showing the full pipeline
- EDA Report.pdf — full project report with findings and recommendations
- Statement of Work.pdf — project brief and scope

## Requirements
Python 3.x and Jupyter Notebook or VS Code must be installed. Install the required libraries using:

pip install pandas numpy matplotlib seaborn

glob and os are built into Python and do not require installation.

## How to Run
1. Open preprocessing.ipynb and select Python 3 as the kernel
2. Restart kernel and Run All
3. Open analysis.ipynb and select Python 3 as the kernel
4. Restart kernel and Run All

## Project Links
- GitHub Repository — https://github.com/Tariq1067/CrimeDataAnalysis
- Trello Board — https://trello.com/invite/b/69b18cc71c7a24bcec2227ed/ATTIeffe5d8fb7a803526148376a9eabef654366DC2A/crime-analysis-trello-board


## Data Sources
- Police street crime data — https://data.police.uk
- ONS population estimates — https://www.ons.gov.uk
- Median house prices — manually compiled per police force area


## Notes
- The preprocessing notebook must be run before the analysis notebook
- All file paths are relative so the notebooks must be run from inside the crime_data folder
- The kernel must be set to Python 3 for both notebooks to run correctly
