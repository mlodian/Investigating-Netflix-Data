# Netflix Movie Duration Analysis

This project analyzes the duration of movies available on Netflix over time to determine if there's a trend indicating that movies are getting shorter. The analysis includes data preprocessing, exploratory data analysis, and statistical modeling.

## Dataset

The dataset used for this analysis is `netflix_data.csv`, which contains information about various shows and movies available on Netflix. The dataset includes columns such as `title`, `release_year`, and `duration`.

## Analysis Steps

1. **Data Loading and Preprocessing**: The Netflix dataset is loaded into a Pandas DataFrame, and data preprocessing steps are performed to filter the data for movies only and subset the required columns.

2. **Exploratory Data Analysis (EDA)**: The average duration of movies is calculated for each release year, and a scatter plot is created to visualize the trend in movie duration over time.

3. **Statistical Modeling**: Linear regression analysis is conducted to quantitatively assess the trend in movie duration over time. The coefficient of determination (R-squared) is calculated to evaluate the goodness of fit of the regression model.

## Results

The analysis reveals a moderate/high level of certainty (based on R-squared value) that movies are getting shorter over time. However, further analysis and domain knowledge may be required to confirm this trend conclusively.

## Repository Structure

- `netflix_data.csv`: Raw dataset used for analysis.
- `netflix_movie_duration_analysis.ipynb`: Jupyter Notebook containing the analysis code.
- `README.md`: Documentation providing an overview of the project.

## Usage

To replicate the analysis:

1. Clone this repository to your local machine.
2. Ensure you have Python and necessary libraries installed (Pandas, Matplotlib, Scikit-learn).
3. Run the `netflix_movie_duration_analysis.ipynb` notebook.

## Conclusion

The analysis provides insights into the duration trends of movies available on Netflix and highlights the need for further investigation to confirm the observed trend.
