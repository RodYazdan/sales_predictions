# Sales_predictions
Predicting sales of various items 

**Author**: 
Hirad Yazdankhah

### Business problem:

We are trying to identify relationships between the dales data for difffernt items sold in differnt sotres in this database.
Ultimately we wan to predict sales

### Data:
#### Data can include source and high-level description (e.g. # obs)
#### '/content/sales_predictions.csv'
####/---------------------------------------------------
#### The data information is given below :

#### RangeIndex: 8523 entries, 0 to 8522
####Data columns (total 12 columns):
####   Column                     Non-Null Count  Dtype  
#### ---  ------                     --------------  -----  
#### 0   Item_Identifier            8523 non-null   object 
#### 1   Item_Weight                7060 non-null   float64
#### 2   Item_Fat_Content           8523 non-null   object 
#### 3   Item_Visibility            8523 non-null   float64
#### 4   Item_Type                  8523 non-null   object 
#### 5   Item_MRP                   8523 non-null   float64
#### 6   Outlet_Identifier          8523 non-null   object 
#### 7   Outlet_Establishment_Year  8523 non-null   int64  
#### 8   Outlet_Size                6113 non-null   object 
#### 9   Outlet_Location_Type       8523 non-null   object 
#### 10  Outlet_Type                8523 non-null   object 
#### 11  Item_Outlet_Sales          8523 non-null   float64

## Methods
- Data preparation steps:
We eliminate dulplicates and got rid of cells with Nulls.
W also deleted Outlet Size
We fixed inconsistencies in data to make all the tages the same.
## Results

#### Histogram of Number of Items Sold vs. Type of Of item Sold

![Histogram](https://github.com/RodYazdan/sales_predictions/blob/master/Images/Histogram%20of%20Numner%20of%20items%20sold.png))




### Heatmap of the correlation between features.
![Correlations](https://github.com/RodYazdan/sales_predictions/blob/master/Images/Correlations.png)


> The pictures above show the distribution of the data and the correlation between the differnt data columns

#### Visual 2 Title

## Model

We decided to go with a Random forrest model 

Report the most important metrics
#R2 SCORES
#Model Training R2: 0.9459499007697441
#Model Testing R2: 0.5581937612210199

#RMSC SCORES
#Model Training RMSE: 430.90539327118023
#Model Testing RMSE: 1127.941831980576

Refer to the metrics to describe how well the model would solve the business problem

The model is nto doing a great job at fitting the testing data but is doing a good job at training sata. This may indicate over fitting of data.

## Recommendations:

More of your own text here


## Limitations & Next Steps

Further analysis is requred to tune the data 


### For further information


For any additional questions, please contact Rod at email : ibluetouch@gmail.com
