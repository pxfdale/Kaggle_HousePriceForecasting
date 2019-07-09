# Kaggle_HousePriceForecasting
Integrated learning of machine learning for price forecasting
This is the final project of "Statistical Machine Learning", we used ensembling methods to do house price learning.
In the stacking, we chose Lasso, Ridge, SVR, Kernel Ridge, ElasticNet, BayesianRidge as the first layer model, and the second layer model used Kernel Ridge. The role of the first layer model is to train an n × m feature matrix for inputting the second layer model training, where n is the number of training data rows and m is the number of first layer models. Here, the feature matrix of the first layer model is extracted by the method of get_oof, and then spliced with the original features. Finally, the score is found to be 0.1047, and the effect is better than before.
We submit our submission.csv in Kaggle and get our final scores. The final ranking is 724/4501 ≈ 16.085%.
