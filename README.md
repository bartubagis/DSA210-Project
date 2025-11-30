# Does High Inflation Reduce Happiness?

## Motivation
Inflation directly impacts purchasing power and living standards. This project investigates whether countries with high inflation rates experience lower happiness levels among their populations. Understanding this relationship can provide insights into economic policy impacts on social well-being and quality of life.

## Data Sources

**1. World Happiness Index (2013-2023)**
- **Source:** [Kaggle - World Happiness Index](https://www.kaggle.com/datasets/simonaasm/world-happiness-index-by-reports-2013-2023)
- **Content:** Happiness scores by country, GDP per capita, social support, life expectancy, freedom, generosity, corruption perception

**2. Global Inflation Data**
- **Source:** [Kaggle - Global Inflation Data](https://www.kaggle.com/datasets/sazidthe1/global-inflation-data)
- **Content:** Annual inflation rates by country across different time periods

Both datasets will be merged using country name and year fields.

## Research Question
Does high inflation rate in countries correlate with lower happiness levels among their populations?
Is there a statistically significant relationship between inflation rates and happiness scores within Norway?

## Hypotheses
- **H0 (Null Hypothesis):** There is no statistically significant relationship between global inflation and global happiness index.
- **H1 (Alternative Hypothesis):** There is statistically significant relationship between global inflation and global happiness index.
- 
- **H0 (Null Hypothesis):** There is no statistically significant relationship between inflation and happiness in Norway.
- **H1 (Alternative Hypothesis):** There is statistically significant relationship between inflation and happiness in Norway.
  

## Methodology

**Data Cleaning**
- Handle missing values and outliers
- Standardize country names across datasets
- Convert data types for proper analysis
- Filter relevant years where both datasets overlap

**Data Integration**
- Merge datasets by country and year
- Calculate year-over-year changes in both inflation and happiness

**Exploratory Data Analysis (EDA)**
- Distribution of happiness scores across different inflation levels
- Correlation heatmap between inflation, happiness, and other economic factors
- Temporal trends: tracking how inflation changes affect happiness over time
- Regional comparisons and scatter plots

**Hypothesis Testing**
- **Correlation Analysis:** Evaluate relationship between inflation and happiness metrics
- **Regression Analysis:** Control for other factors (GDP, social support, etc.) to isolate inflation's effect

**Visualization**
- Scatter plots showing inflation vs. happiness score
- Heatmaps for correlation matrices
- Time-series plots tracking changes over years
- Box plots comparing happiness across inflation categories

## Expected Results
Countries with higher inflation rates are expected to show lower happiness scores. The relationship may be mediated by economic factors like GDP per capita, and different regions may show varying sensitivity to inflation.

## Limitations
- Causation cannot be definitively established (correlation vs. causation)
- Happiness is subjective and influenced by many cultural factors
- Data availability may vary across countries and years
- External factors (political stability, natural disasters) not accounted for

## Tools and Libraries
**Python Libraries:** pandas, numpy, matplotlib, seaborn, scipy, statsmodels, scikit-learn  
**Platform:** Jupyter Notebook / Google Colab

## Ethical Integrity
All datasets are publicly available from Kaggle.
