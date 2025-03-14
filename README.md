# Bayesian Logistic Analysis

This project applies Bayesian logistic regression to a social network purchase dataset. The analysis is implemented in R and leverages Bayesian inference to assess model parameters, quantify uncertainty, and generate posterior predictions.

## Data Source

- **Dataset:** [Social Network Purchase Data](https://www.kaggle.com/datasets/dragonheir/logistic-regression)  
- **Author:** ANANYA NAYAN, 2017

## Project Overview

In this analysis, you will find:
- **Data Wrangling:** Importing and cleaning the dataset to prepare it for modeling.
- **Model Building:** Fitting a Bayesian logistic regression model to predict the binary outcome (Purchased or Not Purchased) based on predictors such as Estimated Salary and Age.
- **Posterior Inference:** Evaluating the posterior distributions of the model parameters, computing credible intervals, and checking convergence diagnostics (e.g., R-hat values and effective sample sizes).
- **Visualization:** Generating plots to illustrate the posterior distributions and model predictions.

## Imported Libraries

This R notebook loads several key packages to support data manipulation, modeling, and visualization. For example, the notebook includes the following libraries:

- **dplyr** – for data manipulation  
- **ggplot2** – for creating visualizations  
- **rstanarm** – for fitting Bayesian generalized linear models  
- **bayesplot** – for plotting posterior distributions and diagnostics  
- **bayesrules** – for applying Bayesian methods  
- **tidyverse** – for a collection of data science tools  
- **tidybayes** – for tidying Bayesian model outputs  
- **broom.mixed** – for summarizing model results in a tidy format

These packages are loaded at the beginning of the notebook, as shown in the code chunk (see :contentReference[oaicite:0]{index=0}).

## How to Run the Analysis

1. **Download or Clone the Repository:**  
   Get a copy of the project repository containing the R notebook.

2. **Open the Notebook:**  
   - If you prefer a static view, open the `Bayesian Logistic Analysis.nb.html` file in your web browser.  
   - For an interactive experience, open the corresponding R Markdown (.Rmd) file in RStudio.

3. **Execute the Analysis:**  
   Follow the step-by-step instructions in the notebook to load the data, build the Bayesian model, and review the results.

## Results and Interpretation

The notebook provides:
- **Parameter Estimates:** Posterior means, credible intervals, and diagnostic statistics (such as R-hat and effective sample size) for the model coefficients.
- **Posterior Predictions:** Visualizations that illustrate the predicted probabilities for purchasing behavior based on input predictors.
- **Model Diagnostics:** Insights into model convergence and fit.

