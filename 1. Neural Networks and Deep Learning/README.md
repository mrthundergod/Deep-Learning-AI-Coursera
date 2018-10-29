## What is an Artificial Neural Network?
Artificial Neural Networks or ANNs or Connectionist systems are interconnected nodes similar to the vast netwrok of neurons in the human brain. It is a processing paradigm inspired off the biological network of the brain. The NN isn't an algorithim but, a framework for many different machine learning algorithms to work together and process complex data inputs.

An ANN is based on a collection of connected units or nodes called artificial neurons. Each connection, like the synapses in a biological brain, can transmit a signal from one artificial neuron to another. An artificial neuron that receives a signal can process it and then signal additional artificial neurons connected to it.

Let's take an example of a predicting house prices using a NN.

![Image of Example](https://github.com/mrthundergod/images-repo/blob/master/11.PNG)

Above shows the simplest NN with a single neuron, one input and one output. As per the example the input is the size of a house and the output is the price. The data is plotted on a graph as shown above and the NN works to draw or fit a curve so that it correlated with future values. The shape of the curve in the graph is made using a fuction called ReLU. 

ReLU replaced sigmoid curves as the standard used, because in sigmoid, there are places where the slope of the curve is zero which results in making the gradient descent and in effect the NN slow.

A neural network is essentially a whole collection of above neurons placed one above the other. Instead of a single input, there are multiple inputs(x1, x2, x3, x4) which, constitute an 'Input Layer'. These features combine to form different features in the middle layer called a 'Hodden Layer'. Things like the size of the house and no. of bedrooms constitute a new feature called Family Size. Similarly there may form other features like Walkability and School Quality. 
![Neural Network](https://github.com/mrthundergod/images-repo/blob/master/12.PNG)

