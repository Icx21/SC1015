# Welcome to our SC1015 Mini Project

## About
This is a Mini-Project for SC1015 which focuses on predicting a Car's resale value in a Fair Market. For a detailed walkthrough, please view the code in the order: 
1. [Data Extraction](https://github.com/Icx21/SC1015/blob/main/data_extraction.ipynb)
2. [Data Visualisation](https://github.com/Icx21/SC1015/blob/main/data_visualization.ipynb)
3. [Data Machine Learning](https://github.com/Icx21/SC1015/blob/main/data_machinelearning.ipynb)

To view the Database that we use:
1. [Orginal Database](https://github.com/Icx21/SC1015/tree/main/Cars)
2. [Cleaned Data Excel Sheet](https://github.com/Icx21/SC1015/blob/main/cleaned_data.csv)


## Contributors:
- @Icx21 - Data Extraction, Data Visualisation
- @yanyox - Machine  Learning, Slides, Script
- @zk0008 - Analysis, Slides, Script

## Problem Statement:
Given a dataset comprising multiple factors, we aim to determine a fair market value for a used car and predict its resale price. By leveraging multiple variables and typical data associated with used cars, we seek to develop a reliable model that accurately estimates the value of a vehicle based on these factors.

## Motivation:
Every factor we use in the data contributes to an unreasonable resale price for a vehicle (for example: higher mileage often leads to a lower resale price and a vehicle's history, including accidents, title status, and maintenance records, can affect its resale value).
The motivation behind reaching our problem statement of predicting used car resale prices stems from Transparency, Risk Mitigation, Market Optimization, and Efficiency.
By addressing these motivations, our project aims to provide an accurate estimation tool for determining the fair market value of pre-owned vehicles by creating a predictive model that considers the intricacies of the automotive market. 

## Dataset:
The dataset, sourced from Kaggle and focused on the Indian automotive market, comprises 6019 entries and includes resale prices along with key factors deemed significant in the car-buying process, such as mileage and power.

## Model Used: 
1. Random Forest Regression
2. Gradient Boosting Regressor
3. Support Vector Regression
   
## Conclusion: 
Gradient Boosting and Random Forest have significantly lower MSE values compared to Support Vector Regression. This indicates that both Gradient Boosting and Random Forest models perform much better than the Support Vector Regression model in terms of predicting prices on the testing dataset.

Gradient Boosting has a slightly higher MSE than Random Forest, but the difference is not substantial. Both models seem to perform similarly, but Random Forest has a slightly better performance based on the MSE metric.

The SVR model has a very high MSE compared to Gradient Boosting and Random Forest. This suggests that the SVR model might not be suitable for this particular dataset.

In summary, based on the MSE metric, Gradient Boosting and Random Forest models outperform the SVR model in predicting prices on the testing dataset, with Random Forest showing slightly better performance than Gradient Boosting.

## What did we learn from this project? 

- Learned that estimation of car prices are relatively due to different factors based on our analysis
- Learned new regression techniques
- Machine Learning helps to automate processes (e.g Physical evaluation of a used car can be done through machine learning)
- Our project could be a way for users to not get overcharged for a used car (E.g implmenting more training for the model, feeding more data would make the model predict prices more accurately)

## Reference: 
- <https://www.kaggle.com/datasets/colearninglounge/used-cars-price-prediction>
- <https://builtin.com/data-science/random-forest-python#:~:text=What%20Is%20Random%20Forest%20Regression,trees%20while%20building%20the%20trees.>
- <https://towardsdatascience.com/all-you-need-to-know-about-gradient-boosting-algorithm-part-1-regression-2520a34a502>
- <https://www.analyticsvidhya.com/blog/2020/03/support-vector-regression-tutorial-for-machine-learning/#:~:text=Support%20Vector%20Regression%20(SVR)%20is,while%20minimizing%20the%20prediction%20error.>
