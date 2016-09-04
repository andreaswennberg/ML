A point in a N-dimensional space needs N coordonates to be represented.

Line - one number
Square - two numbers
Cube - three numbers

N-dimensional hypercube. It just mean that each point in this hypercube is a list of N values.

Any email can be represented as a point in a hypercube.

Imagine a list with all words:
(W1, W2, ... ... ... ... Wn)

Any email will be a subset of those

Let say that the entire universe of words are:

(hello, why, there, how, are, the weather, you)

Messages can be represented as a tuple of 1's and 0's

Hello there how are you

(1, 0, 1, 1, 1, 0, 0, 1)

We can represent any email as a point in a hypercube.

The email that we want to categorize - problem instance.

The emails that we already have - training data.

Find the K NEAREST NEIGHBOURS of our problem instance.

Naive Bayes assume that probability distributions are not independent.

Problems where ML is often used:
* Classification - Spam detection
* Clustering - topic modeling
* Association detection - sentiment analysis
* Anomaly detection - recommendations
* Dimensionality reduction - genre classification, quant trading

### Classification

We have a population with two categories.

We have the training date. Some data where we have done some categorization.

Then we are given a new problem instance.

We want to assign a label/category for the new problem instance.

An algorithm that implement classification is called a classifier.

Three commonly used algos:

Naive Bayes
K-Nearest neighbor
Support Vector Machine

Classification is a form of supervised learning. A set of classified data is available.

### Clustering

Given set of instances. (All Facebook users)

Divide those instances into clusters, so that instances within a cluster are more similar to each other. Like, age group, gender.

Clustering is very closely related to classification.

A new user has signed up - what community will she most likely belong to?

Clustering can be used before the classification.

Classification is a bit more focused on classifying a problem instance.

Clustering is a prototypical example of unsupervised learning. There are no training data.

K-means Clustering
Hierarchical Clustering
Density-based Clustering
Distribution-based clustering.

### Association detection

Your job is a category manager. You want to sell as much as possible as high as possible while spending as little as possible on marketing.

What if you figure out that if a person buys A, then they are also possible to know that the person want to buy B.

You can offer things or packages.

Association rules learning.

Think Amazon suggested buys.

### Anomaly detection
How do you know that a specific traffic is harmful?

Intrusion detection system.

Anomaly can be seen as a classification problem or a clustering problem. (Finding network packets that work in a weird way)

### Dimensionality Reduction Techniques

Any rich representation of a complex instance requires a lot of features. Doing something with data is hard.

Dimensionality reduction techniques reduce the number of dimensions and make it much more efficient to deal with the data.
