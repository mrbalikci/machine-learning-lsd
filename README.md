# Machine Learning 

## Description 

Source: Wagner, Agahajanian, and Bing (1968). Correlation of Performance
Test Scores with Tissue Concentration of Lysergic Acid Diethylamide in
Human Subjects. Clinical Pharmacology and Therapeutics, Vol.9 pp635-638.

Description: Group of volunteers was given LSD, their mean scores on
math exam and tissue concentrations of LSD were obtained at n=7 time points.

Variables/Columns

TC: Tissue Concentration   1-4
SCORE: Math Score          8-12


* Calculated a regression line using a dataset of LSD drug concentrations vs. math scores.

## Instructions

* Started by creating a scatter plot of the data to visually see if any linear trend exists.

* Next, used sklearn's linear regression model and fit the model to the data.

  * Printed the weight coefficients and the y-axis intercept for the trained model.

* Calculated the `y_min` and `y_max` values using `model.predict`

* Ploted the model fit line using `[x_min[0], x_max[0]], [y_min[0], y_max[0]]`

## Method Used 
* Least Squares 

## Data Set 
* lsd.csv

## Tools Used 
* Python
* Pandas
* Numpy
* Sklearn
* Matplotlib