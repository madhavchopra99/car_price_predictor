creating a Linear Regression and Lasso regression model for sale of second hand cars.

## Dataset Columns

* name
* year
* selling price
* present price
* kilometers driven
* fuel type
* seller type
* transmission type
* owner

## Dependencies

* Pandas
* Scikit-Learn
* Seaborn
* Matplotlib
* Numpy

## Data Graphs

### Pie Chart for Seller Type

![Pie Chart](https://raw.githubusercontent.com/madhavchopra99/car_price_predictor/main/screenshots/Seller%20Type%20-%20Pie%20Chart.png)

### Count graph for Transmission Type w.r.t. Fuel Type

![Count Chart](https://raw.githubusercontent.com/madhavchopra99/car_price_predictor/main/screenshots/Transmission%20Type%20vs%20Fuel%20Type%20-%20CountPlot.png)

## Model Evaluation

we are using 8:2 train and test split respectively

### Linear Regression

![Scatter Plot](https://raw.githubusercontent.com/madhavchopra99/car_price_predictor/main/screenshots/Actual%20vs%20Predicted%20Prices%20on%20Test%20Data%20-%20Linear%20Regression.png)

using r square evaluation linear regression scores 85% on test data.

### Lasso Regression

![Scatter Plot](https://raw.githubusercontent.com/madhavchopra99/car_price_predictor/main/screenshots/Actual%20vs%20Predicted%20Prices%20on%20Test%20Data%20-%20Lasso%20Regression.png)

using r square evaluaton lasso regression scores 84.9% on test data.

