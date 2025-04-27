# Cricket Career Statistics Analysis 🏏

This project focuses on retrieving, cleaning, and analyzing cricket career statistics data from ESPNcricinfo.

## 📥 Data Source
The original data was retrieved from:  
> [ESPNCricinfo - Highest Career Batting Averages](https://www.espncricinfo.com/records/highest-career-batting-average-282910)

## 🛠️ Libraries Used
- **Pandas** for data manipulation and cleaning
- **Matplotlib** for visualization
- **Seaborn** for advanced plotting

## 📄 Project Overview
The dataset (`Cricket_Data.csv`) contains records of top cricketers, including their playing span, matches, innings, runs, batting averages, strike rates, hundreds, fifties, ducks (0 runs), and boundary counts.

The following steps were performed:

### 1. Data Cleaning
- Replaced missing values represented by '-' with `NaN`.
- Handled inconsistent values (e.g., '+' signs in data fields like `BF`, `4s`) during data cleaning.

### 2. Data Analysis
- **Average Career Length**: Calculated the average number of years players had active international careers.
- **Average Strike Rate (>10 years)**: Computed the average batting strike rate for players whose careers lasted more than 10 years.
- **Players Before 1960**: Found the number of players who started their careers before 1960.
- **Highest Innings Score by Country**: Identified the maximum highest individual score categorized by the player's country.
- **Average 100s, 50s, and Ducks by Country**: Computed the country-wise averages of centuries (100s), half-centuries (50s), and ducks (0s).

## 📊 Visualizations
- Bar plots and statistical summaries were created using **Matplotlib** and **Seaborn** to showcase trends and insights from the analysis.

## 📁 Files
- `Cricket_Data.csv` — Cleaned dataset used for analysis
- `Cricket_Batting_Analysis.ipynb` — Jupyter Notebook containing the complete code (data loading, cleaning, and analysis)
- Visual outputs saved as PNG files (optional, if you generate plots)

## 🚀 How to Run
1. Clone this repository.
2. Ensure you have the necessary libraries installed:
   ```bash
   pip install pandas matplotlib seaborn


## 🎥 Reference and Credits
This project was inspired by the following tutorial:

YouTube Video - Data Cleaning and Analysis using Pandas

I have modified and extended the project by adding my own data visualizations and additional analysis to enhance the insights.

## Conclusion
This project provided a structured approach to cleaning and analyzing real-world sports data.
By performing key statistical calculations and visualizing the results, we gained valuable insights into the careers of some of the greatest cricketers.

The addition of customized visualizations enhanced the interpretability of the data and highlighted important trends across different countries and time periods.
