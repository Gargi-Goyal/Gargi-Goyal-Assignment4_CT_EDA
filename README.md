# EDA on Titanic Dataset 

## Project Overview

This project provides an in-depth exploratory data analysis (EDA) of the famous Titanic dataset, culminating in essential machine learning data preparation steps and advanced statistical hypothesis testing. The goal is to uncover significant patterns related to passenger survival through rigorous analysis and compelling visualizations.

## Key Features & Analysis Highlights
This EDA covers a wide range of analytical techniques to extract valuable insights from the Titanic dataset:

### Comprehensive Missing Values Analysis
* Detailed count and percentage of missing values across all features, accompanied by a clear visualization for quick identification of data gaps.

### Advanced Visualizations
* *Violin Plots:* Illustrates the distribution of age by survival status and gender, revealing nuances in age-related survival.
* *Logistic Regression Plot:* Visualizes the survival probability based on key features, helping to understand trends.
* *FacetGrid:* Provides multi-dimensional age distribution analysis, segmenting data across various categorical features for deeper insights.
* *Family Size Impact Analysis:* Dedicated visualizations to explore how the size of a passenger's family aboard influenced their survival.

### Statistical Tests
* *T-tests:* Performed to determine statistically significant differences in age between various groups (e.g., survivors vs. non-survivors).
* *ANOVA (Analysis of Variance):* Used to assess significant differences in fare across multiple categories or groups.
* *Chi-square Tests:* Applied to analyze relationships and dependencies between categorical variables (e.g., Pclass vs. Survival, Sex vs. Survival).

### Additional Analysis Features
* *Family Size Calculation:* Derivation and analysis of a new family_size feature to better understand social group dynamics.
* *Deck Analysis:* Exploration of how the assigned deck might correlate with survival rates.
* *Correlation Matrix:* A visual representation of the correlation between numerical features, annotated for clarity, to identify strong relationships.

### Interactive Plotly Visualizations
* *2D Scatter Plot:* An interactive visualization displaying age vs. fare, colored by survival status, with hover information including passenger class. This allows dynamic exploration of survival patterns.
* *3D Plot:* A three-dimensional scatter plot showcasing age, fare, and passenger class together, colored by survival and symbolized by sex, offering a comprehensive view of complex interactions.

### Machine Learning Preparation
* *Age Imputation Strategy Comparison:* Tests three different strategies (mean, median, most_frequent) for handling missing 'age' values.
* *Model Accuracy Evaluation:* Demonstrates how each imputation strategy affects the accuracy of a RandomForestClassifier model, providing practical insights into data preprocessing choices.

### Advanced Hypothesis Testing
* *T-test for Class Survival Differences:* Statistically evaluates if there's a significant difference in survival rates between different passenger classes (e.g., 1st vs. 3rd class).
* *Kolmogorov-Smirnov (KS) Test for Age Distributions:* Determines if the age distribution of survivors is significantly different from that of non-survivors.
* *ANOVA for Family Size Impact:* Assesses if family size has a statistically significant effect on survival rates across various family size groups.
* *Visualization of p-values:* A bar plot illustrating the statistical significance of the hypothesis test results, using a -log10(p-value) scale for clear interpretation against a significance threshold.

## Technologies Used
* Python 3.x
* Pandas (for data manipulation)
* NumPy (for numerical operations)
* Seaborn (for statistical data visualization)
* Matplotlib (for plotting)
* Plotly Express (for interactive visualizations)
* Scikit-learn (sklearn) (for machine learning models and preprocessing)
* SciPy (for statistical tests)

## Insights Gained
This project offers a deep dive into the Titanic disaster, providing insights into:
* The impact of missing data on model performance and how different imputation methods can yield varying results.
* Statistically significant factors influencing survival, such as passenger class, age distribution, and family size.
* The power of interactive visualizations to explore complex relationships in the data.
