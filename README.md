<!---- London Bike Sharing Problem ---->
<h3 align="center"> London Bike Sharing Problem <hr></h3>


![23qtg3hvggm0gux8nu0v](https://2.bp.blogspot.com/-lpnFCLuWr6w/UhiPO9cT1UI/AAAAAAAAFp8/R-hJ5UEq_Sc/s1600/Evolution-of-Bicycle.jpg)


<!---- Abstract: ---->
<h3 align="center"> Abstract: <hr></h3>

The purpose of this research is to try a machine learning approach for predicting bike sharing demand in London by given the hour, day, and information about the weather. 

The research contains: Data exploration, feature engineering, choosing appropriate scoring metric, cross algorithms, cross validation, tuning the algorithms,analysis of feature importance, analysis of residuals and performance evaluation. 

The used dataset is from years 2015 and 2016. With XGBoost the lowest RMSLE achieved on test set is 0.2611. 


<!---- Problem Statement ---->
<h3 align="center"> Problem Statement <hr></h3>

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. 

Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. 

This bike can then be returned to another dock belonging to the same system.


<!---- Explore the Data ---->
<h3 align="center"> Explore the Data <hr></h3>

The first step in any machine learning project is to explore the data that you will use to train a model. 

The goal of this exploration is to try to understand the relationships between its attributes; in particular, any apparent correlation between the features and the label your model will try to predict. 

This may require some work to detect and fix issues in the data (such as dealing with missing values, errors, or outlier values), deriving new feature columns by transforming or combining existing features (a process known as feature engineering), normalizing numeric features (values you can measure or count) so they're on a similar scale, and encoding categorical features (values that represent discrete categories) as numeric indicators
