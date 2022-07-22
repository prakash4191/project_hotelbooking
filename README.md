# project_hotelbooking

collect data form csv file 

import pandas as pd
import numpy as np
from google.colab import drive 
drive.mount('/content/drive')
hb=pd.read_csv('/content/drive/MyDrive/DS/PROJECT/HOTEL BOOKING/Copy of Hotel Bookings.csv')
clearing the data 
remving the null values


Understand the problem. We'll look at each variable and do a philosophical analysis about their meaning and importance for this problem. 2.Univariable study. We'll just focus on the dependent variable ('SalePrice') and try to know a little bit more about it.

3.Multivariate study. We'll try to understand how the dependent variable and independent variables relate.

4.Basic cleaning. We'll clean the dataset and handle the missing data, outliers and categorical variables.

5.Test assumptions. We'll check if our data meets the assumptions required by most multivariate techniques.

# Extracting infromation from 
hb.head(10)
