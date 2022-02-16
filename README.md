
# Real Estate Price Prediction 
In this project I develop the model which predict the price of house 
on some features. There are 14 different features releted house I collected as a data. 

Features :-     

    1. CRIM      per capita crime rate by town  
    2. ZN        proportion of residential land zoned for lots over 
                 25,000 sq.ft.  
    3. INDUS     proportion of non-retail business acres per town   
    4. CHAS      Charles River dummy variable (= 1 if tract bounds 
                 river; 0 otherwise)    
    5. NOX       nitric oxides concentration (parts per 10 million)
    6. RM        average number of rooms per dwelling   
    7. AGE       proportion of owner-occupied units built prior to 1940 
    8. DIS       weighted distances to five Boston employment centres   
    9. RAD       index of accessibility to radial highways  
    10. TAX      full-value property-tax rate per $10,000   
    11. PTRATIO  pupil-teacher ratio by town    
    12. B        1000(Bk - 0.63)^2 where Bk is the proportion of blacks 
                 by town    
    13. LSTAT    % lower status of the population       
    14. MEDV     Median value of owner-occupied homes in $1000's    

Libraries Used in project :-    
* Pandas
* Numpy
* Scikit-learn
* Matplot lib
* joblib        

Import .csv file in jupyter notebook and first perform some Pandas library
function on that data to maka perfect. we can get deep details about 
our data using .info() function.    

With the help of numpy i got the mathimatical details of data 
which is helpfull further. i got count, min, max, standard deviation
etc details of data. i used random function to arrange data randomly
. i make the different histograms for analyse the data.

Then i split the data into train set and test set with the help
of sklearn.model_selection. i use train_test_split for spliting
data. Now check the correlation of functions and make the plots
of some relevent features. According plots trying out features 
combinations.   

After find the missing values of the data Create the pipeline.
Then Select the desired model for the data using sklearn library -   

    from sklearn.linear_model import LinearRegression
    from sklearn.tree import DecisionTreeRegressor
    from sklearn.ensemble import RandomForestRegressor
***
Then evaluating the model and find the mean squared error for 
accuracy of model prediction. At last i saved the project 
using joblib library.   

Models Outputs :-

1.Decision Tree :-

    Mean: 4.016918348306055
    Standard deviation: 0.5935280276680469
    
    
2.Linear Regression :-

    Mean: 4.221897658745642
    Standard deviation: 0.752369553214521
    

3.Random Forest Regression :-

    Mean: 3.096923480250687
    Standard deviation: 0.8690871865922318
