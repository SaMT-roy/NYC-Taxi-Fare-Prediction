# NYC-Taxi-Fare-Prediction


This was a Kaggle challenge. In this contest, the aim is to predict the fare of a taxi ride given the starting time, the starting and ending latitude / longitude, and the number of passengers. This is a supervised regression machine learning task.

![image](https://user-images.githubusercontent.com/82521644/152027948-a981c46d-e05a-4cbb-b381-c488db6e9c43.png)


![image](https://user-images.githubusercontent.com/82521644/152028668-08b0cfdc-0e74-485b-9f62-3257e9b281c5.png)

![image](https://user-images.githubusercontent.com/82521644/152028747-7c3ebca9-d7a7-4cac-ba36-c1ec8e19c52b.png)


The above graphs helped to remove outliers.


Manhattan and Euclidean Distance 

The Minkowski Distance between two points is expressed as: ![image](https://user-images.githubusercontent.com/82521644/152028986-630a5551-8b9a-45f8-8d34-c0bbc40c9078.png)


if p = 1, then this is the Manhattan distance and if p = 2 this is the Euclidean distance. You may also see these referred to as the l1 or l2 norm where the number indicates p in the equation.

![image](https://user-images.githubusercontent.com/82521644/152028117-28c25ce7-dfef-4c2a-8f7e-f378d70963fd.png)


I  used the Random Forest regressor. This is a powerful ensemble of regression trees that has good performance and generalization ability because of its low variance.

It performed well when  compared  to linear regression model and simple general mean model.

Random Forest Regressor :   Training:    rmse = 1.64 	   mape = 15.06
                            
                            Validation:  rmse = 1.8 	   mape = 15.82
                                     
