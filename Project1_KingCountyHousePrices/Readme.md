# Data science project in week 3 of the data science bootcamp [@neuefische](https://www.neuefische.de/)

King County House Prices:
* Exploratory Data Analysis based on a dataset for house prices in King County
* Goal: Predict House Prices with a linear regression analysis, depending on selected features in the dataset
* First data exploration:
   * Have a look at the dataset 
     (nr. of observations, nr. of features, head and tail of the dataset, datatype of the features)
   * Explore the target variable ("price")
* General data cleaning
   * Delete very expensive houses
   * Analyse and replace missing values
   * Delete variables that are not interesting for the prediction ("id", "date")
   * Explore the remaining variables (which values do they take, are their outliers or other problems in the data)
   * Delete more variables that are not relevant for the prediction ("lat", "long", "condition", "waterfront")
* Explain the business case: Consider whether the model is depending on the region
   * Define 4 regions in King County
   * Create 4 sub-dataframes for the 4 regions
   * Explore the target variable ("price") for each region
   * Get a first impression of possible (linear) relationships (calculate and plot the correlations of all features)
   * Identify features with high correlations and state observations from the correlations
* A first simple model
   * Build a first model using simple linear regression and use the feature with the highest correlation ("sqft_living")
   * Analyse whether to use a logarithmic transformation
   * Build an analogous model for each of the region
   * Analyse statistical significance, performance and residuals (for each region)
* Improve the models by adding more features
   * Add the feature "grade" as a categorical variable
   * Analyse statistical significance, performance and residuals (for each region)
* Visualization
   * Simple linear regression (first model): Compare performance of the model built from the entire dataset with the model built for each region
   * Multiple linear regression (second model): Compare performance of the model built from the entire dataset with the model built for each region
* Conclusions
* Outlook
