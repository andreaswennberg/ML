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

### Fraud Detection Case

Think about variables. Here are some interesting parts:

Amount spent
IP address
Number of failed attempts
Time since last transaction
Location of transaction

The list of these are the feature vectors.

We don't know what these values will be, but we will know what range the value will be in.

Amount spent [0, infinity]
IP address [all IP addresses in the world]
Number of failed attempts [0, 1, 2]
Time since last transaction [0, 1, 2]
Location of transaction [Stockholm, Uppsala]

We can't know what the value is beforehand.

A random variable is a variable whose value is subject to variations due to chance. - Stochastic variable.

### Random Values
Discrete - integer values
Continuous - any value
Categorical - can take one of a limited, fixed set of values.

Categories/group.

A statistical experiment. We know the possible outcomes beforehand.

Uniform probability distribution: has a known function.

The normal distribution - occurs a lot in natural phenomena.

A measurement is a random variable. most of the measurements would be concentrated near a central point.

P(A|B) = P(A and P)/ P(B)
What is the probability of A given that B.

A priori probability - stat before we have an evidence that outcome.
A posterio probability

After the fact takes into account more information and are therefore more insightful.

Naive Bayes is called naive because it assumes the features are independent of each other.

### K-Nearest NEIGHBOURS

We represent all emails as points in a hypercube.

Measure the distance between the different cases.

Find the K Nearest Neighbors. Basically, plot out all over points in a feature space. Plot out the problem instance.

Dimensionality - length of the feature.
Vector - number of coordinates needed to express each point.

Feature extraction: for instance using principal components analysis or hashing.

Euclidean distance only works with continuous variables.

### Support Vector Machines

A support vector machine is used to build binary classifiers.

A support vector machine is a supervised machine-learning approach used to build linear non-probabilistic binary classifiers.
