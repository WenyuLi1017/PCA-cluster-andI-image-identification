# PCA and K-means cluster

## Content

1.  Breast cancer cluster
2.  Fetch_olivetti_faces image compression

## Breast cancer cluster

<p align="center"><img src="pic/pca_cancer.jpg" alt="Routing" width="500"/></p>
I use the load_breast_cancer from sklearn dataset, and use PCA to compress the features to 2 dimensions. There are 0.632 components explained in 2 dimensions. 

<p align="center"><img src="pic/kmeans.jpg" alt="Routing" width="500"/></p>

Then I use kmeans to aggregate the data into two categories, namely, cancer and no cancer. Finally, compare with the real data and calculate the misdiagnosis rate. The misdiagnosis rate is 0.0949.

## Fetch_olivetti_faces image compression

<p align="center"><img src="pic/rebuild_1.jpg" alt="Routing" width="500"/></p>
<p align="center"><img src="pic/rebuild_400.jpg" alt="Routing" width="500"/></p>

I use the fetch_olivetti_faces from sklearn dataset, and use PCA to compress the features to different dimensions. I show the compressed images under different dimensions and compute the explained variance ratios of these images. The explained variance ratio when use 1 eigenface is  0.238, and the explained variance ratio when use 400 eigenfaces is  0.99999995
