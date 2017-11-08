# feedforwardneuralnetwork
Simple Feedforward Neural Network with h-hidden layers

R code found in "feedforward.R"

This is for binary data in both inputs (e.g., which switches are flipped on) and outputs (e.g., whether a machine is running).

I have created 4 activation/smooshing functions, 3 of which have their derivative included (the 4th is almost exclusively used at the 
output layer(s) in practice, and therefore is never derived).

The user can choose the number of hidden layers, the number of neurons in each layer, the learning rate, the number of epochs, and the activation function, and the network will run.

One thing to note is that the output layer is activated linearly, but an activation function could be applied, if desired.

Enjoy! Feel free to comment, improve, or try on other data.

Current projects: 

(i) building a way to optimize the hyperparamters (e.g. the learning rate); 

(ii) building a graphing tool to visualize the network in its final form; 

(iii) refining the program to do a network on continuous data;
