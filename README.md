# COVID-19_time_series_data
In this repository we are analyzing the spread of the novel coronavirus, also known as SARS-CoV-2.
Dataset used in this repository has been obtained from [*here*](https://github.com/CSSEGISandData/COVID-19) and it is being maitained by John Hopkins University for [*intrective dashboard*](https://www.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6) and other projects. Dataset is avialable in the **CSV** format.
Dataset is consist of total 4 files :
  1. Confirmed_df -> Contain data of the confirmed coronavirus cases.
  2. Deaths_df -> Contain data of the confirmed death due to coronavirus cases.
  3. Recoveries_df -> Contain data of the recovered cases.
  4. Latest_data -> Newely added data to the dataset. Updated on regular basis.

Dataset is read in  **pandas DataFrame**.
**sklearn** library is used for different machine learinig algorithem.


# Machine Learning Model


## SVM

Support-vector machines are supervised learning models with associated learning algorithms that analyze data used for classification and regression analysis.
SVM is used to predict the future trend of the coronavirus.

## Polynomial regression 

Polynomial regression is a form of regression analysis in which the relationship between the independent variable x and the dependent variable y is modelled as an nth degree polynomial in x. Polynomial regression fits a nonlinear relationship between the value of x and the corresponding conditional mean of y, denoted E.
Polynomial regression is used to predict the future of mortality rate, recovries and new confirmed cases. 
