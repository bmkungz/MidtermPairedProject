# World Happiness Data Exploration
## Project Overview
This project is a preliminary data analysis exercise using historical and recent data from the **World Happiness Report**. The goal of the included notebook is to load the two core datasets and perform an initial inspection of their structure and contents.
<br />The analysis is performed using a Jupyter Notebook and the Python pandas library.

## Data Sources
This project utilizes two datasets related to the World Happiness Report:
1. world-happiness-report-2021.csv: Contains the 2021 World Happiness data, including metrics such as:

 * Ladder score (The main happiness score)
 * Logged GDP per capita
 * Social support
 * Healthy life expectancy
 * Freedom to make life choices
 * Generosity
 * Perceptions of corruption
2. **world-happiness-report.csv**: Contains historical, multi-year data, including the core metrics like **Life Ladder** (happiness score) and the main explanatory variables over a range of years.
<br />**Note:** The CSV files themselves were not provided, but the code assumes they are in the same directory as the notebook.
## Files in this Repository
File Name |	Description
----|----
**Paired_Project.ipynb** | The main Jupyter Notebook file containing the project's code.
**world-happiness-report-2021.csv** |	Dataset for the 2021 World Happiness Report.
**world-happiness-report.csv** |	Historical dataset for the World Happiness Report.

## Setup and Installation
### Requirements
This project requires **Python 3.x** and the following library:
* **Pandas**

### Installation
1. **Clone the repository** (if hosted in a version control system).
2. **Install the required library** using pip:
```
pip install pandas
```
3. **Ensure the data files** (world-happiness-report-2021.csv and world-happiness-report.csv) are placed in the same directory as the Paired_Project.ipynb file.

## How to Run the Project
1. **Start a Jupyter environment** (Jupyter Notebook or JupyterLab) or open the notebook in **Google Colab**.
2. **Open the Paired_Project.ipynb file**.
3. **Run the cells sequentially** to load the data into two pandas DataFrames, df and df1, and display the first five rows of each to verify data loading.

## Future Enhancements
The current notebook only focuses on data loading and initial inspection. Potential next steps for this project include:
* **Data Cleaning:** Checking for and handling missing values across both datasets.
* **Data Merging:** Combining the two datasets for a comprehensive analysis of happiness trends over time.
* **Visualization:** Creating plots to visualize happiness scores by region and the correlation between the Ladder score and factors like Logged GDP per capita and Healthy life expectancy.
* **Statistical Analysis:** Performing statistical tests or building models to understand which factors most significantly predict national happiness.
