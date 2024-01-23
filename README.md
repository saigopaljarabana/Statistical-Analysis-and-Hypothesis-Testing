# Statistical-Analysis-and-Hypothesis-Testing-on-Football-Matches-Python

## Introduction

This project explores FIFA matches data for both men and women, aiming to answer specific questions through hypothesis testing. The analysis focuses on aspects like goal distribution, mean comparisons, and differences between men's and women's matches. The project uses two datasets, `men_results.csv` and `women_results.csv`, providing details on date, teams, scores, and tournament names.

## Data Preparation

New variables, "goal," are created to represent total goals scored in each match for men and women. Unnecessary columns are dropped for simplicity.

## Assumptions and Tests

The analysis checks two critical assumptions, normality and equal variance, before proceeding with hypothesis tests.

### Check Normality

Shapiro-Wilk tests and Q-Q plots are employed to assess the normality of goal distributions for both men and women.

### Histogram Distribution

Histograms are used to visualize skewness and differences between mean and median in goal distributions for men and women.

### Check Variance Equality

Levene's test is conducted to compare variances between men's and women's goal distributions.

## Hypothesis Tests

### Test 1: Mean of Men's Matches

**Objective:** To determine if the mean of men's matches' goals is greater than 2.5.

**Outcome:** The null hypothesis is rejected. The mean of scored goals in men's matches is statistically greater than 2.5.

**Implication:** The analysis suggests that, on average, men's matches tend to have a goal-scoring mean higher than 2.5, providing insights into the goal-scoring patterns in men's FIFA matches.

### Test 2: Difference Between Men's and Women's Goals

**Objective:** To assess if the differences between men's and women's goals are greater or equal to 75%.

**Outcome:** The null hypothesis is not rejected. The differences between men's and women's goals are not statistically greater or equal to 75%.

**Implication:** The analysis indicates that there is no significant evidence to suggest that the differences in goal-scoring between men's and women's matches are substantial.

### Test 3: Mean Number of Goals in FIFA World Cup

**Objective:** To investigate if the mean number of goals in men's matches during the FIFA World Cup is less than in other tournaments.

**Outcome:** The null hypothesis is rejected. The mean number of goals in men's matches during the FIFA World Cup is statistically less than in other tournaments.

**Implication:** The analysis suggests that, on average, men's matches in the FIFA World Cup tend to have fewer goals compared to matches in other tournaments. This provides specific insights into goal-scoring patterns during the FIFA World Cup.

## Outcome

The project offers a comprehensive exploration of FIFA matches data, providing insights into goal distributions, mean comparisons, and differences between men's and women's matches. The outcomes of each hypothesis test contribute to a better understanding of scoring dynamics in various contexts.

## How to Run the Statistical Analysis and Hypothesis Testing on Football Matches Project

Follow these steps to run the Statistical Analysis and Hypothesis Testing on Football Matches project:

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/your-username/Statistical-Analysis-and-Hypothesis-Testing-on-Football-Matches-Python.git
    ```

2. **Install Dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

3. **Open the Jupyter Notebook:**

    ```bash
    jupyter notebook Statistical-Analysis-and-Hypothesis-Testing-on-Football-Matches-Python.ipynb
    ```

4. **Explore and Analyze:**

    Run the notebook cells to execute the code and generate visualizations.

    Note: Make sure to have Python and Jupyter Notebook installed on your machine.

Feel free to customize and modify the paths, commands, and instructions based on your project's specifics.


