# Billionaires Dataset Analysis

## Overview

This project analyzes the **Billionaires Dataset** from CORGIS, focusing on the demographics and financial data of the world's billionaires. The dataset includes information on their wealth, citizenship, age, gender, and companies. Through data exploration and visualization, this project aims to uncover patterns and insights within this unique population.

### Key Objectives
- Understand the distribution of wealth, age, and gender among billionaires.
- Analyze the relationship between age and wealth.
- Visualize wealth categories (low, medium, high) to observe patterns in wealth accumulation.
  
## Features

- **Data Overview**: A preview of key billionaire attributes (name, rank, year, company, age, gender, citizenship, and wealth).
- **Statistical Insights**:
  - Total number of billionaires.
  - Average rank and age.
  - Maximum wealth and details about the wealthiest billionaire.
  - Gender distribution (male vs. female billionaires).
- **Visualizations**:
  - Histogram of billionaire ages.
  - Bar chart for gender distribution.
  - Pie chart for wealth categories (low, medium, high).
  - Scatter plot of billionaire wealth vs. age.

## Technologies Used

- **Python**: Main programming language.
- **Libraries**:
  - `JupyterLab`: For interactive data exploration and visualization.
  - `Matplotlib`: For data visualization.
  - `PrettyTable`: For tabular data representation.
  - `NumPy`: For statistical calculations.

## Dataset

The dataset is sourced from the [CORGIS Dataset Project](https://corgis-edu.github.io/corgis/python/billionaires/). It contains detailed information about billionaires, including their demographics and financial status.

## How to Run

1. Clone the repository:
    ```bash
    git clone <repository-link>
    ```
2. Install the required Python packages:
    ```bash
    pip install matplotlib prettytable numpy
    ```
3. Run the analysis script:
    ```bash
    python billionaires_analysis.py
    ```

## Insights and Findings

- The average age of billionaires is **53.34 years**.
- The billionaire with the maximum wealth holds **76.0 billion** dollars.
- Gender distribution shows a notable underrepresentation of female billionaires.
- Wealth tends to grow with age, although there are significant variations.

## References

The project was supported by the following references:

- [Programiz: Dictionary items() method](https://www.programiz.com/python-programming/methods/dictionary/items)
- [W3Schools: Python map() function](https://www.w3schools.com/python/ref_func_map.asp)
- [RealPython: Python f-strings](https://realpython.com/python-f-strings/)
- [W3Schools: Matplotlib](https://www.w3schools.com/python/matplotlib_pyplot.asp)
- [GeeksforGeeks: PrettyTable in Python](https://www.geeksforgeeks.org/creating-tables-with-prettytable-library-python/)
- **ChatGPT**: Used to troubleshoot error messages and get explanations on using libraries.
