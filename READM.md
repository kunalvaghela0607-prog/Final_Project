# COVID-19 Data Analysis and Visualization

## Project Description

This project analyzes worldwide COVID-19 data using the Worldometer daily coronavirus dataset. It covers the full data analysis workflow: loading and exploring the data, cleaning it, computing world and country-level statistics, and presenting the findings through static (Matplotlib / Seaborn) and interactive (Plotly) visualizations. The notebook was built in Google Colab as the final project for the *Python – Data Analysis* course at Red & White Skill Education.

## Features

- Loads and explores the dataset (head, shape, columns, data types)
- Data cleaning: handles missing values, converts dates to datetime, removes duplicate rows
- Calculates **recoveries** as `cases - active cases - deaths`
- Computes world-level totals per day (cases, recoveries, deaths)
- Finds the **Top 10 countries** by total cases and by total deaths
- Compares selected countries (India, USA, Brazil, UK)
- Line charts of world cases, recoveries and deaths over time
- Bar chart of the top 10 countries by cases
- India case:  daily new cases vs. government interventions (Lockdown 1 start and Unlock begins)
- Interactive Plotly charts: country comparison over time and top 10 countries by deaths

## Technologies Used

- Python 3
- Pandas
- Matplotlib
- Seaborn
- Plotly Express
- Google Colab / Jupyter Notebook

## How to Run / Installation

1. **Clone the repository**
   ```bash
   git clone <your-repository-url>
   cd <your-repository-folder>
   ```

2. **Install the required libraries**
   ```bash
   pip install pandas matplotlib seaborn plotly jupyter
   ```

3. **Add the dataset**
   Place `worldometer_coronavirus_daily_data (1).csv` in the same folder as the notebook (or update the file path in the first cell).

4. **Run the notebook**
   - Locally: `jupyter notebook Final_Project_10.ipynb`, then run all cells.
   - On Google Colab: upload `Final_Project_10.ipynb` and the CSV file, then choose *Runtime → Run all*.

## Project Structure

```
├── main.ipynb                     
├── output.png
├── worldometer_coronavirus_daily_data (1).csv  
└── README.md                                   
```

## Author / Developer

**Kunal Vaghela**