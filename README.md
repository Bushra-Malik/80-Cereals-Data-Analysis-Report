# 80 Cereals Data Analysis Report

The **80 Cereals Data Analysis** project aims to analyze a dataset containing nutritional information about 80 cereal products. The primary objectives of the project include:

1. **Data Loading**:
   - The project begins with importing necessary libraries and loading the cereal dataset from a CSV file using Pandas.

2. **Data Checking**:
   - Initial checks are performed to identify missing values, duplicate entries, and the data types of each column. This ensures that the dataset is in a suitable format for analysis.

3. **Data Cleaning**:
   - Missing values are addressed by filling them with zeros or appropriate alternatives. Duplicate entries are removed to maintain data integrity, and data types are confirmed to be correct for numerical columns like calories and sugars.

4. **Nutritional Analysis**:
   - The project identifies cereals with the highest and lowest calories and sugar content, providing insights into the nutritional extremes present in the dataset.

5. **Correlational Analysis**:
   - A correlation matrix is calculated to assess relationships between numerical attributes, such as calories, sugars, and ratings, highlighting potential dependencies.

6. **Visualization of Distributions**:
   - Histograms and Kernel Density Estimation (KDE) plots are created to visualize the distribution of key attributes: calories, sugars, and ratings. This helps to understand the spread and tendencies of these variables.

7. **Correlation Heatmap Visualization**:
   - A heatmap is generated from the correlation matrix, visually representing the strength and direction of relationships between variables, making it easier to identify patterns.

8. **Manufacturer Comparison**:
   - The project analyzes average nutritional values by manufacturer, providing insights into which manufacturers produce higher-calorie or higher-sugar cereals through bar plots.

9. **Rating vs. Sugars Scatter Plot**:
   - A scatter plot is created to visualize the relationship between sugar content and cereal ratings, with points color-coded by manufacturer to identify trends among different brands.

10. **Rating vs. Fiber Scatter Plot**:
    - Another scatter plot shows the relationship between fiber content and ratings, helping to determine if cereals high in fiber tend to receive better ratings.

11. **Summary**:
    - The project concludes with a summary of key insights, including the cereals with the highest and lowest calories and sugars and which manufacturers have higher average calorie cereals.

This structured approach to data analysis not only highlights the nutritional profiles of various cereals but also provides valuable insights for consumers looking to make informed dietary choices.

## Dataset Credit
The dataset used for this analysis is sourced from Kaggle and can be found at the following link: [80 Cereals Dataset](https://www.kaggle.com/datasets/crawford/80-cereals).

