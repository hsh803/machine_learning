# Machine learning for NLP tasks
- Exercises from Machine learning course, Language Technology Mater's program, Uppsala university
- Learning and Understanding different algorithms and methods usded in machine learning focusing on nlp tasks
- Starter codes, instructions from F. Wahlberg

## Exercises

### 1. Fiding decision boundary for classification task (exercise1.py)
- Implement a simple decision tree to manually find decision boudaries (the older artificial intelligence paradigm of finding clever rules)
- Build a class including following functions : predict, score

### 2. Optimazation for linear regression (exercise2.py)
- Build a class for 2D linear regression model using an n-order polynomial (2 and 3 order)
- Implement following functions: predict (Higher order polynomial), score(using L2 loss function), _fit(improvement of random parameter vectors), fit(optimization loop)

### 3. Binary Logistic regression (exercise3.py)
- Develope the code, exercise2.py by adding an activation function (Sigmoid)
- Implement following functions: predict (binary classification 0 or 1), _sigmoid(activation function to pass output through), score(using L2 loss function), _fit(improvement of random parameter vectors), fit(optimization loop)

### 4. Neural classification from scratch (exercise4.py)
- Build a neural network classification model using sigmoid function
- Implement following functions: _soft_predict (predict flattened, concatenated parameters),  _sigmoid(activation function to pass output through), _loss(cross entropy loss), score (accuracy), _fit(improvement of random parameter vectors), fit(optimization loop)

### 5. Clustering with k-means (exercise5.py)
- Build a class implementing k-means clustering algorithm
- k-means clustering algorithm: identify groups of data points iteratively, representing the clusters by their respective centres

## Assignments

### 1. Sentiment classification for film reviews ()
- Implement a classification model for film reviews, labelled as either positive or negative using Scikit-learn
- not using sklearn or any equivalent ML library
- Result: accuracy 85.8% (max iteration: 500)

### 2. Evaluating and Extending an RNN based Part-of-Speech Tagger ()
- Refactor the starter code to build a model for PoS tagging using RNN layers (GPU or LSTM, option to use a bi-directional RNN layer) and mini-batch training
- Evaluate the model on a number of sources in different languages (Korean, Engligh, Swedish)
- Data : Universal dependencies (UD)
- Result: With 64 hidden dimension, test accuracy in English, Korean and Swedish are 95%, 61%, 75% respectively while with 128 hidden dimension 95%, 72% and 77%
: Test accuracy of both LSTM and GRU without using bidirectional option are 95% and with using bidirectional option are 97%. (Only English taggning)

### 3. Sentiment classification for film reviews using pre-trained transformer language model ()
- Develop the model implemented for assignment 1 (Sentiment classification for film reviews) by using a transformer-based language model running in g a neural network. (Use Huggingface and bigger dataset)
- Result: Test accuracy 69.9%
