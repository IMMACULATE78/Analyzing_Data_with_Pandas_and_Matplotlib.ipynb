# Analyzing Data with Pandas and Visualizing Results with Matplotlib

This project demonstrates how to load, analyze, and visualize a dataset using **Pandas** and **Matplotlib** in Python.

## Objective
- Load a CSV dataset and explore the data using pandas.
- Perform basic statistical analysis on the dataset.
- Visualize the data with various chart types (Line chart, Bar chart, Histogram, and Scatter plot).

## Steps Involved

### 1. Data Loading and Exploration
- The dataset was loaded from a CSV file.
- Initial exploration was done using `df.head()` to inspect the first few rows.
- Missing values were checked using `df.isnull().sum()`, and any missing data was handled.

### 2. Basic Data Analysis
- Grouped the data by species and computed the average values of the numerical columns for each group using `.groupby()`.
- Calculated basic statistical measures such as mean, median, and standard deviation using `.describe()`.

### 3. Data Visualization
Four types of plots were created:
- **Line chart** showing trends over time.
- **Bar chart** comparing the average petal length per species.
- **Histogram** to display the distribution of sepal width.
- **Scatter plot** to visualize the relationship between sepal length and petal length.

## Observations
- The dataset contains 150 rows and no missing values.
- Different species (0, 1, 2) have distinct average values for features like petal and sepal lengths.
- The line chart shows the trend of sepal length across data entries.
- The bar chart shows species 2 has the highest average petal length.
- The histogram indicates most sepal width values are between 2.5 cm and 3.5 cm.
- The scatter plot shows a strong relationship between sepal length and petal length, with species forming clear clusters.

## Requirements
- Python 3.x
- pandas
- matplotlib
- seaborn (for better visualization)

## How to Run the Code
1. Clone this repository to your local machine.
2. Install the required libraries:
   ```bash
   pip install pandas matplotlib seaborn
