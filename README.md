### Model: Nonparametric-Regression
Implementation of three nonparametric regression algorithms using univariate regression data set in Python.
### Data set: 
Univariate regression data set, which contains 272 data points about the duration of the eruption and waiting time between eruptions for the Old Faithful geyser in Yellowstone National Park, Wyoming, USA (https://www.yellowstonepark.com/things-to-do/about-old-faithful), in the file named data_set.csv.
### Implementation Steps:
1. Divide the data set into two parts by assigning the first 150 data points to the training set and the remaining 122 data points to the test set.
2. Learn a regressogram by setting the bin width parameter to 0.37 and the origin parameter to 1.5. Draw training data points, test data points, and your regressogram in the same figure.
3. Calculate the root mean squared error (RMSE) of your regressogram for test data points. Regressogram => RMSE is 5.963 when h is 0.37.
4. Learn a running mean smoother by setting the bin width parameter to 0.37. Draw training data points, test data points, and your running mean smoother in the same figure.
5. Calculate the RMSE of your running mean smoother for test data points. Running Mean Smoother => RMSE is 6.089 when h is 0.37.
6. Learn a kernel smoother by setting the bin width parameter to 0.37. Draw training data points, test data points, and your kernel smoother in the same figure.
7. Calculate the RMSE of your kernel smoother for test data points. Kernel Smoother => RMSE is 5.875 when h is 0.37.
