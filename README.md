## Brief Introduction to Artificial Neural Networks

The field of Artificial Intelligence which deals with intelligence demonstrated by computer systems, has seen major growth in the last few years and many believe that this growth is due to advancements in **Artificial Neural Networks** (or ANN’s for short). ANN’s can be thought of as computational frameworks, loosely inspired by the human cognitive function and biological neural networks. 

In this post, I will provide a brief and simple introduction to ANN’s and hopefully when you finish reading this you will have a high-level understanding of how and why they are used.

### Connection to Nature: Biological Neural Networks

Neurons are the fundamental units of the brain and nervous systems. They are a specialized cell whose function is to transmit information from one part to the other. Neurons “connect” with other neurons to form networks, and communicate with each other through a process of electrochemical signaling. These neural networks act as the basis for human cognitive function and allows us to process and handle information.

![Neuron Structure](neuron.png)

An individual neuron receives information in its Dendrites (in the form of chemical signals), process it and then propagates that information at the Axon Terminals. Note that there are many different types of neurons so their structure and function can vary. If they receive the necessary amount of excitatory input, the neuron “fires” and transmits a signal through the network. 

### Delving deeper into ANN's

As its biological counterpart, ANN’s consist of a collection of processing units called artificial neurons which receive multiple inputs and have one output. These connections are weighted, which basically means that they carry a value. Each artificial neuron performs a calculation on its inputs, which is then multiplied by the weight of its output connection. The calculation that each neuron performs is a function of the inputs and is called the **transfer function**. The network as a whole is then able to detect patterns and perform complex computations. 

However, to be able to perform a calculation, we have to show it how: 

This can be done by providing the network with examples. This process is called **supervised learning**, where the ANN is given a set of example inputs, as well as what the correct output should be for each input. The artificial neural networks then adjust the weights and firing rules (the calculation at each unit) of artificial neurons, calculate the probability of each output and, if the input set is large enough, become experts in the task on hand. In other words they strengthen the connections that lead to success and weaken those that lead to failure. 

Artificial Neural Networks usually tackle two types of problems, **classification** problems which are all about predicting the correct label for an input, and **regression** problems which deals with computing a value.


