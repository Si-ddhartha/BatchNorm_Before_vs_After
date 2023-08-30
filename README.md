# BatchNorm_Before_vs_After

In deep learning, enhancing the training and convergence of deep neural networks has been a long-standing challenge. One technique that has demonstrated remarkable effectiveness in stabilizing and accelerating the training process is Batch Normalization. There are two distinct approaches to integrating Batch Normalization within a neural network architecture - before and after the activation functions in a neural network.

I used TensorFlow for the implementation of these two strategies.

After my implementation, I found out that the disparity in performance between the two implementations is minimal. Following training for 10 epochs, the "after activation" approach achieves a training accuracy of 0.8917, while the "before activation" approach achieves a slightly lower training accuracy of 0.8812. Similarly, in terms of test accuracy, the "after activation" strategy achieves a score of 0.7100, while the "before activation" strategy scores slightly lower at 0.7049.

The observations may differ due to various factors including the number of training epochs, the complexity of the dataset, and the architecture of the neural network.
