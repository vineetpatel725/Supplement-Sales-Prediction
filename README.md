# Supplement Sales Prediction
Forecast sales for 350+ supplement retail chain stores for next 2 months.


## Description
Your Client WOMart is a leading nutrition and supplement retail chain that offers a comprehensive range of products for all your wellness and fitness needs.

WOMart follows a multi-channel distribution strategy with 350+ retail stores spread across 100+ cities.

Effective forecasting for store sales gives essential insight into upcoming cash flow, meaning WOMart can more accurately plan the cashflow at the store level.

Sales data for 18 months from 365 stores of WOMart is available along with information on Store Type, Location Type for each store, Region Code for every store, Discount provided by the store on every day, Number of Orders everyday etc. Your task is to predict the store sales for each store in the test set for the next two months. Data Dictionary Train Data Variable Definition ID Unique Identifier for a row Store_id Unique id for each Store Store_Type Type of the Store Location_Type Type of the location where Store is located Region_Code Code of the Region where Store is located Date Information about the Date Holiday If there is holiday on the given Date, 1 : Yes, 0 : No Discount If discount is offered by store on the given Date, Yes/ No #Orders Number of Orders received by the Store on the given Day Sales Total Sale for the Store on the given Day

Test Data Variable Definition ID Unique Identifier for a row Store_id Unique id for each Store Store_Type Type of the Store Location_Type Type of the location where Store is located Region_Code Code of the Region where Store is located Date Information about the Date Holiday If there is holiday on the given Date, 1 : Yes, 0 : No Discount If discount is offered by store on the given Date, Yes/ No.


## Algorithm
**I have created this project in different algorithms. The accuracy of the project varies according to the algorithm. Below, are the listed algorithms that i have used in the project. Among them the XGboost have the highest accuracy which is _82.57%._**

> - XGBoost
> - Random Forest
> - Extra Tree
> - Decision Tree
> - K-NN
> - Linear Regression

## Directory Structure

    ├── Supplement Sales Prediction
    │   ├── Supplement Sales Prediction.ipynb         # Prediction .ipynb file
    │   ├── TEST_FINAL.csv                            # Dataset for Test
    │   └── TRAIN.csv                                 # Dataset for Train
