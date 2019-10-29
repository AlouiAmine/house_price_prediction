# house price prediction

22th March 2019

The first AML challenge for this year is adapted from the well-known 'Zillow's Home Value Prediction' competition on Kaggle. In particular, given a dataset containing descriptions of homes on the US property market, your task is to make predictions on the selling price of as-yet unlisted properties. Developing a model which accurately fits the available training data while also generalising to unseen data-points is a multi-faceted challenge that involves a mixture of data exploration, pre-processing, model selection, and performance evaluation.

# Overview

Beyond simply producing a well-performing model for making predictions, in this challenge we would like you to start developing your skills as a machine learning scientist. In this regard, your notebook should be structured in such a way as to explore the five following tasks that are expected to be carried out whenever undertaking such a project. The description below each aspect should serve as a guide for your work, but you are strongly encouraged to also explore alternative options and directions. Thinking outside the box will always be rewarded in these challenges.

# Dataset Description
* Files
- train.csv - The training dataset;
- test.csv - The test dataset;
- data_description.txt - Full description of each column.
* Attributes
A brief outline of the available attributes is given below:

* SalePrice: The property's sale price in dollars. This is the target variable that your model is intended to predict;
* MSSubClass: The building class;
* MSZoning: The general zoning classification;
* LotFrontage: Linear feet of street connected to property;
* LotArea: Lot size in square feet;
* Street: Type of road access;
* Alley: Type of alley access;
* LotShape: General shape of property;
* LandContour: Flatness of the property;
* Utilities: Type of utilities available;
* LotConfig: Lot configuration;
* LandSlope: Slope of property;
* Neighborhood: Physical locations within Ames city limits;
* Condition1: Proximity to main road or railroad;
* Condition2: Proximity to main road or railroad (if a second is present);
* BldgType: Type of dwelling;
* HouseStyle: Style of dwelling;
* OverallQual: Overall material and finish quality;
* OverallCond: Overall condition rating;
* YearBuilt: Original construction date;
* YearRemodAdd: Remodel date;
* RoofStyle: Type of roof;
* RoofMatl: Roof material;
* Exterior1st: Exterior covering on house;
* Exterior2nd: Exterior covering on house (if more than one material);
* MasVnrType: Masonry veneer type;
* MasVnrArea: Masonry veneer area in square feet;
* ExterQualv: Exterior material quality;
* ExterCond: Present condition of the material on the exterior;
* Foundation: Type of foundation;
* BsmtQual: Height of the basement;
* BsmtCond: General condition of the basement;
* BsmtExposure: Walkout or garden level basement walls;
* BsmtFinType1: Quality of basement finished area;
* BsmtFinSF1: Type 1 finished square feet;
* BsmtFinType2: Quality of second finished area (if present);
* BsmtFinSF2: Type 2 finished square feet;
* BsmtUnfSF: Unfinished square feet of basement area;
* TotalBsmtSF: Total square feet of basement area;
* Heating: Type of heating;
* HeatingQC: Heating quality and condition;
* CentralAir: Central air conditioning;
* Electrical: Electrical system;
* 1stFlrSF: First Floor square feet;
* 2ndFlrSF: Second floor square feet;
* LowQualFinSF: Low quality finished square feet (all floors);
* GrLivArea: Above grade (ground) living area square feet;
* BsmtFullBath: Basement full bathrooms;
* BsmtHalfBath: Basement half bathrooms;
* FullBath: Full bathrooms above grade;
* HalfBath: Half baths above grade;
* Bedroom: Number of bedrooms above basement level;
* Kitchen: Number of kitchens;
* KitchenQual: Kitchen quality;
* TotRmsAbvGrd: Total rooms above grade (does not include bathrooms);
* Functional: Home functionality rating;
* Fireplaces: Number of fireplaces;
* FireplaceQu: Fireplace quality;
* GarageType: Garage location;
* GarageYrBlt: Year garage was built;
* GarageFinish: Interior finish of the garage;
* GarageCars: Size of garage in car capacity;
* GarageArea: Size of garage in square feet;
* GarageQual: Garage quality;
* GarageCond: Garage condition;
* PavedDrive: Paved driveway;
* WoodDeckSF: Wood deck area in square feet;
* OpenPorchSF: Open porch area in square feet;
* EnclosedPorch: Enclosed porch area in square feet;
* 3SsnPorch: Three season porch area in square feet;
* ScreenPorch: Screen porch area in square feet;
* PoolArea: Pool area in square feet;
* PoolQC: Pool quality;
* Fence: Fence quality;
* MiscFeature: Miscellaneous feature not covered in other categories;
* MiscVal: Value (in dollars) of miscellaneous feature;
* MoSold: Month sold;
* YrSold: Year sold;
* SaleType: Type of sale;
* SaleCondition: Condition of sale.
