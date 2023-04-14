# Maching-Learning-Mock-Classification
A Classification problem on machine learning is answered. 

# Source of Data

I plan on predicting the fires using data from a smoke detector. And this [link](https://www.hackster.io/stefanblattmann/real-time-smoke-detection-with-ai-based-sensor-fusion-1086e6#toc-dataset-7) has a comprehensive description and gives us a data dict.

# Machine Learning Preparation and Processing

Data exploring and cleaning was taken place, which includes missing values checking, outliers identifying ,and ensuring the data is properly formatted. On machine learning algorithms, logistic regression and KNN were used and I also tuned them with different parameters. Finally, performance evaluation was applied whilst using metrics such as accuracy, precision and F1-score.

#Results

![image](https://user-images.githubusercontent.com/126204698/231933112-7f5378fa-25bc-4a64-874c-776dd6973362.png)

- KNN is the mest model amongst all with the best testing data metrics.

- Key insights on metrics

1. In this project, false positive (Type 1 Errors) is predicting a fire when there is none whilst false negative (Type 2 Errors) is predicting no fire but actually there is a fire. Therefore, we can tell that **false negatives are more costly than false positives in this project.**

2. Precision is a bit higher than accuracy (.967 > .967) which is fine because we can tolerate with false positives in this case.

# Further questions

1. Which sensors are most important for predicting fires?

2. Can we use this model to detect fires in real-time and trigger alarms?
