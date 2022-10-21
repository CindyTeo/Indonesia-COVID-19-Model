# Indonesia-COVID-19-Model

The purpose of this study is to know the effect of weather factors and community mobility towards daily confirmed cases in 34 provinces of Indonesia using correlation test. Other than that, this study also aims to get a linear equation between these variables using counting GLM, namely the Poisson model and negative binomial model. 

There are two models for each province where a model is formed without using the clustering method and the other one is formed with the use of clustering method. K-means clustering algorithm will be used to cluster each province in Indonesia based on the weather factors. Performance of the two models will be compared by the MAE (Mean Absolute Error), MASE (Mean Absolute Squared Error), and RMSE (Root Mean Squared Error) values. 

Research result shows that the majority of weather factors are negatively correlated with daily confirmed cases, whereas most of the community mobility variables are positively correlated. There are 5 clusters formed based on weather factors, with 2 clusters containing only one province each. Daily cases of 31 provinces are better modeled without the clustering method and 3 others are better modeled with the clustering method applied.

As an example, only 1 province (DKI Jakarta) models would be uploaded in these files.
