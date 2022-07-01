# Sales_predictions
Predicting sales of various items 

**Author**: 
Hirad Yazdankhah

### Business problem:

We are trying to identify relationships between the dales data for difffernt items sold in differnt sotres in this database.
Ultimately we wan to predict sales

### Data:
Data can include source and high-level description (e.g. # obs)
'/content/sales_predictions.csv'
/---------------------------------------------------
The data information is given below :
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 8523 entries, 0 to 8522
Data columns (total 12 columns):
 #   Column                     Non-Null Count  Dtype  
---  ------                     --------------  -----  
 0   Item_Identifier            8523 non-null   object 
 1   Item_Weight                7060 non-null   float64
 2   Item_Fat_Content           8523 non-null   object 
 3   Item_Visibility            8523 non-null   float64
 4   Item_Type                  8523 non-null   object 
 5   Item_MRP                   8523 non-null   float64
 6   Outlet_Identifier          8523 non-null   object 
 7   Outlet_Establishment_Year  8523 non-null   int64  
 8   Outlet_Size                6113 non-null   object 
 9   Outlet_Location_Type       8523 non-null   object 
 10  Outlet_Type                8523 non-null   object 
 11  Item_Outlet_Sales          8523 non-null   float64
dtypes: float64(4), int64(1), object(7)
memory usage: 799.2+ KB


## Methods
- Data preparation steps:
We eliminate dulplicates and got rid of cells with Nulls.
W also deleted Outlet Size
We fixed inconsistencies in data to make all the tages the same.
## Results

#### Visual 1 Title
![sample image](project1_sample_image.png)

![Histogram of Number of Items Sold vs. Type of Of item Sold] (https://github.com/RodYazdan/sales_predictions/blob/master/Images/Histogram%20of%20Numner%20of%20items%20sold.png)

![Screen Shot 2022-06-30 at 2 41 30 PM](https://user-images.githubusercontent.com/67288119/176753994-687bd194-74df-4ffe-ac8e-c0466f1be9fc.png)

> Sentence about visualization.

#### Visual 2 Title

## Model

Describe your final model

Report the most important metrics

Refer to the metrics to describe how well the model would solve the business problem

## Recommendations:

More of your own text here


## Limitations & Next Steps

More of your own text here


### For further information


For any additional questions, please contact **email**
