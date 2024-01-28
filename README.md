# House Pricing Assignmetn
> To create a Linear Regression Model that explains the demand House Pricing


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- An US-based housing company wants to predict house prices for them to enter the Australian Market
- So, create a Linear Regression Model to predict house prices
- The model should explain two things:
    - Which variables are significant in predicting the demand for shared bikes?
    - How well those variables describe the bike demands

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The best model created: log(house price) = 0.132842 * (Neighborhood|NridgHt) - 0.128209 * (OverallCond|low_rat) - 0.117582 * (Functional|other) + 0.114976 * (BsmtExposure|Gd) - 0.111992 * (ExterQual|low_rating) + 0.110986 * (OverallCond|ex_rat) - 0.108265 * (BldgType|other) - 0.102732 * (MSZoning|RM) + 0.097118 * (SaleCondition|Partial) - 0.089207 * (GarageQual|other_rating_r_no_rating) + 0.068555 * (YearRemodAdd|2000-till date) - 0.063730 * (SaleCondition|other) + 0.060890 * (Foundation|PConc) - 0.053292 * (Condition1|other) + 0.052201 * (GarageType|Attchd) + 0.048199 * (FireplaceQu|low_rating) - 0.031838 * (HeatingQC|low_rating) + 0.028826 * (YearBuilt|1950-1999) - 0.028714 * (Neighborhood|NAmes) + 0.022387 * (OverallCond|gd_rat) + 0.000386 * (GrLivArea) + 0.000146 * (BsmtFinSF1)
- This model uses Ridge Regularization
- Train R2-score: 0.8705868605851732; Test R2-score: 0.8435258072437739
- Top 5 most impactful factors: 
    - Neighborhood|NridgHt
    - OverallCond|low_rat
    - Functional|other
    - BsmtExposure|Gd
    - ExterQual|low_rating

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas
- numpy
- matplotlib
- seaborn
- sklearn
- statsmodels

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->