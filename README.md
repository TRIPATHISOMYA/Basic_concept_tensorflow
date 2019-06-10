# Basic_concept_tensorflow
# Computational Graph
It is a graph in which each node corespond to an operation or variable.Variable can feed their values into operations, and operations can feed their results into operation.

The input variable need not to be real number.It can be matrix, vector and so on.
# Tensor
The basic unit to handle tensorflow.A tensor is simply a collection of primitive types.
1=scaler
[1,2,3]=vector
[[1,2,3],[5,6,8]]=matrix

A tensor has static type and dynamic dimensions.You cannot cannot change while evaluating while it dimension can be changed before evaluation.Rank of tensor can be defined as dimensions of tensor.

# There are three main types of tensor
1-tf.variable= It can be changed.It may contain the weights of neural network.The entity ch=an be changed during calculation.
2-tf.constant= the entity are immutable.for example fix values in your model.
3-tf.placeholder= The entity will not changed at each evaluation phase. Usually input of datasets or learning rates are used.


