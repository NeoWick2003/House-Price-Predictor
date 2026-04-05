# House-Price-Predictor
Created a ML project ( R-sqaured ~ 0.71) which can predict house prices across 50+ locations in India, from 180+ listings. 
Also, created an interactive website for putting in various details and criteria. Currently, working on reducing the response time of the website (takes time due to the use of huge data set). 

- Used and compared linear regression and random forest models.
- Random forest showed better performance: MAE reduced by 63% and RMSE by 56%
- Used the following features: location, price (in INR), carpet area, transaction, furnish level, overlooking, bathroom, balcony, ownership, BHKs and floors
- Implemented floor ratio (i.e., designated floor/total no. of floors). Accounts in relatability for the same floor (e.g. differentiates 3/5 floor from 3/11 floor).
