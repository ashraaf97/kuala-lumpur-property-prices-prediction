# Kuala Lumpur Property Price Prediction

This project is made as requirement for the  Data Mining Subject with my friends. THe main objective is to try demostrate the regression model that we learned in the class. We also tried sequential model to see the result.

This project is about predicting property (including houses) prices using the data scapped from iproperty.com.my. The website is the marketplace to for property's business. Special Thanks to Jan S, Data Scientist in Kaggle for his data on property prices in Kuala Lumpur that are scrapped from website iProperty.

### Data requirements:
Download .csv from: https://www.kaggle.com/dragonduck/property-listings-in-kuala-lumpur

### Softaware and Libraries:

* Python
* NumPy
* pandas
* matplotlib
* scikit-learn
* seaborn
* matplotlib
* keras
* statsmodels
* BeautifulSoup

This prediction can be done either in cloud based notebook or local notebook. Recommended cloud based notebook is Google Colab. Recommended for local is Jupyter Notebook. For local make sure all required libraries is installed and the evironement is property set up.

The results for the price prediction is not reliable.The R-Squared value gained is 0.67(price) and 0.51(price per area) for the linear regression model.The result using Sequential model is even worst which are 0.39(price) and 0.55(price per are). If only prices and size num are considered we still only get 0.63. The reason for this is the data itself. The data scapped for this project is not enough to gives good results for the model. However the steps and procesures used are very good enough for future improvement. 

Further steps and codes for the prediction please go to : https://github.com/ashraaf97/kuala-lumpur-property-prices-prediction/blob/master/DataMiningProject.ipynb
