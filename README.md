# Self Driving Car


> People are so bad at driving car, that Computer don't have to be that good.

We built our own self-driving car. This is a modelled version of a car (so it won't be driving on the streets of real cities) but still it will learn how to drive itself. The key word here is learn, because the car will not be given any rules on how to operate in the environment before hand.

It will have to figure everything out on its own. To achieve this, we will be using Deep Q-Learning. 

### About Deep Q-learning
Deep Q-Learning is the result of combining Q-Learning with an Artificial Neural Network.

The states of the environment are encoded by a vector which is passed as input into the Neural Network. Then the Neural Network will try to predict which action should be played, by returning as outputs a Q-value for each of the possible actions. Eventually, the best action to play is chosen by either taking the one that has the highest Q-value, or by overlaying a Softmax function.

**Here is the link of analysis :**
[Click Here] (https://goo.gl/STfu5b)

<a href="http://www.youtube.com/watch?feature=player_embedded&v=EaY5QiZwSP4" target="_blank"><img src="http://img.youtube.com/vi/EaY5QiZwSP4/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>


