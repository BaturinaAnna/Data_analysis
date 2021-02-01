# Regression

In the work uses 2 sets of data: data on electricity generation at a power plant and data on the level of sound pressure created by the aerodynamic model for its different positions, sizes, modifications and for different levels of sound waves.

Electricity - https://archive.ics.uci.edu/ml/datasets/Combined+Cycle+Power+Plant 
Sound Pressure  - https://archive.ics.uci.edu/ml/datasets/Airfoil+Self-Noise


1. Using the Electricity Generation Dataset:

 - Build a regression and find the regression coefficients for each feature. Determine the direction of influence of the feature and the importance based on these coefficients, give an interpretation for the coefficients.

 - Find coefficients for Ridge regression with parameter 𝜆 = 100. Determine how much the coefficients and R2 score have changed. Construct a graph of the dependence of the values ​​of the coefficients and the R2 score on the change in the parameter 𝜆, change the parameter so that the change in the values ​​of the coefficients is noticeable.

 - Find coefficients for Lasso regression with parameter 𝜆 = 10. How much have the odds and R2 score changed? Construct a graph of the dependence of the values ​​of the coefficients and the R2 score on the change in the parameter 𝜆, change the parameter so that the change in the values ​​of the coefficients is noticeable. Determine which coefficients are zeroed and in what order. Draw a conclusion from this.

 2. Using the SPL dataset:
 - Choose the optimal configuration for obtaining a high R2 score: choose a regression model and the value of its parameters. (R2 score is calculated over the entire sample). 