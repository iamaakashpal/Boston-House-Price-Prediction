
**`Application Url`** **:** https://boston-house-price--prediction.up.railway.app/

# Boston House Price Prediction
The Boston Housing Dataset is derived from information collected by the U.S. Census Service concerning housing in the area of Boston MA.

**`Description of Dataset`** **:**

The dataset contains 506 observations of 14 variables:

**`CRIM`** **:** per capita crime rate by town

**`ZN`** **:** proportion of residential land zoned for lots over 25,000 sq. ft.

**`INDUS`** **:** proportion of non-retail business acres per town.

**`CHAS`** **:** Charles River dummy variable (1 if tract bounds river; 0 otherwise)

**`NOX`** **:** nitric oxides concentration (parts per 10 million)

**`RM`** **:** average number of rooms per dwelling

**`AGE`** **:** proportion of owner-occupied units built prior to 1940

**`DIS`** **:** weighted distances to five Boston employment centres

**`RAD`** **:** index of accessibility to radial highways

**`TAX`** **:** full-value property-tax rate per $10,000

**`PTRATIO`** **:** pupil-teacher ratio by town

**`B`** **:** 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town

**`LSTAT`** **:** % lower status of the population

**`MEDV`** **:** Median value of owner-occupied homes in $1000's

# Code
The code for the Boston house price prediction model is implemented in Python and is available in the [**`Boston_House_Price_Prediction.ipynb`**](https://github.com/iamaakashpal/Boston-House-Price-Prediction/blob/main/Boston_House_Price_Prediction.ipynb) Jupyter Notebook. The notebook provides step-by-step instructions for data preprocessing, model training, and evaluation.

The following dependencies are required to run the code in this repository:

```
Flask
gunicorn
Jinja2
Werkzeug
numpy
pandas
scipy
scikit-learn
matplotlib
```

# Technical Aspects : 


- **`Front End`** **:** HTML5, CSS

- **`Back End`** **:** Python

- **`Deployment`** **:** railway.app


# Usage
To use this code and dataset, follow these steps
    
#### 1. Clone the repository **:**
        
```
git clone https://github.com/iamaakashpal/Boston-House-Price-Prediction.git
```
#### 2. Navigate to the project directory **:**

```
cd Boston-House-Price-Prediction
```

####  3. Install the required dependencies **:**

```
pip install -r requirements.txt
```

#### 4. Open the Boston_House_Price_Prediction.ipynb Jupyter Notebook **:**

```
jupyter notebook Boston_House_Price_Prediction.ipynb
```

#### 5. Run app.py file **:**

```
python app.py
```
# Results

The prediction model achieves an **`r2_score`** of approximately **`71%`** in predicting the house price. The evaluation metrics and additional insights can be found in the notebook.

**`Best Model`** **:** **`Linear Regression`**

**`Test Score`** **:** **`71%`**

**`Mean Absolute Error`** **:** **`3.1627`**

**`Mean Squared Error`** **:** **`21.5174`**

# Output

![Output Screenshot](https://raw.githubusercontent.com/iamaakashpal/Boston-House-Price-Prediction/main/img/1.png)

![Output Screenshot](https://raw.githubusercontent.com/iamaakashpal/Boston-House-Price-Prediction/main/img/2.png)


# Contributing

If you want to contribute to this project, you can:

- Create an issue to discuss potential improvements or report bugs.
- Fork the repository, make your changes, and submit a pull request.

# License
The code and dataset in this repository are available under the General Public  License. Feel free to use, modify, and distribute them as per the terms of the license.
