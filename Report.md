The avarage score I am targeting for this project is to get +13 over 100 consecutive episodes. The schore we are able to achieve is:

Episode 1800	Average Score: 16.36

Episode 1900	Average Score: 16.07

Episode 2000	Average Score: 15.98

The plot is available at DQNPlot.png.

Network Design: The network which is used is three layered network. For the input layer we select 37 input which represent 37 state from the environemtn. The next layer is of size 64
 and the next is also 64 layer. For final layer we get 4 output neuron represent each actions.
 
The network is proper deep neural network but this is not asking for input as image of frames of screen as state.

For improvement we can reduce the number of iteration OR we can reduce the layer complexity because we can see the network is overfitting.
