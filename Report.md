The avarage score I am targeting for this project is to get +13 over 100 consecutive episodes. The schore we are able to achieve is:

Episode 1800	Average Score: 16.36

Episode 1900	Average Score: 16.07

Episode 2000	Average Score: 15.98

The plot is available at DQNPlot.png.

Network Design: The network which is used is three layered network. For the input layer we select 37 input which represent 37 state from the environemtn. The next layer is of size 64
 and the next is also 64 layer. For final layer we get 4 output neuron represent each actions.
 
The network is proper deep neural network but this is not asking for input as image of frames of screen as state.

For improvement we can reduce the number of iteration OR we can reduce the layer complexity because we can see the network is overfitting.

## Possible Imporvement:
### Primary issues:
* Final episodes are nearly equal but due to randomness and according to plot improvement in episodes could increase the accurace. 
* Further more if we try to reduce the randomness using regularization it will reduce the randomenss and hence the accuracy.
* If we can increase the examples for learning we can improve the model accuracy.

### Possible Improvement through model improvement: 
The Rainbow model experimented by researchers from Deep Mind can give more accurate result for the model better for this test case. The model are:
* Double DQN (DDQN)
* Prioritized experience replay
* Dueling DQN
* A3C
* Distributional DQN
* Noisy DQN
