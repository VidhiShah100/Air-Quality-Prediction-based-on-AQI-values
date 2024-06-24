# Air-Quality-Prediction-based-on-AQI-values

This repository hosts the source code and dataset for predicting air quality using AQI values. It includes an initial Exploratory Data Analysis (EDA) followed by a comparative analysis of four machine learning models: K-Nearest Neighbors (KNN), Naive Bayes Classifier, Random Forest Classifier, and Extreme ML.

During the Exploratory Data Analysis (EDA), the null and NaN values as well as outliers were handled. A heatmap was utilized to identify features with the highest correlations. Based on governmental data, the Air Quality Index (AQI) was calculated and air quality was discretized on a scale from one (1) to six (6), with one indicating the best quality. The processed data was then used to run four machine learning models: K-Nearest Neighbors (KNN), Naive Bayes, Random Forest, and Extreme Learning Machine (ELM). A comprehensive comparative analysis of these models was subsequently performed. 

## Final findings: 
KNN has the highest accuracy and is robust to noise but computationally expensive on a large dataset. It is followed by Naive Bayes, Random Forest and finally the ELM model. KNN and Naive Bayes are performing better in this case due to their simplicity, flexibility, and ability to handle the specific characteristics of the dataset more effectively than Random Forest. KNN's local decision-making and robustness to noise and Naive Bayes' efficiency and handling of high-dimensional data makes them better suited for this problem compared to the more complex Random Forest model. However, KNN takes more time and therefore, considering the balance between accuracy and computational efficiency, the Naive Bayes classifier is the best choice for this dataset. 

