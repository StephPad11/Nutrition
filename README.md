# Nutrition
Calculating nutrition information for menu items or home recipes with a dataset of nutrition info of basic products.

The dataset nutrition.csv was downloaded from kaggle, https://www.kaggle.com/datasets/trolukovich/nutritional-values-for-common-foods-and-products,
so thank you to Aleksandr Antonov for compiling and publishing this information.

The original dataset has been cleaned and written to a new .csv named cleaned_nutrition_data.

That data is used by nutrition_calculator_one to create an html app using Dash that collects user inputs for ingredients
and serving size to produce a table of nutrition values and charts of those values for the inputted recipe.