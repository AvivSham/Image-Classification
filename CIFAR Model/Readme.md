# CIFAR Classification Model
The model which I trained achieved ~86% accuracy.

**There is also a preparation for model training by using google's TPU hardware but few adjustments are needed**

#### further work:
1. Apply usage of Batchnormalization in order to achieve faster convergence of the loss function.
2. Use of GridSearch to fine tune the hyperparameters such as: batch_size, dropout rate etc.
3. Define an early stopping callback.
4. Create deeper fully connected network at the edge of the model.

