# Naive-Bayes-Classifier
Implement **naive bayes classifier** to predict *subject of news*.<br />
Note that you should extract `Dataset.zip` file at first and then run the code file.<br />
To solve this problem, use the **bag of words** model. In this model, each word is considered independent of its position, and the number of repetitions of each word in each category is considered as a feature. <br /> <br />
In Naive Bayes, we consider the categories as the father of all features and assume that its children are independent from each other on the condition of knowing the father. So if we consider the words used in the news as `X` or ( $x_{1}$, $x_{2}$, $x_{3}$, ... ), we should get the following probability for different categories(`c` is a category) :<br />
```math
P(c|X) = P(c) * P(x_{1}|c) * P(x_{2}|c) * P(x_{3}|c) * ...
```
You can see complete description in `report` file.
