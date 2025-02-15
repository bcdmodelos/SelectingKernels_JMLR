# SelectingKernels_JMLR

Deep Learning for Kernel Selection in Gaussian Process Regression

GenK

Data Reading: loads a time series from a CSV file.
Kernel Combinations: generates combinations of Gaussian kernels using sum and multiplication operations.
Active Learning: selects a representative subset of the combinations.
Metrics: calculates metrics to evaluate the performance of each kernel in the subset.
File Samples: saves the evaluated combinations in a CSV file in the dataset/dataset_possibilities directory.

BestK

Data Reading: loads and prepares data for model training.
Deep Learning: uses a deep learning model for predicting the R² metric.
File Select Kernel: saves the selected kernel in a .txt file in the dataset/dataset_possibilities directory.

GaussianR

Data Reading: loads a time series and the selected kernel.
Model GPR: defines the GPR model using the selected kernel.
Predictions: makes predictions via GPR for the time series.
Output: displays a graph with the GPR predictions.

Process flow

![Code-Deep-Active](https://github.com/user-attachments/assets/490509a5-1baa-449b-a162-f2045f3bf5cc)





