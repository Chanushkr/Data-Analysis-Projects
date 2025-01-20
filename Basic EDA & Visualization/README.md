# Data Analysis and Visualization with Python

This project demonstrates the step-by-step process of performing data analysis and visualization using Python libraries like NumPy, Pandas, Matplotlib, and Seaborn. The dataset used in this project contains some missing and unorganized data to showcase data cleaning, exploratory data analysis (EDA), and visualization techniques.

## Project Overview

### Steps Followed:
1. **Import Libraries**: Essential libraries for data handling and visualization.
2. **Load Dataset**: Read the dataset from a CSV file.
3. **Understand Data**:
   - Display the first few rows.
   - Summarize data types and statistics.
4. **Handle Missing Values**:
   - Identify missing values.
   - Impute or drop missing values based on context.
5. **Clean Data**:
   - Rename columns.
   - Handle duplicates and reformat data.
6. **Exploratory Data Analysis (EDA)**:
   - Analyze distributions, relationships, and outliers.
7. **Data Visualization**:
   - Create insightful visualizations using Matplotlib and Seaborn.

## Dataset Description

The dataset includes the following columns:
- **Name**: Name of the employee.
- **Age**: Age of the employee (some values are missing).
- **Gender**: Gender of the employee (some values are missing).
- **Salary**: Monthly salary of the employee (some values are missing).

### Data Issues Addressed:
- Missing values in the `Age` column were filled with the mean age.
- Rows with missing values in the `Name` or `Gender` columns were removed.
- Column names were standardized for better readability.

## Visualizations Included

1. **Age Distribution**: A histogram showing the frequency of different age groups.
2. **Salary Boxplot**: A boxplot visualizing the distribution of monthly salaries.
3. **Gender Count**: A countplot displaying the number of employees by gender.
4. **Age vs. Salary**: A scatter plot showing the relationship between age and monthly salary, categorized by gender.

## Tools Used

- **NumPy**: For numerical computations.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For creating static visualizations.
- **Seaborn**: For creating aesthetically pleasing and informative plots.

## How to Run the Code

1. Clone this repository:
   ```bash
   git clone https://github.com/Chanushkr/Data-Analysis-Projects/tree/main/Basic%20EDA%20%26%20Visualization
   ```
2. Navigate to the project directory:
   ```bash
   cd Basic EDA & Visualization
   ```
3. Install the required libraries:
   ```bash
   pip install numpy pandas matplotlib seaborn
   ```
4. Run the Python script:
   ```bash
   python Basic_Visualization.py
   ```

## Conclusion

This project provides a comprehensive guide to data analysis and visualization, focusing on handling messy datasets and extracting meaningful insights. The visualizations offer a clear representation of data trends and distributions.

---

**Author**: Chanush KR

**GitHub**: https://github.com/Chanushkr/Data-Analysis-Projects/tree/main

**LinkedIn**: https://www.linkedin.com/in/chanush-kr/
