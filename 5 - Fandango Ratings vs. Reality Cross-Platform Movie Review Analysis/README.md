# Fandango Movie Ratings Analysis

This project analyzes movie ratings and reviews across multiple platforms, including Fandango, Rotten Tomatoes, Metacritic, and IMDB. The analysis uncovers discrepancies in ratings and explores relationships between different rating systems.

---

## Libraries Used
- **Numpy**
- **Pandas**
- **Matplotlib**
- **Seaborn**

---

## Tasks Performed

### Part 1: Fandango Ratings Analysis
1. **Loading Data**: Imported Fandango ratings data.
2. **Exploration**: Examined the structure and properties of the dataset.
3. **Scatterplot**: Analyzed the relationship between film popularity (votes) and ratings.
4. **Correlation**: Computed correlations between numerical columns.
5. **Year Extraction**: Created a column for film release year.
6. **Movies Per Year**: Visualized the count of movies released per year.
7. **Top Movies**: Identified the 10 most-voted movies.
8. **Zero Votes**: Counted and removed movies with zero votes.
9. **Rating Discrepancies**:
    - Visualized discrepancies between displayed (STARS) and actual ratings.
    - Quantified differences and identified movies with large discrepancies.

---

### Part 2: Comparing Ratings Across Platforms
1. **Rotten Tomatoes**:
    - Explored critic vs. user reviews.
    - Calculated and visualized mean differences in ratings.
    - Identified movies with the largest critic-user rating gaps.
2. **Metacritic**:
    - Created scatterplots of critic vs. user ratings.
3. **IMDB**:
    - Analyzed vote counts and identified the most popular movies.

---

### Part 3: Fandango vs. Other Platforms
1. **Data Normalization**:
    - Standardized all ratings to a 0-5 scale.
2. **Distribution Comparison**:
    - Compared normalized rating distributions across platforms.
    - Highlighted Fandango's inflated ratings.
3. **Clustermap**:
    - Visualized clustering of highly rated vs. poorly rated movies.
4. **Worst Movies Analysis**:
    - Identified the 10 lowest-rated movies on Rotten Tomatoes.
    - Compared their normalized ratings across platforms.

---

## Key Findings
- Fandango consistently displays inflated ratings compared to other platforms.
- Movies like *Taken 3* show significant discrepancies, with Fandango displaying much higher ratings than warranted.

---

## Visualizations
- Scatterplots, KDE plots, histograms, and clustermaps to uncover trends and discrepancies.

---

## Conclusion
This project highlights significant biases in Fandango's rating system and provides a comprehensive comparison with other movie review platforms.

