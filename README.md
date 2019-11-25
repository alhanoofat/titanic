<h1>Predict survival on the Titanic</h1>

<h3> Problem Statement:</h3>
Titanic is a widely known disaster. However, it can be useful to learn from disasters. In this project, we acquired the dataset of the passengers of Titanic. It contains 10 features about approximately 1300 passengers; their name, ticket class, sex, age, ticket number, number of children and parents, number of siblings, ticket fare, cabin number, port of embarkation, and whether or not they survived.
We wanted to predict whether or not a specific passenger has survived the tragedy. Therefore, We trained some classification models to predict that. <br> <br>


Here is the competition that we joined:
[Titanic](https://www.kaggle.com/c/titanic/overview)


A quick overview on two dataset's features, keys and Description


| Feature            | Key   |Description |
|--------------------|-------|------------|
|survival|0 = No, 1 = Yes|Survival|
|pclass|1 = 1st, 2 = 2nd, 3 = 3rd|Ticket class|
|sex| |Sex|
|Age|	|Age in years|	
|sibsp| |# of siblings / spouses aboard the Titanic|	
|parch|	|# of parents / children aboard the Titanic|	
|ticket|	|Ticket number|	
|fare|	|Passenger fare|	
|cabin|	|Cabin number|	
|embarked|C = Cherbourg, Q = Queenstown, S = Southampton|Port of Embarkation|


<h4>Here is our notebook on kaggle </h4><br>
<a href="https://www.kaggle.com/shehanaaljaloud/project2-part2/edit/run/22725510">Predict survival on the Titanic</a> <br>
Our Kaggle score we got for the best model is : 0.76555

<h3>Conclusion:</h3>
 In this project, we created classification models; LogisticRegression, ExtraTreesClassifier, KNeighborsClassifier, RandomForestClassifier and DecisionTreeClassifier to predict whether or not a Titanic passenger has survived. We tested all models by submitting them individually in Kaggle. The best score was for RandomForestClassifier and DecisionTreeClassifier, in which we got a score of 0.76555.
