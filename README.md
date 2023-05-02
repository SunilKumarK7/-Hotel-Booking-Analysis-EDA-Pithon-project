# -Hotel-Booking-Analysis-EDA-Python-project
This project analyzes hotel booking data consisting of two hotel types - City Hotel and Resort Hotel. The dataset contains 119,390 rows and 32 columns, and the data manipulation workflow is divided into three categories: Data Collection, Data Cleaning and Manipulation, and EDA (Exploratory Data Analysis).

In the Data Collection phase, various methods such as head(), tail(), info(), describe(), columns() were used to find different columns in the dataset. Key columns such as hotel, is_canceled, lead_time, arrival_date_year, arrival_date_month, arrival_date_week_number, and arrival_date_day_of_month were identified.

Next, the unique values of each column were found and presented in a tabular form. The dataset was checked for accurate data types, and columns with incorrect data types were corrected during the Data Cleaning and Manipulation phase. Duplicate data items were also removed, as there were 87,396 duplicate items in the dataset.

Before visualizing the data, data wrangling was performed. Null values in columns were checked, and columns with a significant number of null values were dropped using the 'drop' method. For columns with minimal null values, missing values were filled in as necessary using the .fillna() method.

Different charts were used for data visualization to gain better insights and achieve business objectives.
