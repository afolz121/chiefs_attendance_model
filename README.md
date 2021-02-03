# chiefs_attendance_model

The goal of this project is to create a machine learning model to accurately predict A Kansas City Chiefs home game using 
data frame https://pro-football-reference.com.

The first file is chiefs_data_scrape. This is a method for scraping pro-football-reference to get statistics and attendance
data for the number of years you are looking to use.

Initial modeling has been complete. Lasso Lars and Ridge regression gave some slight lift when using the RMSE of attendence to the average attendance in the dataset. 

Next, I want to try some neural networks with tensorflow to see if I can increase R^2 compared to the lasso and ridge models. 



