# Analysis and predicting booking value and booking probability for cruise ship data


# Data Description!

The data set is from a cruise ship **Booking!** company with around 20000 rows. In total it has 7 columns including **booking_probability** and **booking_value** .  I predicted booking_value(regression problem) and booking_probability(classification problem). 

![data_set_sample](/lead.png)


# Data Cleaning
There are lot of ways to clean the data and this is one of the most important task before feeding the data to machine learning or neural net work.

Some possible way to clean the data...
- drop nan or NaN or any other missing values
- use Imputer using scikit or any other library
- predict missing values using regression models like (Linear/Multiple Regression), Decision Tress or Random forest


I tried to predict the missing value using Regression models. i used Kernel Ridge regression model to predict Nan or missing values. You can use whatever model you want based on performacne.

# Problem i have solved

- Predict booking value ?
- Predict booking probability?
- Find the most impact factor variables?
- Some descriptive analysis of the datset?
- Any relation between two models to sort out ultimate prediction of booking (tough one)!!!


## Algorithm Used

- Gradient Boosting and Radom Forest for regressiong task (**booking_value**)
- Linear Support Vector Classifier and Random Forest Calssifier for the classification(**binary**) task. 
