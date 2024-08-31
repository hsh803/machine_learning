# machine_learning
- Exercises from Machine learning course, Language Technology Mater's program, Uppsala university
- Learning and Understanding different algorithms and methods usded in machine learning focusing on nlp tasks
- Starter codes, instructions from F. Wahlberg

## 1. Fiding decision boundary for classification task (exercise1.py)
- Implement a simple decision tree to manually find decision boudaries (the older artificial intelligence paradigm of finding clever rules)
- Build a class including following functions : predict, score

## 2. Optimazation for linear regression (exercise2.py)
- Build a class for 2D linear regression model using an n-order polynomial (2 and 3 order)
- Implement following functions: predict (Higher order polynomial), score(using L2 loss function), _fit(improvement of random parameter vectors), fit(optimization loop)

## 3. Binary Logistic regression (exercise3.py)
- Develope the code, exercise2.py by adding an activation function (Sigmoid)
- Implement following functions: predict (binary classification 0 or 1), _sigmoid(activation function to pass output through), score(using L2 loss function), _fit(improvement of random parameter vectors), fit(optimization loop)

## 4. Neural classification from scratch (exercise4.py)
- Build a neural network classification model using sigmoid function
- Implement following functions: _soft_predict (predict flattened, concatenated parameters),  _sigmoid(activation function to pass output through), _loss(cross entropy loss), score (accuracy), _fit(improvement of random parameter vectors), fit(optimization loop)

## 5. Clustering with k-means (exercise5.py)
- Build a class implementing k-means clustering algorithm
- k-means clustering algorithm: identify groups of data points iteratively, representing the clusters by their respective centres
