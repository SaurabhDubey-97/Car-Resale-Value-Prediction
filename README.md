# Car-Resale-Value-Prediction
End to End Machine learning project with ML model build and deployed on Heroku cloud Platform.
Problem - To predict car's resale value on certain paramters related to the car mentioned in the dataset.

Solution :

1) For the problem in hand, its a typical regression problem.
2)  For feature Engineering used heatmaps and correlation to understand the underlying relation of features with each other, 
3) Using One Hot encoding for categorical Data of Fuel Type, which would help our model at training time.
4) Used Extra Tree Regressor method of Sklearn to know about feature importance, return type is matrix with score of relevancy
5) With the help of RandomizedSearchCV method of sklearn, hypertuned paramters to get best results for our Machine learning model, i.e Random Forest Regressor algorithm
6) Following project was done is a virtual enviroment with requirement.txt provided to help with installation on any local computer with all the libraries needed to run the program smoothly.
7) The program is being deployed on Heroku cloud platform.

The CSV Dataset provided
1) Car Name - Name of the car manufacturer and model name
2) Year of Purchase
3) Kms Driven - No. of Kilometers car has been driven 
4) fuel - Petrol/Diesel/CNG
5) seller_type - Individual/Dealer
6) transmission - Automatic/Manual
7) Owner - 1/2/3 or more
