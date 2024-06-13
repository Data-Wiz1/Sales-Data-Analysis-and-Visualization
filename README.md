
# Sales Data Analysis and Visualization

This repository contains a Jupyter Notebook that analyzes customer shopping data to extract insights about sales trends, gender distribution, category distribution, and age group distributions. The analysis includes data cleaning, exploratory data analysis (EDA), and visualization using various Python libraries such as Pandas, Matplotlib, and Seaborn.

## Dataset

The dataset used in this project is the Customer Shopping Dataset, which can be found on Kaggle: [Customer Shopping Dataset](https://www.kaggle.com/datasets/mehmettahiraslan/customer-shopping-dataset).

## Notebook Overview

### Sections:

1. **Importing Libraries**:
    - Import necessary libraries for data manipulation, analysis, and visualization.

2. **Loading and Cleaning Data**:
    - Load the dataset and perform initial data cleaning steps such as dropping unnecessary columns.

3. **Data Inspection**:
    - Display the first few rows of the dataset to understand its structure.
    - Check for data types and missing values.

4. **Duplicate Check**:
    - Check for duplicate rows in the dataset.

5. **Gender Distribution Analysis**:
    - Calculate the distribution of genders in the dataset.
    - Visualize the gender distribution using a pie chart.

6. **Time-Based Sales Analysis**:
    - Convert the `invoice_date` column to datetime format.
    - Group sales data by shopping mall and invoice date.
    - Create time series plots for total sales over time for each shopping mall.

7. **Category Distribution Analysis**:
    - Calculate the distribution of different product categories.
    - Visualize the category distribution using a bar chart.

8. **Gender and Category Analysis**:
    - Analyze the relationship between gender and product categories.
    - Visualize the count of each category for different genders using a count plot.

9. **Age Group Analysis**:
    - Segment customers into different age groups (<30, 30-40, 40-50, >50).
    - Display the segmented customer data.


## Dependencies

- numpy
- pandas
- matplotlib
- seaborn
- warnings

## License

This project is licensed under the MIT License.

## Acknowledgements

- Thanks to Mehmet Tahir Aslan for providing the [Customer Shopping Dataset](https://www.kaggle.com/datasets/mehmettahiraslan/customer-shopping-dataset) on Kaggle.
