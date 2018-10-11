# CIFAR Classification Model
The model which I trained achieved ~86% accuracy.
**The model can be trained using google's TPU hardware but few adjustments are needed:
1. If you are using google colab go to the 'runtime' tab and select 'change runtime type' change the type of the hardware to TPU.**

#### further work:
1. Apply usage of Batchnormalization in order to achieve faster convergence of the loss function.
2. Use of GridSearch to fine tune the hyperparameters such as: batch_size, dropout rate etc.
3. Define an early stopping callback.
4. Create deeper fully connected network at the edge of the model.

