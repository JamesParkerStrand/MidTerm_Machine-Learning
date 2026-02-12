# Problem 3

## 1. There is a lot around us that's driven by some form of machine learning (ML), but not all. Give an example of a system/service that does not use ML, and the one that does. Use this contrast to explain ML in your own words. [4 points]
```
Machine learning, in a more general sense, is a process of taking data, running the data through an algorithm to 
generalize a trend, and predict what the potential classification of new data points would be. ML at large is a 
statistical analysis tool. ML is mostly used by data scientists to gain a general understanding of how their data 
behaves. Netflix is a great example of ML being used. Netflix uses ML to get a general sense of what content you are 
most interested in, and uses that data to send you new movies or TV shows that you may like. An example, albeit a 
silly example, of a service that doesn't use ML are cashiers. Their job is to know exactly what you are buying so 
that they can charge you precisely for the items you are trying to purchase. 

```

## 2. When/why would you use unsupervised learning? [1 point]
```
You would use unsupervised learning when you have data that don't have labels and you wan the model to discover 
structures on its own. Unsupervised learning is great for when you are wanting to see how data are/ aren't related to 
each other, find hidden patters or associations between the data points, or to group similar data points together, 
in order to summarize the data.
```


## 3. Many of the ML models are represented using parameters. Use this idea to define ML. [2 points]
```
In a ML learning model, when you fit the data frame into the model, what you get back are the parameters. The parameters 
are the adjusted weights for each feature in the data frame. When you apply the parameter to the data, you get back a 
probability for each row (if its a binary class) or a probability for each class if there are multiple classes. You 
would then use this data to predict the class based on specific threshold metric you set.
```

## 4. When would you use batch gradient descent (BGD) and when would you use stochastic gradient descent (SGD)? Why? [4 points]
```
You would use batch gradient descent if the size of the data set isn't exceptionally large. Its typically less noisy 
and more accurate, but it is much slower since I goes through all of the datapoints. You would use stochastic gradient 
decent when you have an exceptionally large dataset and you would rather not wait several days to process the weights 
for the dataset, but the trade off is, the result often adds more noise. 
```

## 5. Decision tree is a greedy algorithm. List one advantage and one disadvantage of being greedy here. [2 points]
```
The advantage is it is often a quicker solution for smaller datasets, and the algorithm is scalable since the tree 
chooses the best split at each node locally, without searching all possible trees. However, there is a tendency for 
overfitting, which makes it a more fragile solution for machine learning and often requires you to prune the leaves to 
prevent overfitting.
```