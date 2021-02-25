# Overview

A supervised learning model to predict the price of different types of furniture
based on the [Ikea Webscraper](https://github.com/gamladz/price-prediction-ikea)

## Installation

For each file , please run the necessary imports in the opening cell and follow through 
sequentially as each file follows on from each other. For example in Exploratory-Data-Analysis.ipynb


```python
import pandas as pd
import json
from ast import literal_eval
import numpy as np
import matplotlib.pyplot as plt 
import pandas as pd  
from sklearn.linear_model import LinearRegression
import statsmodels.api as sm
from sklearn.model_selection import train_test_split
```

## File Structure

The project is structured in 4 Jupyter Notebooks and CSV's which containe the data
Please run in sequential order as variables in cells depend on previous ouputs.

(1) Exploratory-Data-Analysis.ipynb
- Data Cleaning
- Feature Selection
- Train Test Split

(2) ML.ipynb
- Randomised search CV for Linear Regression, Decision Tree Regressor, Random Forest
- Hyper parameter Optimisation 

(3) Interpretations.ipynb
- Stats Model Analysis
- Recursive Feature Reduction
- P-Value analysis
- Notes on Model Analysis and interperetations for business

(4)Interface.ipynb
- Input form to make predictions


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


## License
[MIT](https://choosealicense.com/licenses/mit/)
