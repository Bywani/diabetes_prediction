![diabetes](https://user-images.githubusercontent.com/85582924/207213511-34e43523-5974-4e78-8a47-bc37ad321eae.jpg)

# Diabetes - Business Problem

Diabetes is a chronic long-lasting health condition that affects how your body turns food into energy. Your body breaks down most of the food you eat into sugar (glucose) and releases it into your bloodstream. When your blood sugar goes up, it signals your pancreas to release insulin. Diabetes often leads to cardiovascular disease, stroke, kidney damage, and long-term damage to the extremities such as the limbs and eyes.

In this project, we will use machine learning algorithms to address the issue of diabetes. We will use the labeled vital measurements of the patients for example, "Age and Blood Insulin Level" from data then train them using machine learning neural networks to make predictions on new patients.

## The Diabetes Dataset

The dataset that will be used in this project is obtained from the Pima Indians Diabetes dataset, as provided by the National Institute of Diabetes, Digestive, and Kidney Diseases and hosted by Kaggle https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database.

## Project Summary

In this project, we have designed and implemented a Neural Networks Multi-Layer Perceptron that is capable of predicting the early symptoms or stages of diabetes with 76% accuracy.

When exploring our data we looked at the distribution of each variable, as well as the relationship between each of those variables and the target variable. After exploratory data analysis, we performed some data preprocessing to remove any missing data to avoid overfitting in our model performance by standardizing such that each variable has a mean of 0 with a unit standard deviation. Then, we moved forward to train-test and split our data into three categories: "Training Set, Validation Srt, & lastly Testing Set". 

<img width="837" alt="Screenshot 2023-01-08 at 19 23 01" src="https://user-images.githubusercontent.com/85582924/211388152-69176ebb-94a9-4049-888d-83e04a10f60c.png">

<img width="1083" alt="Screenshot 2023-01-08 at 19 14 41" src="https://user-images.githubusercontent.com/85582924/211388192-b97ef16c-eac8-4023-821e-bd0df5c9079f.png">

The Neural Network MLP architecture that was used in this project consist of 2 hidden layers, with 32 nodes in the first hidden layer and 16 nodes in the second hidden layer. 
