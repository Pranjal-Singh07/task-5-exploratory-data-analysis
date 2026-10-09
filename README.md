# Exploratory Data Analysis (EDA) – Titanic Dataset

This project explores the Titanic passenger dataset using Python to understand data distributions, missing values, and relationships between passenger details and survival rates. It was completed as part of **Data Analyst Internship – Task 5**.

## Objectives

* Explore and understand the dataset.
* Identify and handle missing values.
* Analyze passenger survival rates.
* Visualize distributions, relationships, and correlations.
* Summarize the main findings from the analysis.

## Tools Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Google Colab

## Work Performed

* Inspected the dataset using `info()` and missing-value checks.
* Filled missing values in the `Age` and `Embarked` columns.
* Used a pairplot to explore relationships between selected variables.
* Created a correlation heatmap.
* Analyzed survival rates by sex and passenger class.
* Created a histogram for age distribution.
* Used a scatterplot to explore fare and `Parch`.
* Used a boxplot to identify potential outliers in ticket fares.

## Key Findings

* The dataset contains 891 passenger records.
* 342 passengers survived and 549 did not survive.
* Female passengers had a higher survival rate than male passengers.
* First-class passengers had the highest observed survival rate, while third-class passengers had the lowest.
* The `Age` column had 177 missing values, and the `Cabin` column had 687.
* Ticket fares were right-skewed, with some high-value outliers.
* `SibSp` and `Parch` showed a positive correlation.

## Files

* `EDA_Titanic.ipynb` – Notebook containing the analysis and visualizations.
* `Titanic_EDA_Report.pdf` – Report describing the analysis and findings.
* `train.csv` – Dataset used for the analysis, if included.

## How to Run

1. Download or clone this repository.
2. Open `EDA_Titanic.ipynb` in Google Colab.
3. Upload `train.csv` to Colab if it is not already available.
4. Run the notebook cells in order.

**Note:** The notebook currently uses `/content/train.csv` as the dataset path.

## Conclusion

This project provided practical experience with data cleaning, descriptive statistics, and visualization. The analysis highlighted patterns in passenger survival, age distribution, passenger class, and ticket fares.
