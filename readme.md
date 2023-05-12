# Naive KNN implemetation with Python

* The KNN algorithm, is a non-parametric classification algorithm.
This means that the KNN doesn't have a training phase and uses the data itself to make predictions.
* Desire understand more about how a KNN algorithm works is the motivations behind this project.

# How it works

* Given an input features with unknown label/target, the distance between the input and every observation in the training data across all the features is calculated.
* Then **K** number observations that are nearest (by calculated distance) to the input are calculated.
* The label with the highest count among the K observations is returned label as the prediction for the input.

## Example

```python
    knn = KNN(x_train, y_train, k)
    prediction = knn.predict()
    accuracy = knn.accuracy(x_test, y_test)
```

# Distance Metrics

1. Euclidean
2. Manhattan
3. Minkowski

# Limitations in my Naive KNN

* Speed - My algorithm is not optimized therefore very slow especially for a large dataset.
* Uses the Euclidean distance only.

# Contribution

* Any improvements on the projects are welcome.
