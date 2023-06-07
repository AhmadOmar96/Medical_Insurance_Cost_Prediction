# A Medical Insurance Cost Prediction using Liner, Ridge, and Random Forest Regression
* The [dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance) utilized for this study is made up of a sizable number of anonymized medical insurance records that includes a range of demographic and health-related factors. Following preprocessing of the data, feature engineering approaches are used to improve the models' prediction skills. Exploratory data analysis is done to learn more about the relationships between the independent factors and the price of health insurance.
* The Linear Regression model is applied as a baseline model, followed by the Ridge Regression and Random Forest Regression models, to estimate the costs of medical insurance. The models are tested using the R-squared score after being trained using a portion of the dataset.
* According to the results the liner and ridge regression approaches produce relatively accurate estimates of medical insurance costs. However, the Random Forest Regression model performs better than the others, obtaining the highest R-squared rating. According to these results, the ensemble-based method of Random Forest Regression well captures the nonlinear associations inherent in the dataset, leading to increased prediction accuracy.


## Checking missing data:
The dataset has no missing data.

## Dataset analysis:
we explored many relationships between attributes according to the figured charts:


<img src="https://i.postimg.cc/7GgwNcLb/1.png" align="center" />
<img src="https://i.postimg.cc/vxbM2z1h/2.png" align="center" />
<img src="https://i.postimg.cc/ZvHmGdpS/3.png" align="center" />
<img src="https://i.postimg.cc/pyHFtMzG/4.png" align="center" />
<img src="https://i.postimg.cc/K1w1q6m5/5.png" align="center" />
<img src="https://i.postimg.cc/2VjLVdHn/7.png" align="center" />
<img src="https://i.postimg.cc/Z0xybsLT/6.png" align="center" />
<img src="https://i.postimg.cc/k2BVyJP4/8.png" align="center" />

## Regressin Models:
After splitting the data, we defined the models using **sklearn** in Python, fitted the model, and calculated the R-squared score. We then applied the obtained model to calculate the cost of a new sample `[age:50, bmi:25, children:2, smoker:1, region:2]` to obtained the below mentioned results.

<img src="https://i.postimg.cc/HxnjGsKs/0.png" align="center" />
