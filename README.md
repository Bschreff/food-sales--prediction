

# Big Mart Sales-Prediction

## Predicting and Analyzing Sales of store items.
Brian Schreffler

### Trying to help Big Mart predict what items people spend the most money on and what items are the most expensive.

## Data Source:
Big Mart Sales Predictions
https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/

For this dataset, there were 8523 rows and 12 columns.

## Explanatory Data Analysis
  -  To visualize the data for explantory purposes, two barplots were chosen to look at Item MRP Item Outlet Sales.
  -  The bargraphs were chosen to show how the categories compare to each other. 
     
        
## Explanatory Visuals

![Unknown](https://user-images.githubusercontent.com/116525770/216511628-534a0ada-6c6d-42ae-a14b-76e622b9d113.png)

![Unknown](https://user-images.githubusercontent.com/116525770/216987057-059fdf54-524a-4d6f-b76c-40b01aa48419.png)

## Linear Regression Coefficients
<img src="Top_3.png" alt="Alternative text" />
The top two importances are the same as in SHAP but the third is different outlet type tier 3 is the third in SHAP where as in impotances outlet size medium is third.


## Random Forest Regression Coefficients
<img src="Top_5.png" alt="Alternative text" />
The Top five are very different in SHAP.


## Shap Summary
<img src="images/summary_plot_1.png" width=400px>
The Item MRP influences the prediction of outlet sales being higher, outlet type grocery shows an influence on item outlet sales to be lower, and supermarket type 3 shows influences the prediction to be higher.
## Model Evaluated & Results
Tuned Bagged Tree Model Test Scores
   - MAE: 1425819.3488 
   - MSE: 1425819.3488 
   - RMSE: 1194.0768, 
   - R2: 0.4832073

Tuned Random Forest Model Test Scores
   - MAE: 1100093.219 
   - MSE: 1100093.219 
   - RMSE: 1048.8533, 
   - R2: 0.6012678

Best Fit Decision Tree Test Scores
   - MAE: 1118185.9731 
   - MSE: 1118185.9731 
   - RMSE: 1057.4431, 
   - R2: 0.59471

## Limitations and next steps
The final model chosen was the Random Forest it performed the best on the testing data. it would not perform well on the cost of a car or a house. The model needs tuned more to perform better or try some other metrics to get a better predictions.

## Recomendations
My recomendations to Big Mart would be to focus sales on the items that people seem to be spending the bulk of their money on and more visability.

## For further questions or insights
Please contact:
Brian Schreffler
brianschreffler1105@gmail.com
