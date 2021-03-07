# Cryptocurrencies
## Overview of the Analysis:
The purpose of this project is to use machine learning to unsupervised learning models to evaluate cryptocurrency data to provide a recommendation to our client Accountability Accounting. We have been asked to analyze and group the cryptocurrencies on the market.

### Technologies:
The following unsupervised machine learning tools were employed in this project: 
sklearn package using StandardScaler and MinMax Scaler to help preprocess the data, principal component analysis and finally KMeans and for clustering the cryptocurrencies. 

### Summary:
We initially created an Elbow Curve to determine the optimal number of k-values and selected '4' as noted in the image below:
![imageelbowcurve.PNG](/Resources/imageelbowcurve.PNG)
Next we ran K-means clustering and rendered this 3D chart showing the tight grouping of class 0 and class 1:
![imageel1.PNG](/Resources/image1.PNG)
We also ran principal component analysis to transform our feature set for another K-means analysis. The analysis similalry clustered the cryptocurrencies with classes 0 and 1 close together as this 2d scatter plot shows:
![imageel3.PNG](/Resources/image3.PNG)