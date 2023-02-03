# Machine Learning Classification: Human Supervision

Machine Learning systems can be classified according to the amount and type of supervision they get during training

There are four categories:

🟢 Supervised Learning  
🟡 Semi-Supervised Learning  
🟠 Unsupervised Learning  
🔴 Reinforcement Learning

## 🟢Supervised Learning

`In Supervised Learning, the training set also includes the desired output/results also known as labels`

Supervised learning is a type of machine learning where the algorithm learns to predict an output (label or response variable) based on a set of input features. The learning process is "supervised" because the algorithm is trained on labelled data, where the correct output or label is provided for each input. The goal of supervised learning is to build a model that accurately maps inputs to outputs, based on the labelled training data. The model can then be used to make predictions on new, unseen data. Some common applications of supervised learning include image classification, speech recognition, and predictive modelling for various tasks such as credit risk assessment and stock price forecasting.

Supervised Learning can perform two different tasks:

🟢🔵 Regression  
🟢🟣 Classification

### 🟢🔵 Regression

`Regression is a statistical technique which is used to predict continuous values by estimating a relationship between dependent and Independent Variables, plotting a best-fit line or a curve between the data points`

The ultimate goal of the regression algorithm is to plot a best-fit line or a curve between the data points

There are 6 different types of the regression algorithm

🟥 Linear Regression  
🟧 Logistic Regression  
🟨 Ridge Regression  
🟩 Lasso Regression  
🟦 Polynomial Regression  
🟫 Bayesian Linear Regression

### 🟢🟣 Classification

`Classification is a technique which is used to predict the category/label of a given data point, approximating a mapping function from input variables to discrete output variables`

There are three types of Classification algorithm

🟩 Binary Classifier  
🟨 Multi-Class Classifier  
🟥 Multi-label Classifier

## 🟡 Unsupervised Learning

`Unsupervised learning is a technique in which there is no label attached to the training data, the machine tries to learn and discover any naturally occurring pattern in the data set all by itself`

Unsupervised learning is a type of machine learning where the algorithm tries to discover hidden patterns or relationships in a dataset without any labeled data. Unlike supervised learning, unsupervised learning does not have any target or output variables. Instead, the algorithm works by grouping similar data points together into clusters, or by finding lower-dimensional representations of the data, such as principal components. The goal of unsupervised learning is to extract meaningful information from the data and to represent it in a more compact and interpretable form. Some common applications of unsupervised learning include anomaly detection, data compression, and dimensionality reduction.

Some popular unsupervised learning methods include

🟤Clustering  
🔵Principal Component Analysis (PCA)  
🟣Autoencoders.

### 🟡🟤 Clustering

`Clustering is a technique of segregating data and assigning them into similar clusters.`

Clustering is a machine-learning technique that groups similar data points into clusters or clusters. The goal of clustering is to find the natural structure in the data, such as patterns or relationships, without using any prior knowledge or labels. Clustering algorithms work by assigning each data point to a cluster based on its similarity to other points in the same cluster. Common clustering algorithms include k-means, hierarchical clustering, and DBSCAN. Clustering can be used for a variety of applications, such as market segmentation, image segmentation, and anomaly detection.

Some popular Clustering Methods

🟩 Connectivity-based Clustering  
🟨 Centroids-based Clustering  
🟧 Distribution-based Clustering  
🟥 Fuzzy Clustering  
🟦 Density-based Clustering  
🟫 Graph-based Clustering

### 🟡🔵Principal Component Analysis (PCA)

`PCA is a technique for reducing the number of dimensions in data by transforming to a new set of linearly uncorrelated variables.`

Principal Component Analysis (PCA) is a dimensionality reduction technique that is commonly used in unsupervised learning. The goal of PCA is to transform a set of possibly correlated variables into a new set of linearly uncorrelated variables, known as principal components. These principal components capture the maximum amount of variance in the data and are ordered such that the first principal component captures the most variance, the second captures the second most, and so on. PCA can be used for data visualization, and noise reduction, and to increase the interpretability and computational efficiency of machine learning algorithms. PCA is computed using singular value decomposition (SVD) or eigenvalue decomposition of the covariance matrix of the data.

### 🟡🟣Autoencoders

`Autoencoders are neural networks that compress input data into lower-dimensional representations and then reconstruct the original data. They are used for data compression, denoising, and generative modelling.`

An autoencoder is a type of neural network used for unsupervised learning. It consists of two main components: an encoder and a decoder. The encoder compresses the input data into a lower-dimensional representation, known as the encoding or bottleneck representation. The decoder then takes the encoding and tries to reconstruct the original input. The goal of the autoencoder is to learn a compact representation of the data that captures its important features, while ignoring noise or unimportant information. The autoencoder is trained by minimizing the reconstruction error between the original input and its reconstructed output. Autoencoders can be used for a variety of tasks, including data denoising, dimensionality reduction, and generative modelling. Autoencoders can also be used as a pre-training step for supervised learning, where the encoder can be used as a feature extractor and the weights can be fine-tuned using labelled data.

## 🟠 Semisupervised Learning

`Semi-supervised learning involves a small portion of labelled data and a large number of unlabeled data from which a model learns and makes predictions`

Semi-supervised learning is a machine learning technique where the model is trained on both labelled and unlabeled data. This is useful in scenarios where obtaining labelled data is costly, time-consuming, or infeasible, as it allows the model to learn patterns and relationships in the data using the abundant unlabeled data, while still incorporating the relatively sparse labelled data to guide the learning process. The result is a model that can generalize better to unseen data and achieve better accuracy than if it were trained solely on the limited labelled data

## 🔴 Reinforcement Learning

`The learning system is an agent which observes the environment, then select and performs an action according to which it gets a reward or penalty.`

Reinforcement learning is a type of machine learning where an agent learns to make decisions by performing actions in an environment to maximize a reward signal. In reinforcement learning, the agent interacts with the environment by choosing actions, and the environment provides feedback in the form of rewards or penalties. The agent's goal is to learn a policy that maps states to actions to maximize the expected cumulative reward over time. Reinforcement learning has been successfully applied in various fields, such as robotics, control systems, game-playing, and recommendation systems.