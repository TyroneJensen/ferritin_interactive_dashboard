# Ferritin Interactive Dashboard

## Project Overview
This project analyzes ferritin levels across different time periods, providing insights into donor characteristics and ferritin distribution.

🔍 **Note:** For a comprehensive analytical report with detailed insights and visualizations, please refer to the [REPORT.md](REPORT.md) file.

📊 **Interactive Dashboard:** Explore the data in real-time using the [Interactive Dashboard](https://public.tableau.com/app/profile/ty.jensen/viz/WCBSFerritinAnalysisDashboard/Dashboard3)

## Data Sources
The project uses three CSV files containing ferritin results:
- `Ferritin Results Feb22 to Feb23.csv`
- `Ferritin Results Mar22 to Oct23.csv`
- `Ferritin Results Nov23 to Jun24.csv`

## Project Structure
- `Data/`: Contains raw CSV files with ferritin results
- `Notebooks/`: Jupyter notebook for data preprocessing
- `Plots/`: Generated visualizations and analysis plots

## Key Visualizations
The project includes several plots exploring:
- Ferritin category distribution
- Age distribution by ferritin category
- Donations by ferritin category
- Donations by gender and ferritin category
- Donations by race and ferritin category

## Data Preprocessing
The Jupyter notebook `data_preprocessing.ipynb` handles:
- Data import and consolidation
- Data cleaning
- Categorical analysis
- Visualization generation

## Ferritin Categories
The analysis categorizes ferritin levels into:
- Very Low
- Low
- Normal
- High
- Very High

## Requirements
- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Setup
1. Clone the repository
2. Create a virtual environment
3. Install dependencies: `pip install -r requirements.txt`
4. Run Jupyter Notebook: `jupyter notebook`
