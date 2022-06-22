# 1 ) First of all importing important Libraries and Files 
# 2 ) Read data from CSV (Train , Test)
# 3 ) Value of Head and Tail
# 4 ) Check any value is null or not
# 5 ) Splitting the train dataset in train and validation dataset in 4:1 - > 80,20 ratio

## Train Dataset Shape : (3128, 57)
## Validation Dataset Shape : (782, 57)
## Test Dataset Shape : (691, 57)

# 6 )  Plotting bar plot of 'Y' for imbalanced data
# 7 )  Univarient Analysis   
# 8 )  Plotting variance of features using PCA
# 9 )  Visualizing Train Dataset using T-SNE
# 10)  Feature Selection
# 11)  Heatmap for correlation 
# 12)  Drop and Remove some sparse value row
# 13)  Hyperparameter tunning the Decision Tree
# 14)  Normalizing the Dataset for Training
#  Machine Learning Algorithms
# 15) Navie Bayes
# 16) Logistic Regression
# 17) K-Nearest Neighbor (KNN)
# 18) Support Vector Machine (SVM)
# 19) Decision Tree
# 20) Random Forest
# 21) XGBoost
# 22) Testing Best Model

# +--------------------------------+----------------+----------------+-----------+----------------+
# |             Model              | Train Accuracy | Valid Accuracy | Train AUC | Validation AUC |
# +--------------------------------+----------------+----------------+-----------+----------------+
# |          Navie Bayes           |    84.9104%    |    85.6777%    |   0.7278  |     0.7406     |
# |      Logistic Regression       |    91.4322%    |    93.9897%    |   0.9052  |     0.9332     |
# |    K-Nearest Neigbour (KNN)    |    93.6061%    |    90.1534%    |   0.8723  |     0.8706     |
# | Suport Vector Classifier (SVC) |    95.7161%    |    93.9897%    |   0.9524  |     0.9390     |
# |         Decision Tree          |    96.3554%    |    93.2225%    |   0.9577  |     0.9292     |
# |         Random Forest          |    92.5191%    |    93.0946%    |   0.9102  |     0.9201     |
# |            XGBoost             |    99.6803%    |    95.0127%    |   0.9959  |     0.9485     |
# +--------------------------------+----------------+----------------+-----------+----------------+

