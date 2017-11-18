# Linear-regression
Linear regression of California housing datasets from sklearn

**1. Data pre-processing**
- Imort california_housing data from sklearn.datasets.
- Use 90% datasets for training and 10% datasets for testing.
- Use mean +- 1.5 * Standard Deviation to find the outlier of training data.
- We also use scikit learn LocalOutlierFactor to find the outlier of training data.
- Remove outlier in the datasets. (Can reduce error rate)

**2. Weight calculation**
- We use the formula below to calculate weight!
![](https://i.imgur.com/MzEfrV3.png)

**3. Computation**
- Initialize variables.
- Use **weight * X_test** to get predicted **Y_test**.
- Use **mean(abs(y–ŷ)/y)** to get error rate. (ŷ is the predicted value)
- Show graph of tensorflow computation flow.

