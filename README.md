# Maching-Learning-Mock-Classification
A Classification problem on machine learning is answered. 

# Source of Data

I plan on predicting the fires using data from a smoke detector. And this [link](https://www.hackster.io/stefanblattmann/real-time-smoke-detection-with-ai-based-sensor-fusion-1086e6#toc-dataset-7) has a comprehensive description and gives us a data dict.

# Machine Learning Preparation and Processing

Since you have categorized this as a classification problem, you will likely need to use algorithms such as , decision trees, or random forests to classify the data into "fire" and "no fire" categories.

Data exploring and cleaning was taken placed, it includes missing valueschecking, identifying outliers, and ensuring the data is properly formatted. On machine learning algorithms, logistic regression and KNN were used and I also tuned them with parameters. Finally, performance evaluation was applied whilst using metrics such as accuracy, precision, recall, and F1-score.

#Results

![image](https://user-images.githubusercontent.com/126204698/231933112-7f5378fa-25bc-4a64-874c-776dd6973362.png)

1. Results above shows Tuned KNN is the mest model amongst four becaue it has the highest metrics on testing datas. 

2. False Negatives (Type 2 Errors) are more costly than False Positives (Type 1 Errors) in this project.

3. In this project, false positive is predicting a fire when there is none whilst false negative is predicting nothing if there is a fire. 

# Further questions
1. What is the probability of a fire given a certain set of sensor readings?
2. Which sensors are most important for predicting fires?
3. Can we use this model to detect fires in real-time and trigger alarms?
