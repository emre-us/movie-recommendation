# movie-recommendation

This is an example of a recommendation system.

This project attempts to accurately recommend movies based on preferences, much like NetFlix, Amazon, Hulu or other streaming service.

The main aim is to accurately predict movies users are likely to enjoy.

It uses the following packages:

dslabs for the subset of movielens data <br>
tidyverse for tidy data <br>
gridExtra for grid arrangement of graphs <br>
dplyr for data wrangling <br>
ggplot2 for visualisations<br>
caret for machine learning, for resampling and model training, including kNN <br>


randomForest for carrying out random forest<br>
and <br>
matrixStats as an option for calculating matrix statistics (eg rowSds, colSds)

The movielens data by GroupLens reearch project can be found here: https://grouplens.org/datasets/movielens/ 

There are many versions of this data at the GroupLens research project's website. In this project a subst of 20M dataset is being used, online documentation of which is here:  https://files.grouplens.org/datasets/movielens/ml-20m-README.html

The subset of this data is provided within the dslabs package.

This is a project from HarvardX Data Science programme. For more information see www.edx.org and the book Introduction to Data Science: Data Analysis and Prediction Algorithms with R by Raafael A Irizarry (https://rafalab.github.io/dsbook/)
