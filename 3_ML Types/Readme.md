<h1>Machine Learning Types</h1>

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1221dd95-5d7a-4ede-998c-ab3c6af03d0b/Untitled.png)


<h3>Supervised machine learning</h3>

Data type - Lebal Data

If your have data which having input (x) and output (y) also then with the help of this data pattern. after training machine learning model then machine able to make decison in future cases

Two types of data in machine learning :-

1. Numerical
2. Categorical column

Generally two types of problem in supervised machine learning :-

1. Regression

If your model having numerical data for example house price prediction output is numerical (like -age, salary), Regression model is only for numerical output

1. classification

If category is output (yes or no, )

### Unsupervised learning

Unsupervised learning refers to the **use of artificial intelligence (AI) algorithms to identify patterns in data sets containing data points** that are neither classified nor labeled. ... In other words, unsupervised learning allows the system to identify patterns within data sets on its own.

<b>Clustering</b>

Cluster analysis or clustering is the task of grouping a set of objects in such a way that objects in the same group are more similar to each other than to those in other groups.

Clustering is an **unsupervised machine learning method of identifying and grouping similar data points in larger datasets without concern for the specific outcome**. Clustering (sometimes called cluster analysis) is usually used to classify data into structures that are more easily understood and manipulated.

for example

- grouping data having some range like bad-good-excellent
- Converting some category into some form of cluster

<b>Dimensionality reduction</b>

- If we have large input column then in Dimensionality reduction remove extra column which is not helpfull to machine learning algorithum
- Reduce Dimension of data to make use full for visuals
- when data is in high diamention that case we use dimensionality reduction to capture this relation of data and converted into low dimention with same relation.

For example mnist data set

<b>Anomaly detection</b>

Anomaly detection (aka outlier analysis) is **a step in data mining that identifies data points, events, and/or observations that deviate from a dataset's normal behavior**. Anomalous data can indicate critical incidents, such as a technical glitch, or potential opportunities, for instance a change in consumer behavior.

In data analysis, anomaly detection is the identification of rare items, events or observations which raise suspicions by differing significantly from the majority of the data.

Input data is not performing well as like past data or training data then machine thinks is a anomoly 

<b>we us anomoly in : -</b>

- credit card fault detection
- Loan froud detection
- Manufactring detect
- Crime analysis

<b>Association rule</b>

Association rule mining finds interesting associations and relationships among large sets of data items. This rule shows how frequently a itemset occurs in a transaction. A typical example is Market Based Analysis.

Market Based Analysis is one of the key techniques used by large relations to show associations between items.It allows retailers to identify relationships between the items that people buy together frequently.

<b>Case Study - Beer and Diapers: The Impossible Correlation</b>

[https://tdwi.org/articles/2016/11/15/beer-and-diapers-impossible-correlation.aspx](https://tdwi.org/articles/2016/11/15/beer-and-diapers-impossible-correlation.aspx)

<b>Types of machine learning</b>

<b>semi-supervised</b>

upervised learning and unsupervised learning are the two major tasks in machine learning. Supervised learning models are used when the output of all the instances is available, whereas unsupervised learning is applied when we don’t have the “true label”.

the concept of **Semi-Supervised Learning** was introduced. In this type of learning, the algorithm is trained upon a combination of labeled and unlabelled data. Typically, this combination will contain a very small amount of labeled data and a very large amount of unlabelled data.

**Practical applications of Semi-Supervised Learning –**

1. **Speech Analysis:** Since labeling of audio files is a very intensive task, Semi-Supervised learning is a very natural approach to solve this problem.
2. **Internet Content Classification:** Labeling each webpage is an impractical and unfeasible process and thus uses Semi-Supervised learning algorithms. Even the Google search algorithm uses a variant of Semi-Supervised learning to rank the relevance of a webpage for a given query.
3. **Protein Sequence Classification:** Since DNA strands are typically very large in size, the rise of Semi-Supervised learning has been imminent in this field.

<b>In Simple langage:-</b>

Convert unlabel data to label data using machine. human give small amount of data as label to machine automatically detect and labeled to large data set.

### Reinforcement learning

Reinforcement learning is an area of Machine Learning. It is about taking suitable action to maximize reward in a particular situation. It is employed by various software and machines to find the best possible behavior or path it should take in a specific situation. Reinforcement learning differs from supervised learning in a way that in supervised learning the training data has the answer key with it so the model is trained with the correct answer itself whereas in reinforcement learning, there is no answer but the reinforcement agent decides what to do to perform the given task. In the absence of a training dataset, it is bound to learn from its experience.

**Example:** The problem is as follows: We have an agent and a reward, with many hurdles in between. The agent is supposed to find the best possible path to reach the reward. The following problem explains the problem more easily.

**Main points in Reinforcement learning –** 

- Input: The input should be an initial state from which the model will start
- Output: There are many possible outputs as there are a variety of solutions to a particular problem
- Training: The training is based upon the input, The model will return a state and the user will decide to reward or punish the model based on its output.
- The model keeps continues to learn.
- The best solution is decided based on the maximum reward.

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/9d19411d-abd9-46fd-a525-da5fdb8bb82b/Untitled.png)
