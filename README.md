# House-Price-Predictor
An intelligent system based on machine learning that can predict the price of house based on its features.
## Table of Contents
[Introduction](#Introduction)
[Requirements](#Requirements)
[How-To-Use](#How-To-Use)
[Dataset](#Dataset)
[Technical-Details](#Technical-Details)
[Algorithm](#Algorithm)
[Lisence](#Lisence)
### Introduction
Real estate and flat business is increasing a lot with urbanization. The prices of these houses vary from place to place and from architecture to architecture. Now assigning the prices to these houses so that both the vendor and buyer will be benifited equally is the real critical issue. Currently the real estate market is depending on manual price assignment. But the problem with this is as the number of features increase it will be difficutl to estimate the correct price. So the objective of this project is to design a machine learning based system that takes the house features as input and produces the house price in dollars as output.  
### Requirements
Python 3.5 or above version with pandas,matplotlib,scikit-learn,seaborn and pickle packages.
Jupyter lab/Jupyter notebook
No specific hardware requirements and runs on any operating system
### How-To-Use
After downloading and extracting the repository open it in jupyter notebook.Then open the `housingprice_predictor.ipynb` file. In that file change the values of `house_properties` variable and then run all the cells. The price of the house  will be displayed as output of the last cell.

### Dataset
The dataset used in this project is from kaggle datasets.
It can be downloaded at <https://www.kaggle.com/puxama/bostoncsv>
### Technical-Details
##### Dataset Details
The dataset contains 15 attributes and 506 instances.
The column details are
Serial Number
crim
zn
indus
chas
nox
rm
age
dis
rad
tax
ptratio
black
lstat
medv
##### Files Organization
The project is implemented in python in Jupyter Notebook environment.It mainly contains two parts.The `housingprice_trainer.ipynb` is for training the data and the `housingprice_predictor.ipynb` is to load the trained data and to predict results.The `houseprice_model.sav` is the model that is saved.The `Boston.csv` is the file containing the dataset.
### Algorithm
The House Price Prediction is a regression (prediction) problem. The target variable of this dataset is a numeric value.
The algorithm used in this is `linear regression`.More details about this algorithm can be found at <https://en.wikipedia.org/wiki/Linear_regression>
### Lisence
This is a public repository and you can be used in research,commercial and non-commercial applications without any restrictions.

