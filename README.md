## Data Analysis and Visualisation to predict Car Prices based on Used Car Prices Data Set
In this project I'm trying to analyze and visualize the Used Car Prices from the dataset: https://archive.ics.uci.edu/ml/machine-learning-databases/autos/imports-85.data

It is divided into four parts:

1-**Data Wrangling**

- Pre processing data in python
- Dealing missing values
- Data formatting
- Data normalization
- Binning

**Exploratory Data Analysis**

- Descriptive statistics
- Groupby
- Analysis of variance
- Correlation
- Correlation stats

**Model Development**

- Simple Linear Regression
- Multiple Linear Regression

**Model Review and Evaluation**

- Regression Plots
- Distribution Plots

## Softwares and libearies used: ##
- Anaconda Distribution
- Jupiter Notebook
- pandas
- numpay
- seaborn
- scikit learn
- matplotlib
## Language Programing ##
- python
## Algorithms , functions and methods ##
- simple Linear regression
- multiple linear regression
- polynomial multiple linear regression
- Ridge regression
- GridSearchCV method
## Analysis ##

1. Histograms representing Binned prices in Low, Medium, High

![download (2)](https://user-images.githubusercontent.com/56628918/87134843-84adf800-c299-11ea-899d-ffdaa4599788.png)

2.boxplots shows minimum overlap between subcategories and this shows  engine-locatuin is a good predictor for price 

![2](https://user-images.githubusercontent.com/56628918/87138995-90042200-c29f-11ea-91e5-6c213d3f09d1.png)

3.boxplots shows  overlap between subcategories and this shows  body-style is not a good predictor for price 

![1](https://user-images.githubusercontent.com/56628918/87139315-13257800-c2a0-11ea-8abc-dbfa05e50bbe.png)

4. This regplot  shows negative correlation  between price and this feature

![1](https://user-images.githubusercontent.com/56628918/87139884-eb82df80-c2a0-11ea-83a3-e7c36f88f796.png)

5. This regplot  shows weak  negative correlation  between price and this feature

![2](https://user-images.githubusercontent.com/56628918/87140561-0144d480-c2a2-11ea-854e-b0cafeac6803.png)

6. This residual plot shows highway-mpg feature needs to  unlinear function for  getting fit data on it 

![3](https://user-images.githubusercontent.com/56628918/87140674-2fc2af80-c2a2-11ea-8b63-845cbfab1f9b.png)

7. Define a polynomial function order 3 on  this feaure.It shows the data is fitted better on this function

![1](https://user-images.githubusercontent.com/56628918/87141635-a1e7c400-c2a3-11ea-8cc5-75921aa00f59.png)

8. Distribution plot on multiple linear regression.It shows how model predicts seen data and how much is different with real data

![1](https://user-images.githubusercontent.com/56628918/87142093-51bd3180-c2a4-11ea-9b1a-6232975a9cce.png)

9. Distribution plot on multiple linear regression.It shows how model predicts unseen data and how much is different with real data.It shows overfitting

![1](https://user-images.githubusercontent.com/56628918/87142779-4fa7a280-c2a5-11ea-97ca-74b75b13c15d.png)

10. Estimated function(polynomial function with order 5 for single linear regression) is diverged around 200

![1](https://user-images.githubusercontent.com/56628918/87143302-2a676400-c2a6-11ea-996a-ccecb0a9e698.png)

11. Find best order for polynomial function(single linear regression).It shows 3 order is best order for model

![1](https://user-images.githubusercontent.com/56628918/87143578-a19cf800-c2a6-11ea-8a3d-44f613765791.png)

12. Estimated function(polynomial function with order 2 for multiple linear regression).It shows how model predicts unseen data and how much is different with real data.

![1](https://user-images.githubusercontent.com/56628918/87144011-62bb7200-c2a7-11ea-8a30-341c13b31113.png)



