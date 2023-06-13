# Variations-Of-SoftMax
The softmax function is a commonly used activation function in neural networks,
particularly for classification tasks. It takes in a vector of K real numbers and outputs a
probability distribution of K possible outcomes. This function is useful because it
allows us to map probabilistic distributions using neural networks.
However, the softmax function can become computationally expensive when the
number of classes, denoted as C, is large. This is because the denominator of the
softmax function involves a summation over all C classes, taking O(C) time. This can
be problematic as the number of classes increases, as it can significantly slow down
the training and evaluation of the model.
Overall, this experiment will provide insights into the trade-offs between different
softmax implementations in neural networks, particularly in the context of classification
tasks with many classes. By understanding the impact of softmax implementations on
model performance and training time, we can make more informed decisions when
designing and training neural networks for classification tasks.
This is useful for many tasks and is used extensively in classification tasks
