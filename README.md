# Exploratory Data Analysis (EDA) - Titanic Dataset

## Objective
Perform Exploratory Data Analysis to identify patterns, trends, and relationships in the Titanic dataset.

##  Dataset
- **Source:** Kaggle Titanic Dataset
- **File:** `/content/train.csv`
- **Rows:** 891
- **Columns:** 12

##  Tools Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Google Colab

##  Steps Performed
1. **Data Loading & Inspection**
   - Checked dataset shape, info, and missing values.
2. **Data Cleaning**
   - Filled missing Age with median.
   - Filled missing Embarked with mode.
   - Dropped Cabin (too many missing values).
   - Created FamilySize feature.
3. **Univariate Analysis**
   - Plots: histograms, countplots, boxplots.
4. **Bivariate Analysis**
   - Relationship between survival & features.
5. **Correlation Analysis**
   - Heatmap and scatter matrix.
6. **Observations**
   - Females had higher survival rate.
   - 1st class passengers survived more.
   - Children had higher survival rate.
   - Fare has significant outliers.

## Visuals
Included in `EDA_Titanic.pdf`.

## Outcome
Gained insights into dataset structure, missing values, feature relationships, and potential predictors for survival.
