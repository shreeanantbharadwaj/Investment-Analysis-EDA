
# Investment Analysis - Exploratory Data Analysis (EDA)

## Overview

This project involves performing exploratory data analysis (EDA) on investment data. The goal is to clean and analyze the data to gain insights into investment patterns and trends. The notebook addresses key questions related to investment rounds, company details, and funding amounts. 

The analysis primarily focuses on cleaning the data, addressing issues like case sensitivity, missing values, and outliers, and then analyzing various aspects of the investment data.

### Key Questions Answered:

1. **How many unique companies are present in the dataset?**
2. **How does case sensitivity impact the uniqueness of company identifiers?**
3. **What insights can be gained from analyzing different investment rounds?**
4. **What are the trends in funding amounts across various companies?**

## Project Workflow

1. **Data Cleaning:**
   - Load the data from the investment rounds and company datasets.
   - Address data quality issues like case sensitivity, missing values, and duplicates.

2. **Exploratory Data Analysis (EDA):**
   - Analyze the unique companies in the dataset.
   - Investigate the impact of case sensitivity on unique identifiers.
   - Explore the trends in funding rounds and funding amounts.
   - Visualize key insights using graphs and charts.

3. **Data Processing:**
   - Transform and process the data to prepare it for further analysis.
   - Compute key metrics such as total funding received by companies, the average funding per round, and the most funded companies.

## Requirements

To run the notebook and reproduce the results, the following libraries are required:

```bash
pip install pandas
pip install matplotlib
pip install seaborn
```

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/investment-analysis-eda.git
   ```

2. Install the necessary dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter notebook:
   ```bash
   jupyter notebook investment-analysis-eda.ipynb
   ```

4. Run the cells to perform data cleaning, exploratory data analysis, and visualize the results.

## Results

The notebook provides key insights into the investment data, including unique companies, funding trends, and the impact of case sensitivity on the data. Visualizations help illustrate these insights in an easy-to-understand format.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
