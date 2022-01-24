# Cryptocurrencies
## Analysis Overview
   The purpose of this project is to use unsupervised machine learning to analyze a database of cryptocurrencies and create a report including the traded cryptocurrencies          classified by 
   group according to their features.This classification report could be used by an investment bank to propose a new cryptocurrency investment portfolio to its clients.
   We use the following methods for the analysis:

   * Preprocessing the database,
   * Reducing the data dimension using Principal Component Analysis,
   * Clustering cryptocurrencies using K-Means,
   * Visualizing classification results with 2D and 3D scatter plots. 

### Results: Following the preprocessing and cleaning phase, we have a total of 532 tradable cryptocurrencies.

* **Clustering Cryptocurrencies using K-Means - Elbow Curve**
We don't know what would be the output of the analysis so we are using unsupervised machine learning to identify clusters of the cryptocurrencies.
We produced the elbow curve below using the K-Means method iterating on k values from 1 to 10.

![elbow_curve](https://user-images.githubusercontent.com/90277142/150712148-5ff9bec2-a43b-4596-ae38-32a8e76e1bc6.png)

The best k value appears to be 4 so we would conclude on an output of 4 clusters to categorize the crytocurrencies.

* **Visualizing Cryptocurrencies Results**
  **3D-Scatter plot with clusters**
  
  ![3D_Shape](https://user-images.githubusercontent.com/90277142/150712170-7d45d702-b275-4e8c-91f8-f099b8118c02.png)
