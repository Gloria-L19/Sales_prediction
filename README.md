# Sales_prediction
## The project is about designing the model that predicts the sales of food at different stores using different parameters. 

**Author**: LAMUNU GLORIA

### Business problem:
To predict the item_outlet_sales based on the different data collected from the stores


### Data:
Item_Outlet_Sales, Item_Weight, Item_Fat_Content, Item_Visibility, Item_Type, Item_MRP, Outlet_Identifier, Outlet_Establishment_Year,
Outlet_Size, Outlet_Location_Type, Outlet_Type, Item_Outlet_Sales


## Methods
- Importing libraries and loaded the data
- Exploring the data, using data visualization like heatmaps: to identify the correlation between different columns, histograms and boxplots to compare data
- Ordinal Encoding the data becasue Item_Fat_Content,Outlet_Location_Type,Outlet_Size is ordinal
- Performing train_test_splitting the data. The X is the feature matrix and is represented by the Item_Outlet_Sales. For the target 'y', the columns Item_Identifier, Item_Visibility,Outlet_Identifier,Item_Outlet_Sales were dropped
- Instantiating column selectors for numerical data and categorical data because some data was of the object type and the rest numerical
- Instantiating transformers StandardScaler and One Hot Encoder . One hot encoding is done because the column Item_Type is norminal
- Instantiating pipelines for numerical data and categorical data
- Fitting data on a preprocessor
- Instantiating the linear regression model  and evaluating the model with R^2 score and Root Mean Squared Error
- Instantiating the DecisionTreeRegression model and evaluating the model with R^2 score and Root Mean Squared Error
- Fine tuning the DecesionTreeRegression using the different depths and finding the depth that provides the highest R^2 score

## Results

### Here are examples of how to embed images from your sub-folder


#### Visual 1 Title
![sample image](https://drive.google.com/file/d/11Cs0nf2pok7ooiJO8iGggrwpQpw63DdG/view?usp=share_link)

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
