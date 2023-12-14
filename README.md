# ML_Clustering_K-Means_Spotify_Project

In this projectt:
We load the Spotify music dataset from a 'df_audio_features_10.csv' file.
We select relevant features for clustering from the DataFrame df.
We use the elbow method to determine an optimal number of clusters and then perform K-means clustering using KMeans class from scikit-learn.
The predicted cluster labels are added back into the original dataframe.
Finally, we visualize clustered data using scatter plot where danceability and energy are plotted against each other and colored by their respective cluster.
