# Final-Python-Project-Week-8

# COVID-19 Global Data Tracker

## Project Description
This project analyzes global COVID-19 trends using real-world data from [Our World in Data](https://ourworldindata.org/covid-data). The focus is on tracking cases, deaths and vaccinations across selected countries and over time; with clear visualizations and insights.

## Objectives
- Import and clean COVID-19 data
- Analyze trends in cases, deaths and vaccinations
- Compare metrics across countries (Kenya, United States, India)
- Visualize trends using Python (matplotlib, seaborn, plotly)
- Present findings and insights in an interactive notebook

## Tools & Libraries Used
- pandas
- matplotlib
- seaborn
- plotly
- Jupyter Notebook

## How to Run the Project
1. Make sure you have [Jupyter Notebook](https://jupyter.org/) installed.
2. Install dependencies:
   ```
   pip install pandas matplotlib seaborn plotly
   ```
3. Place the dataset file (`owid-covid-data (1).csv`) in the same folder as the notebook.
4. Open the notebook (`covid_analysis.ipynb`) and run all cells in order.

## Countries Analyzed
- Kenya
- United States
- India

## Key Insights
- **India** had the highest number of total reported cases over time.
- **United States** led in total vaccinations but also had a high death toll.
- **Kenya** showed a slower vaccination rollout compared to others.
- The **death rate** decreased over time as vaccinations increased.
- Data gaps exist but can be handled using interpolation or filling with zero.

## Data Source
- [Our World in Data COVID-19 Dataset](https://ourworldindata.org/covid-data)