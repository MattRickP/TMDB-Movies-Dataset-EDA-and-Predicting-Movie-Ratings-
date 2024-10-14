### TMDB-Movies-Dataset-EDA-and-Predicting-Movie-Ratings

In the "Movies_EDA_final.ipynb" notebook we examine the TMDB movie dataset in detail. In the "Movies_ML_final.ipynb" notebook, our goal is to build a robust machine learning model to predict the average user rating ("vote_average") of movies. Given that the dataset is frequently updated with new movies, releases and votes, relying on a single model may not be sufficient.  
To account for this, we will employ a combination of powerful machine learning algorithms, XGBoost Regressor, (Light-)GBM Regressor and RandomFOrest Regressor and further enhance the performance by combining LGBM and RandomForest into a stacking model with a Linear Regression meta-model. This approach allows us to leverage the strengths of those models and mitigate potential inaccuracies due to changes in the dataset.  
  
The dataset used in this repository was created by Asaniczka (name on kaggle.com) and is licensed under the ODC Attribution License (ODC-By).  
https://www.kaggle.com/datasets/asaniczka/tmdb-movies-dataset-2023-930k-movies/data
