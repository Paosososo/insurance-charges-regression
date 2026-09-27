# Predicting Insurance Charges Using Statistical Regression

A Python notebook that explores an insurance charge dataset, tests a group difference, and compares regression models.

[Open the notebook](Insurance_Project_2.ipynb) · [View the original Colab notebook](https://colab.research.google.com/drive/1hIrIWWVYcZmUa4BV0ytQfNn5S5CuDKC8?usp=sharing)

## Approach

The notebook examines 1,338 records with age, sex, BMI, number of children, smoking status, region, and insurance charges. It cleans and encodes variables, plots distributions and relationships, and uses a Welch two sample t test and confidence interval to compare mean charges by smoking status.

It then fits four regression models, including one with a BMI by smoking interaction and one with log transformed charges. Residual plots are used to inspect model assumptions.

## Results shown in the notebook

The age only model reports R² of 0.089. The interaction model reports R² of about 0.839 and adjusted R² of about 0.838. These are measures of fit on the data used in the notebook, not held out prediction scores. The log transformed model uses a different response scale, so its R² should not be compared directly with the models fitted to charges.

## Running the notebook

Open the notebook in Colab and run the cells in order. It uses pandas, NumPy, Matplotlib, Seaborn, SciPy, and statsmodels. Check that the notebook's data source is available before running it.

The saved outputs document an earlier run. A clean run in a fresh runtime has not yet been verified for this repository.

The methods and figures above come from the [notebook code and saved outputs](Insurance_Project_2.ipynb).
