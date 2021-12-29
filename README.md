# Neural-Collaborative-Filtering

In the last decade, many studies have been carried out on how to use deep learning in various
fields like natural language processing, speech recognition, fraud detection and computer
vision. The application of deep learning in these fields have proven to be highly effective.
In the recent years, deep learning has also become popular in the field of recommendation
systems. There are several studies using deep learning to learn user and item auxiliary
features in recommendation systems. However, to model the user-item interactions in
collaborative filtering, dot product is more commonly used.

While there are several algorithms used to build recommendation systems, collaborative
filtering using matrix factorization is one of the most extensively used algorithms. Matrix
factorization uses dot product to approximate the interaction between user and item latent
features. However, this choice of interaction function has some limitations.

We study how to use deep neural networks to learn the interactions between
users and items from implicit feedback data, instead of using the dot product. We study the
model, Neural Collaborative Filtering, which can be considered as a generic framework for
incorporating neural networks in collaborative filtering. Multi-layer perceptron is used in this
framework to learn a non-linear function to overcome the shortcomings due to the linearity
of the dot product. Empirically we demonstrate that deep neural networks in collaborative
filtering is promising and by increasing the number of hidden layers, the model provides
better recommendations.

References:
1. https://arxiv.org/abs/1708.05031
2. https://github.com/hexiangnan/neural_collaborative_filtering
3. https://towardsdatascience.com/deep-learning-based-recommender-systems-3d120201db7e
