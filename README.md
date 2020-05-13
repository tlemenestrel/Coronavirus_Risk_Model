![Image of a scraper](https://github.com/tlemenestrel/Coronavirus_Risk_Model/blob/master/Images/coronavirus.jpg)

# Coronavirus_Cases_Prediction

This project is a Machine Learning model to predict real estate prices of properties across France. It is a supervised regression task. The model used for this project is XGBoost.

## Dataset

The dataset contains the data of 350+ real-estate properties across France. The features are:

* the city where the property is located (Aix-En-Provence, Vincennes, Toulouse, Paris, Marseille, Manosque, Lyon, Issy-Les-Moulineaux, Gif Sur Yvette, Enghien Les Bains or Bourg La Reine)

* the region (Paca, Ile de France or Sud Ouest)

* the type (F1, F2, F3, F4, F5, F6, F7)

* the area in square metres 

* the rent per year in €  

* the price of the property in €

## Features importance

![Image of features importance](https://github.com/tlemenestrel/Coronavirus_Risk_Model/blob/master/Images/xgboost_features_importance.png)

For this dataset, the two most dominant features are clearly the annual rent and the area of the property, which is expected for a regression model on real estate prices. The other features help to fine-tune the accuracy of the model.

## How to download a copy of the project

To download a copy of the project, just go on the main page of the project on GitHub, click on **"Clone or download"** and then **"Download ZIP"**. 

After this, you should be able to run the project using Jupyter Notebook.

## Libraries to install

* [Jupyter Notebook](https://jupyter.org/install)
* [pandas](https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html)
* [numPy](https://numpy.org)
* [Seaborn](https://pypi.org/project/seaborn/)
* [Matplotlib](https://matplotlib.org/users/installing.html)
* [scikit-learn](https://scikit-learn.org/stable/install.html)
* [XGBoost](https://xgboost.readthedocs.io/en/latest/build.html)
* [graphviz](https://pypi.org/project/graphviz/)

## Author

* **Thomas Le Menestrel** 

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/tlemenestrel/Coronavirus_Risk_Model/blob/master/LICENSE) file for details
