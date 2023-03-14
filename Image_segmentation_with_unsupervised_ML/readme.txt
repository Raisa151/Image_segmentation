Unsupervised Learning: 
Unsupervised machine learning uses machine learning alorithms to analyze and cluster unlabeled data.

K-mean clustering:
K-mean groups similar datapoints together and discover underlying patterns. Value of k which indicates the number of centroids has to be determined.
This algorithm identifies k number of centroids and them allocates every data point to the nearest cluster while keeping the centroids as small as possible.

Image segmentation with k-mean clustering: https://docs.opencv.org/3.4/d1/d5c/tutorial_py_kmeans_opencv.html

GMM:
A Gaussian mixture model is a probabilistic model that assumes all the data points are generated from a mixture of a finite number of Gaussian distributions with unknown parameters. One can think of mixture models as generalizing k-means clustering to incorporate information about the covariance structure of the data as well as the centers of the latent Gaussians.

GMM vs K-means:
GMM associate probability with each data point while k-mean strictly assign data point to one and only one cluster cluster. In other words, K-means performs hard classification whereas GMM performs soft classification. But in reality there may be overlapping between the cluster. GMM provide us the probabilities of the data point belonging to each of the possible clusters. In cases where there are overlapping datapoints GMM works better than k-mean. In addition, k-means
works great for circular data however the data takes different shapes it does not work well, while GMM takes in account the value of variance so it works for 
all shapes of data.

AIC/BIC: 
The Akaike information criterion (AIC) and the Bayesian information criterion (BIC) provide measures of model performance that account for model complexity.
AIC and BIC combine a term reflecting how well the model fits the data with a term that penalizes the model in proportion to its number of parameters.
So it can be used to determine optimal parameter of a model.

Histogram Segmentation:
If the image histogram shows seperate distribution of pixels of the image we can use histogram segmentation.
Histogram-based thresholding assumes that homogeneous objects in the image manifest themselves as clusters. The key to the histogram-based technique is the selection of a set of thresholds that can discriminate different pixels.
