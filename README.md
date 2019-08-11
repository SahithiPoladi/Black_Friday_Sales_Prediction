# Black_Friday_Sales_Prediction
Dataset columns: 12
USER_ID, Product_ID, Gender, Age, Occupation, City_Category, Stay_In_Current_City_Years, Martial_Status, Product_Category_1, Product_Category_2, Product_Category_3, Purchase

Technologies: Python 3.5 with Spark

Libraries: tensorflow, py4j, pixiedust, plotly, cufflinks

Considered a dataset of 25MB size and performed predictions on few columns.
By removing null values from dataset I have splitted the data into trained, tested and predicted data records.
Taking City_Category as a primary label, performed data classification.
Afetr the trained data is fit in a pipeline, I found the accuracy of data.
The train data is retrieved from pipeline and predictions are performed on GENDER, MARTIAL_STATUS, PURCHASE, AGE and displayed them in pie chart.
