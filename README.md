# 🏠 House Prices – Advanced Regression Techniques

## 📌 Competition Description
Ask a home buyer to describe their dream house, and they probably won’t begin with the height of the basement ceiling or proximity to a railroad.  
However, this dataset shows that many subtle factors influence house prices beyond bedrooms and curb appeal.

This competition uses **79 explanatory variables** describing nearly every aspect of residential homes in Ames, Iowa, to predict the final **SalePrice**.

---

## 🎯 Goal
Predict the **SalePrice** (in USD) for each house in the test set.

---

## 📏 Evaluation Metric
Submissions are evaluated using **Root Mean Squared Error (RMSE)** between the **logarithm of the predicted value** and the **logarithm of the observed sale price**.

Using logarithms ensures that errors in predicting expensive and inexpensive houses are weighted equally.

---

## 🧠 Skills Practiced
- Creative feature engineering
- Handling missing values
- Encoding categorical variables
- Advanced regression techniques:
  - Random Forest
  - Gradient Boosting

---

## 🚀 Start Here If…
- You have basic experience with **Python or R**
- You understand **machine learning fundamentals**
- You’ve completed an online ML course and want hands-on practice before entering featured Kaggle competitions

A starter notebook is provided to help you get started quickly.

---

## 📊 Dataset Description

### 🎯 Target Variable
- **SalePrice** — Property sale price in dollars

---

### 🏗️ Property & Lot Information
- **MSSubClass** — Building class  
- **MSZoning** — Zoning classification  
- **LotFrontage** — Linear feet of street connected to property  
- **Street** — Type of road access  
- **Alley** — Type of alley access  
- **LotShape** — General shape of property  
- **LandContour** — Flatness of the property  
- **Utilities** — Utilities available  
- **LotConfig** — Lot configuration  
- **LandSlope** — Slope of property  
- **Neighborhood** — Physical location within Ames city limits  

---

### 🏠 Building Characteristics
- **BldgType** — Type of dwelling  
- **HouseStyle** — Style of dwelling  
- **OverallQual** — Overall material and finish quality  
- **OverallCond** — Overall condition rating  
- **YearBuilt** — Original construction year  
- **YearRemodAdd** — Remodel year  
- **RoofStyle** — Roof style  
- **RoofMatl** — Roof material  
- **Exterior1st** — Exterior covering  
- **Exterior2nd** — Secondary exterior covering  

---

### 🧱 Basement
- **BsmtQual** — Basement height  
- **BsmtCond** — Basement condition  
- **BsmtExposure** — Walkout or garden level  
- **BsmtFinType1** — Finished basement quality  
- **BsmtFinSF1** — Finished square feet  
- **BsmtFinType2** — Second finished area quality  
- **BsmtFinSF2** — Second finished square feet  
- **BsmtUnfSF** — Unfinished basement area  
- **TotalBsmtSF** — Total basement area  

---

### 🛋️ Interior Living Area
- **1stFlrSF** — First floor area  
- **2ndFlrSF** — Second floor area  
- **LowQualFinSF** — Low quality finished area  
- **GrLivArea** — Above-grade living area  
- **Bedroom** — Bedrooms above basement  
- **Kitchen** — Number of kitchens  
- **KitchenQual** — Kitchen quality  
- **TotRmsAbvGrd** — Total rooms above grade  

---

### 🔥 Utilities & Comfort
- **Heating** — Heating type  
- **HeatingQC** — Heating quality  
- **CentralAir** — Central air conditioning  
- **Electrical** — Electrical system  
- **Fireplaces** — Number of fireplaces  
- **FireplaceQu** — Fireplace quality  

---

### 🚗 Garage
- **GarageType** — Garage location  
- **GarageYrBlt** — Garage construction year  
- **GarageFinish** — Interior finish  
- **GarageCars** — Garage capacity  
- **GarageArea** — Garage size  
- **GarageQual** — Garage quality  
- **GarageCond** — Garage condition  

---

### 🌳 Outdoor & Miscellaneous
- **WoodDeckSF** — Wood deck area  
- **OpenPorchSF** — Open porch area  
- **EnclosedPorch** — Enclosed porch  
- **3SsnPorch** — Three-season porch  
- **ScreenPorch** — Screen porch  
- **PoolArea** — Pool area  
- **PoolQC** — Pool quality  
- **Fence** — Fence quality  
- **MiscFeature** — Miscellaneous feature  
- **MiscVal** — Value of miscellaneous features  

---

### 🗓️ Sale Details
- **MoSold** — Month sold  
- **YrSold** — Year sold  
- **SaleType** — Type of sale  
- **SaleCondition** — Condition of sale  

---

## 🙏 Acknowledgments
The Ames Housing dataset was compiled by **Dean De Cock** for use in data science education.  
It serves as a modern alternative to the Boston Housing dataset.

Photo by **Tom Thain** on Unsplash.
