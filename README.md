# Diabetes Analysis

In this analysis, I first provide some descriptive statistics to better understand the dataset. Key variables include glucose and Outcome (binary). I conducted several tests to assess the data distribution, including the Shapiro-Wilk test, Kolmogorov-Smirnov test, t-test, and QQ plot.

Missing values were handled using multiple imputation with the predictive mean matching (PMM) method. Afterward, I applied logistic regression to predict the presence of diabetes, achieving 80% accuracy. I analyzed the model coefficients and odds ratios to determine the most influential variables. Based on these insights, I performed feature engineering and refined the model by reducing the dataset's complexity while maintaining accuracy. The model was further evaluated using the AUC-ROC curve, optimizing simplicity without sacrificing performance.

I also implemented a decision tree model, which outperformed logistic regression with an accuracy of 85%. Additionally, I explored clustering techniques such as K-means and K-medoids to gain further insights into the data. I visualized the results through scatter plots and t-SNE.

Dataset Link: https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database

Tools Used: 
- R Studio
- Libraries: tidyverse, mice, caret, pROC, RandomForest, rpart, MASS, cluster, Rtsne
