# House prices : advanced regression challenge
Housing price regression [challenge on Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques).
Given a dataset of a subset of the house with known prices predict new house prices based on a set of features.

## Credits
* Yannick Giovanakis ([@yangvnks](https://github.com/yangvnks))


## Method
Below are provided the steps that were followed for this project. Each step and classifiers have their own document.

1. **Data visualisation & Preprocessing**: with the knowledge acquired with the preceding step, apply preprocessing of data including dealing with missing values, drop unuseful features and build new features
2. **Regression**: use regression techniques based on the preprocessed data using a variety of algorithms

## Regression techniques
Regression techniques together with the relative scores (RMSE)

| Regressor | CV score | Kaggle score |
| ------ |:------:|:------:|
| *ENet* | 0.10811 | 0.11926|
| *GBoost* | 0.10882 | 0.12412 |
| *XGB* | 0.11041 | 0.12188 |
| *KRR* | 0.11202 | - |
| *Ensemble*| 0.1051 | 0.11765 |


## Folder structures
* `\` contains all of the jupyter's notebooks including classifiers, preprocessing and data visualization
* `\Data` contains the project dataset given in the Kaggle challenge
* `\Data\outputs` contains the outputs given by the classifiers that were submitted to Kaggle



To run the [jupyter](http://jupyter.org/)'s notebooks just go with `jupyter notebook`
