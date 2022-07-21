# project_hotelbooking

collect data form csv file 

import pandas as pd
import numpy as np
from google.colab import drive 
drive.mount('/content/drive')
hb=pd.read_csv('/content/drive/MyDrive/DS/PROJECT/HOTEL BOOKING/Copy of Hotel Bookings.csv')
clearing the data 
remving the null values
