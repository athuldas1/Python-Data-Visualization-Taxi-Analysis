# Python Data Visualization and Analysis

## Google Colab Notebook

**Google Colab Link:**

[https://colab.research.google.com/drive/10Dc8-RXfYOI3PE9OHBVVkYvZmhmIC2u0?usp=sharing]

---

## Project Overview

This project focuses on data cleaning and visualization using Python. The Seaborn Taxis dataset is used to explore taxi trip information and understand different patterns through graphical representations.

The project includes handling missing values, analyzing numerical and categorical data, and creating different visualizations using Matplotlib, Pandas, and Seaborn.

## Dataset

* **Dataset Name:** Taxis Dataset
* **Source:** Seaborn Built-in Dataset
* **Loading Method:** `sns.load_dataset("taxis")`

The dataset contains taxi trip information, including pickup timestamps, distance, fare, tips, payment methods, pickup boroughs, and other trip details.

## Technologies and Libraries Used

* **Python:** Programming language used for data analysis.
* **Pandas:** Data manipulation, cleaning, and analysis.
* **Matplotlib:** Creating basic data visualizations.
* **Seaborn:** Creating statistical and advanced visualizations.
* **Google Colab:** Writing and executing Python code.

## Project Workflow

### 1. Data Loading

* Imported the required Python libraries.
* Loaded the Taxis dataset using Seaborn.
* Inspected the dataset using Pandas.

### 2. Data Cleaning

* Identified missing values using `isnull()` and `sum()`.
* Separated numerical and categorical columns using `select_dtypes()`.
* Handled missing numerical values using median.
* Handled missing categorical values using mode.
* Removed rows with missing critical values using `dropna()`.

### 3. Data Visualization

Created the following visualizations to explore the taxi dataset.

**Visualizations using Matplotlib and Pandas:**

1. Line Chart – Fare Over Time
2. Bar Chart – Total Fare by Pickup Borough
3. Pie Chart – Trips by Payment Method
4. Histogram – Distribution of Taxi Distance
5. Box Plot – Tip Amount by Pickup Borough

**Visualizations using Seaborn:**

6. Count Plot – Number of Trips by Pickup Borough
7. Scatter Plot – Relationship Between Distance and Fare
8. Heatmap – Correlation Between Numerical Variables
9. Pair Plot – Relationships Between Multiple Variables
10. Violin Plot – Fare Distribution by Payment Method

## Key Python Functions Used

| Function          | Purpose                              |
| ----------------- | ------------------------------------ |
| `head()`          | Displays the first five rows         |
| `info()`          | Provides dataset information         |
| `isnull()`        | Identifies missing values            |
| `select_dtypes()` | Selects columns based on data types  |
| `median()`        | Calculates the median                |
| `mode()`          | Finds the most frequent value        |
| `fillna()`        | Handles missing values               |
| `dropna()`        | Removes missing values               |
| `groupby()`       | Groups data by categories            |
| `value_counts()`  | Counts unique values                 |
| `to_datetime()`   | Converts values into datetime format |
| `corr()`          | Calculates correlations              |
| `plot()`          | Creates visualizations               |

## Learning Outcomes

Through this project, I gained practical experience in:

* Loading and exploring datasets using Pandas.
* Identifying and handling missing values.
* Understanding numerical and categorical data types.
* Creating different charts using Matplotlib and Seaborn.
* Analyzing relationships between numerical variables.
* Understanding data distributions and identifying potential outliers.
* Presenting data insights through visualizations.

## Conclusion

This project helped me develop practical knowledge of Python data analysis and visualization. By working with the Taxis dataset, I learned how to clean data, handle missing values, and create different visualizations to understand patterns and relationships within a dataset.

---

**Project Category:** Data Analytics

**Tools:** Python | Pandas | Matplotlib | Seaborn | Google Colab

