<img src="http://imgur.com/1ZcRyrc.png" style="float: left; margin: 20px; height: 55px">

# Project 2: Ames Housing Data and Kaggle Challenge

## Background

Real Sky Estate Development has been developing residential areas around Ames and is looking to procure and develop new housing in the area. 

Previous housing developments were not returning favourable profits due to the recent pandemic and political tensions, which lead to the rise in the costs of living and building materials over the years.

Facing a forecasted recession in the upcoming year, Real Sky senior management team has reached out to our data science team to pinpoint factors that will be directed towards revamping the company’s focus structure to improve the attractiveness and sales price of new housing developments.

## Problem Statement

What are the core features to focus on, so as to increase the sale price of homes for the next development project.

## Data Dictionary:

**Dataset name: train_final8**

#### Size: 2025 observations, 15 variables
#### Description: Final dataset that contains features for model training.

|Feature|Type|DataType|Dataset|Description|
|---|---|---|---|---|
|**overall_qual**|*integer*|Ordinal|train_final8|Overall material and finish of the house rating| 
|**c_total_area**|*float*|Continuous|train_final8|Total above ground living area + basement area in square feet|
|**garage_area**|*float*|Continuous|train_final8|Size of garage in square feet| 
|**c_tot_exter**|*integer*|Ordinal|train_final8|Total exterior material quality and condition|
|**c_total_bath**|*float*|Discrete|train_final8|Total above grade full bathrooms and half bathrooms in the house| 
|**year_built**|*integer*|Discrete|train_final8|Original construction date|
|**c_tot_bsmt**|*integer*|Ordinal|train_final8|Total basement quality, condition and exposure|
|**c_ord_garage_finish**|*integer*|Ordinal|train_final8|Interior finish of the garage|
|**c_ord_fireplace_qu**|*integer*|Ordinal|train_final8|Fireplace quality|
|**mas_vnr_area**|*float*|Continuous|train_final8|Masonry veneer area in square feet|
|**c_ord_heating_qc**|*integer*|Ordinal|train_final8|Heating quality and condition|
|**neighborhood_NridgHt**|*float*|Categorical|train_final8|Northridge Heights|
|**bsmtfin_sf_1**|*float*|Continuous|train_final8|Type 1 finished square feet|
|**c_total_porch_area**|*integer*|Continuous|train_final8|Total wood deck, open porch, enclosed, three season porch, screen porch area in square feet|
|**saleprice**|*integer*|Continuous|train_final8|Sale price of house|


**Dataset name: train**

#### Size: 2930 observations, 82 variables
#### Description: Data set contains information from the Ames Assessor’s Office used in computing assessed values for individual residential properties sold in Ames, IA from 2006 to 2010.

| Feature | Type | Dataset | Description |
|:--|:-:|:-:|:--|
|Id|int|Train|Identification number.|
|PID|int|Train|Parcel identification number.|
|MS SubClass|int|Train|The building class.|
|MS Zoning|string|Train|Identifies the general zoning classification of the sale.|
|Lot Frontage|float|Train|Linear feet of street connected to property.|
|Lot Area|int|Train|Lot size in square feet.|
|Street|string|Train|Type of road access to property.|
|Alley|string|Train|Type of alley access to property.|
|Lot Shape|string|Train|General shape of property.|
|Land Contour|string|Train|Flatness of the property.|
|Utilities|string|Train|Type of utilities available.|
|Lot Config|string|Train|Lot configuration.|
|Land Slope|string|Train|Slope of property.|
|Neighborhood|string|Train|Physical locations within Ames city limits.|
|Condition 1|string|Train|Proximity to main road or railroad.|
|Condition 2|string|Train|Proximity to main road or railroad (if a second is present)|
|Bldg Type|string|Train|Type of dwelling.|
|House Style|string|Train|Style of dwelling.|
|Overall Qual|int|Train|Overall material and finish quality.|
|Overall Cond|int|Train|Overall condition rating.|
|Year Built|int|Train|Original construction date.|
|Year Remod/Add|int|Train|Remodel date (same as construction date if no remodeling or additions).|
|Roof Style|string|Train|Type of roof.|
|Roof Matl|string|Train|Roof material.|
|Exterior 1st|string|Train|Exterior covering on house.|
|Exterior 2nd|string|Train|Exterior covering on house (if more than one material).|
|Mas VnrType|string|Train|Masonry veneer type.|
|Mas Vnr Area|float|Train|Masonry veneer area in square feet.|
|Exter Qual|string|Train|Exterior material quality.|
|Exter Cond|string|Train|Present condition of the material on the exterior.|
|Foundation|string|Train|Type of foundation.|
|Bsmt Qual|string|Train|Height of the basement.|
|Bsmt Cond|string|Train|General condition of the basement.|
|Bsmt Exposure|string|Train|Walkout or garden level basement walls.|
|Bsmtfin Type 1|string|Train|Quality of basement finished area.|
|Bsmtfin SF 1|float|Train|Type 1 finished square feet.|
|Bsmtfin Type2|string|Train|Quality of second finished area (if present).|
|Bsmtfin SF 2|float|Train|Type 2 finished square feet.|
|Bsmt Unf SF|float|Train|Unfinished square feet of basement area.|
|Total Bsmt SF|float|Train|Total square feet of basement area.|
|Heating|string|Train|Type of heating.|
|Heating QC|string|Train|Heating quality and condition.|
|Central Air|string|Train|Central air conditioning.|
|Electrical|string|Train|Electrical system.|
|1st Flr SF|int|Train|First Floor square feet.|
|2nd Flr SF|int|Train|Second floor square feet.|
|Low Qual Fin SF|int|Train|Low quality finished square feet (all floors).|
|GR Liv Area|int|Train|Above grade (ground) living area square feet.|
|Bsmt Full Bath|float|Train|Basement full bathrooms.|
|Bsmt Half Bath|float|Train|Basement half bathrooms.|
|Full Bath|int|Train|Full bathrooms above grade.|
|Half Bath|int|Train|Half baths above grade.|
|Bedroom AbvGr|int|Train|Number of bedrooms above basement level.|
|Kitchen AbvGr|int|Train|Number of kitchens.|
|Kitchen Qual|string|Train|Kitchen quality.|
|TotRms AbvGrd|int|Train|Total rooms above grade (does not include bathrooms).|
|Functional|string|Train|Home functionality rating.|
|Fireplaces|int|Train|Number of fireplaces.|
|Fireplace Qu|string|Train|Fireplace quality.|
|Garage Type|string|Train|Garage location.|
|Garage Yr Blt|float|Train|Year garage was built.|
|Garage Finish|string|Train|Interior finish of the garage.|
|Garage Cars|float|Train|Size of garage in car capacity.|
|Garage Area|float|Train|Size of garage in square feet.|
|Garage Qual|string|Train|Garage quality.|
|Garage Cond|string|Train|Garage condition.|
|Paved Drive|string|Train|Paved driveway.|
|Wood Deck SF|int|Train|Wood deck area in square feet.|
|Open Porch SF|int|Train|Open porch area in square feet.|
|Enclosed Porch|int|Train|Enclosed porch area in square feet.|
|3Ssn Porch|int|Train|Three season porch area in square feet.|
|Screen Porch|int|Train|Screen porch area in square feet.|
|Pool Area|int|Train|Pool area in square feet.|
|Pool QC|string|Train|Pool quality.|
|Fence|string|Train|Fence quality.|
|Misc Feature|string|Train|Miscellaneous feature not covered in other categories.|
|Misc Val|int|Train|$Value of miscellaneous feature.|
|Mo Sold|int|Train|Month Sold.|
|Yr Sold|int|Train|Year Sold.|
|Sale Type|string|Train|Type of sale.|
|SalePrice|int|Train|The property's sale price in dollars.|

## Conclusion:

- With an observed linear correlation between features and sale price from EDA and feature selection, it is possible to apply regression modelling techniques.
- Features for modelling, were selected through the use of pearson correlation to determine the pairwise correlation of the features in the dataset to sale price. The selected feature had at least > 0.4 correlation coefficient values, and are generally positively correlated to sale price.
- The features used includes overall_qual, c_total_area, garage_area, c_tot_exter, c_total_bath, year_built, c_tot_bsmt, c_ord_garage_finish, c_ord_fireplace_qu, mas_vnr_area, c_ord_heating_qc, neighborhood_NridgHt, bsmtfin_sf_1, c_total_porch_area.
- The model that was best at predicting sale price was Linear Regression model. With the application of polynomial feature engineering method, the resulting R-square value improved from its previous test value of ~82% to 86%, with Linear Regression model having the best R2 and RMSE values in comparison to Lasso and Ridge models.
- Using the variable importance plot, it is observed that the top 3 features with greatest contributions to sale price are c_ord_heating_qc, overall_qual, c_ord_fireplace_qu.
- Looking further at the model's accuracy, based on the prediction plot for the Linear Regression model, it can be observed that sale price predictions for y_test values within the range of 0 to 300,000 is able to maintain a residual score of within +/- 50,000, however for y_test values greater than 300,000, the observed predicted sale price is observed to have higher deviations from actual y_test values. This shows the limitations of the model at higher sale price values, and can be attributed to the limited data in the dataframe for sale price values of more than 300,000 USD.

## Recommendations:

- Observed that the top 3 features with greatest contributions to sale price are the heating quality and condition (c_ord_heating_qc), overall material and finish of the house (overall_qual), fireplace quality (c_ord_fireplace_qu), ]
- More budget can be allocated to prioritization of these core features, to improve the attractiveness of the new housing developments to potential buyers.
- More marketing efforts can also be channeled to advertise these features.

## Moving Forward:

- To include data from more recent years, as dataset used were housing sale prices from 2006 to 2010.
- To have more clarity and description for ordinal features, for example what does an Excellent grade for fireplace quality mean and account for. 