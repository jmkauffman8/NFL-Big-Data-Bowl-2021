# NFL-Big-Data-Bowl-2021
Project that uses  Machine Learning Models on player tracking data from AWS to make predictions about the expected yardage on a play. 

## Overview of NFL Big Data Bowl Project
This project employs a training and testing dataset and provided by the NFL during their 2021 Big Data Bowl. After creating several preliminary visualizations and cleaning the data to track player motion directions, I train a Random Forest model using the given dataset of ~42,000 plays to predict the expected gain on plays where we know defender position, rusher, down, distance, and more

## Introduction
The NFL Big Data Bowl project is a data science competition hosted by the NFL every year, where data enthusiasts and machine learning experts come together to analyze and solve real-world problems using NFL data. The 2021 edition of the competition focused on player tracking data and challenged participants to develop predictive models for the expected yardage on a given play. In this project, we used machine learning models to predict the expected yardage on a given play using player tracking data from AWS. 
Below is a screenshot of a visualization produced at the start of an NFL play.
<img width="934" alt="Screen Shot 2023-02-21 at 4 08 46 PM" src="https://user-images.githubusercontent.com/105028034/220469805-fcb90b63-e06c-4acf-94d9-722d8ceffe25.png">

## Methodology
The project began by exploring the data and creating visualizations to gain insights into the nature of the data. We found that the data had a large number of variables and required significant cleaning and feature engineering to make it suitable for machine learning models. We used R and the dplyr library for data manipulation and cleaning.

We then used the cleaned data to train and test several machine learning models, including linear regression, decision tree, and random forest. We selected the random forest model as the final model for this project because it provided the best results in terms of accuracy and interpretability.

The random forest model was then used to make predictions on the test data, and we evaluated its performance using the mean absolute error metric. We also used feature importance plots to gain insights into which features had the most significant impact on the model's predictions.
Below is a screenshot showcasing the player directions derived from data cleaning
<img width="737" alt="Screen Shot 2023-02-21 at 4 11 12 PM" src="https://user-images.githubusercontent.com/105028034/220470174-a26030d3-af76-4d0e-8ace-6506f4b09681.png">

## Results
Our final model achieved a mean absolute error of 1.6 yards on the test data, which was significantly better than the baseline model's mean absolute error of 3.2 yards. The feature importance plots showed that the rusher's speed and the distance to the endzone were the two most critical features in predicting the expected yardage on a given play.
Below is a screenshot of the direction/result predicted by our Random Forest model
<img width="686" alt="Screen Shot 2023-02-21 at 4 13 03 PM" src="https://user-images.githubusercontent.com/105028034/220470453-415a6c62-b955-443b-9714-34bd342a5e4b.png">

## Conclusion
In conclusion, this project demonstrates the potential of machine learning models in analyzing and predicting NFL player tracking data. By using the random forest model, we were able to achieve accurate and interpretable predictions for the expected yardage on a given play. The insights gained from this project can be used to improve player performance and team strategy in the NFL.
