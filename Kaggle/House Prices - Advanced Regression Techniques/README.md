# House Prices - Advanced Regression Techniques
*"Predict sales prices and practice feature engineering, RFs, and gradient boosting"*

## Link
**Kaggle**: https://www.kaggle.com/c/house-prices-advanced-regression-techniques

---

## Description
Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

---

## Evaluation 

### Goal 
Predict the sales price for each house. For each id in the test set, you must predict the value of the `SalePrice` variable.

### Dataset
[Ames Housing Dataset](http://jse.amstat.org/v19n3/decock.pdf)
> Compiled by Dean De Cock for use in the data science education. It's an incredible alternative for data scientists looking for a modernized and expanded version of the often cited *Boston Housing* dataset.

### Metrics
Submissions are evaluated on [Root-Mean-Squared-Error](https://en.wikipedia.org/wiki/Root-mean-square_deviation) between the logarithm of the predicted value and the logarithm of the observed sales price.

## Skills Practiced 
- Creative feature engineering
- Advanced regression techniques like random firest and gradient booting