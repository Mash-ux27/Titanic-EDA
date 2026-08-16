# Titanic EDA

Exploratory data analysis on the Titanic dataset (Kaggle), looking at how survival relates to class, gender, age, and fare.

## Dataset

`train.csv` from Kaggle's [Titanic competition](https://www.kaggle.com/c/titanic/data) — 891 passengers with features like class, sex, age, fare, and survival outcome.

## Approach

- Checked and handled missing values (`Age`, `Cabin`, `Embarked`)
- Built visualizations: survival by class & gender, age distribution, fare distribution by class, correlation heatmap
- Derived insights from each plot

## Key Insights

**Survival by class & gender**
- Women had a significantly higher survival rate than men across all classes
- Men made up the vast majority of those who did not survive
- Lower classes, especially class 3, show a much higher concentration of non-survivors — reflecting that higher-class passengers were prioritized during evacuation

**Age distribution**
- Most passengers were between 15 and 40 years old
- The distribution is positively skewed, with far fewer older passengers (50–80)
- A small but notable spike at ages 0–5 shows a distinct group of infants and toddlers

**Fare by class**
- First-class passengers paid roughly 4–5x more on average than second and third class
- First class shows high price variability — a mix of standard cabins and ultra-luxury suites
- Second and third class fares were tightly clustered and standardized

## Notebook

[View the full analysis](Titanic-EDA.ipynb)