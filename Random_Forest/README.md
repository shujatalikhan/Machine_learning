# Random Forest 
### Random forest algorithm is a supervised classification algorithm. As the name suggest, this algorithm creates the forest with a number of trees.
## Random Advantages:
 * The same random forest algorithm or the random forest classifier can use for both classification and the regression task.
 * Random forest classifier will handle the missing values
 * When we have more trees in the forest, random forest classifier won’t overfit the model.
 * Can model the random forest classifier for categorical values also.
 ## How Random Forest Algorithm Works.
 

![How-random-forest-algorithm-works](https://user-images.githubusercontent.com/49519213/70375694-24209c00-1901-11ea-96c4-b1a3e32be999.jpg)


<br>Let’s look at the pseudocode for random forest algorithm and later we can walk through each step in the random forest algorithm.

The pseudocode for random forest algorithm can split into two stages.

* Random forest creation pseudocode.
* Pseudocode to perform prediction from the created random forest classifier.
First, let’s begin with random forest creation pseudocode

<br> 1.Random Forest pseudocode:
    Randomly select “k” features from total “m” features.

<br> 2.Where k << m
     Among the “k” features, calculate the node “d” using the best split point.

<br> 3.Split the node into daughter nodes using the best split.

<br> 4.Repeat 1 to 3 steps until “l” number of nodes has been reached.

<br> 5.Build forest by repeating steps 1 to 4 for “n” number times to create “n” number of trees.

The beginning of random forest algorithm starts with randomly selecting “k” features out of total “m” features. In the image, you can observe that we are randomly taking features and observations.

In the next stage, we are using the randomly selected “k” features to find the root node by using the best split approach.

The next stage, We will be calculating the daughter nodes using the same best split approach. Will the first 3 stages until we form the tree with a root node and having the target as the leaf node.

Finally, we repeat 1 to 4 stages to create “n” randomly created trees. This randomly created trees forms the random forest.

## Random forest prediction pseudocode:
To perform prediction using the trained random forest algorithm uses the below pseudocode.

1.Takes the test features and use the rules of each randomly created decision tree to predict the oucome and stores the predicted outcome (target)

2.Calculate the votes for each predicted target.

3.Consider the high voted predicted target as the final prediction from the random forest algorithm.

To perform the prediction using the trained random forest algorithm we need to pass the test features through the rules of each randomly created trees. Suppose let’s say we formed 100 random decision trees to from the random forest.

Each random forest will predict different target (outcome) for the same test feature. Then by considering each predicted target votes will be calculated. Suppose the 100 random decision trees are prediction some 3 unique targets x, y, z then the votes of x is nothing but out of 100 random decision tree how many trees prediction is x.

Likewise for other 2 targets (y, z). If x is getting high votes. Let’s say out of 100 random decision tree 60 trees are predicting the target will be x. Then the final random forest returns the x as the predicted target.

This concept of voting is known as majority voting.

Now let’s look into few applications of random forest algorithm.

## Random forest algorithm applications:
<br>1.Banking
<br>2.Medicine
<br>3.Stock Market
<br>4.E-commerce
