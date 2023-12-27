# Market Segmentation in Insurance
![image](https://github.com/aticem/2.end-to-end-customer-segmentation-ML/assets/65057931/0f490479-d878-4399-b49d-c0c1f24d37c4)

![image](https://github.com/aticem/2.end-to-end-customer-segmentation-ML/assets/65057931/b591ae4e-88fc-48f5-8d0e-3ec0efa69909)


### Objective  :
This case requires to develop a customer segmentation to give recommendations like saving plans, loans, wealth management, etc. on target customer groups.
<img align="center" src="https://user-images.githubusercontent.com/34673684/137431219-a5d99ac4-ce63-4435-8a49-4e19b09d0a07.png" alt="image">
### Data Description : 
The sample Dataset summarizes the usage behavior of about 9000 active credit card holders during the last 6 months. The file is at a customer level with 18 behavioral variables.

### Algorithms used :  
In this dataset i've used five clustering algorithm to perform segmentation.These algorithms are given below.
- [K-Means Clustering](https://en.wikipedia.org/wiki/K-means_clustering)
- [Agglomerative Clustering](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.AgglomerativeClustering.html)
- [Spectral Clustering](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.SpectralClustering.html)
- [DBSCAN Clustering](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.DBSCAN.html)
- [GaussianMixture Model based clustering](https://en.wikipedia.org/wiki/Mixture_model)
### Final Model  :
I have created a Streamlit Application based on this clustering technique, where I am taking the customer details & identifying which cluster the custoemr belongs to.
