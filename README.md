# HousePrice
**********************************************************
Description
*************************************
Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.
**************************************
First import all the requerd 
*************************************
EDA
*****************************
Handling_Missing_values
************************************
Feature having missing values
mean() of missing values using for loop
************************************
We plotting bargraph to find relationship between missing values and SalePrice
*****************************************
Handling catagorical values and numerical values
****************************************
Skewness:
Since the data_continuous has skewness, we have to convert it into logarithmic
**************************************
Converting Categorical value into Numerical Value
****************************************
Feature Selection
******************************************
first, I specify the Lasso Regression model, and I
select a suitable alpha (equivalent of penalty).
The bigger the alpha the less features that will be selected.

Then I use the selectFromModel object from sklearn, which
will select the features which coefficients are non-zero
*******************************************
preforming Feature_scaling
