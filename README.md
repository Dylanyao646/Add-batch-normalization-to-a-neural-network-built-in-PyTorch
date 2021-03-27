# Add-batch-normalization-to-a-neural-network-built-in-PyTorch
Batch Normalization in PyTorch
This section of the notebook shows you one way to add batch normalization to a neural network built in PyTorch.

The following cells import the packages we need in the notebook and load the MNIST dataset to use in our experiments.

Training and Evaluation Mode
Setting a model to evaluation mode is important for models with batch normalization layers!

Training mode means that the batch normalization layers will use batch statistics to calculate the batch norm.
Evaluation mode, on the other hand, uses the estimated population mean and variance from the entire training set, which should give us increased performance on this test data!
