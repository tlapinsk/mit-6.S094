# MIT 6.S094
Huge shoutout to MIT and Lex Fridman for offering the [self-driving car course](http://selfdrivingcars.mit.edu/) to the public. After watching the first two MIT 6.S094 lectures ([here](https://www.youtube.com/watch?v=1L0TKZQcUtA&feature=youtu.be) and [here](https://www.youtube.com/watch?v=QDzM8r3WgBw&feature=youtu.be)), it was time to kickoff the first project: [deeptrafficjs](http://selfdrivingcars.mit.edu/deeptrafficjs/).

## DeepTrafficJS
Big thanks to [Anton Penchenko](https://github.com/parilo/DeepTraffic-solution) for posting his code on Github. My code closely resembles his final solution, so you can call this essentially a replication of his results.

The main goal for me going through this project was to learn the basics of training neural networks, and I would say this was definitely achieved (even through replication of results). 

My final code was able to hit 74.29mph, which isn't too far off the current top score of 76.29mph. There are definitely some improvements that can be made in my code:
- Increase the number of `trainIterations`
- Play around with the number of hidden layers and number of neurons.

Other students had a variety of total hidden layers and number of neurons that yielded similar results to mine. It would be fun to continue optimizing until I hit ~76mph.

### Helpful Resources
1. [Hidden Layer Explanation](https://stats.stackexchange.com/questions/63152/what-does-the-hidden-layer-in-a-neural-network-compute) 
2. [Martin Riedmiller's Tips & Tricks](https://pdfs.semanticscholar.org/03fd/37aba0c900e232550cf8cc7f66e9465fae94.pdf) 
3. [Activation Functions](https://medium.com/towards-data-science/activation-functions-and-its-types-which-is-better-a9a5310cc8f)
4. [dhanush987's code](https://github.com/dhanush987/DeepTraffic) 
5. [jasonsalas's code](https://github.com/jasonsalas/deeptraffic) 

## DeepTeslaJS
The DeepTesla project was pretty straight forward and another great introduction to concepts such as layering, pooling, etc. I didn't find the final model I created doing a great job at predicting the steering angle, but I don't believe that was the point to the project. It was more to get you familiar with the basics of layering convolutional neural networks and the steps needed to downsize the output of a CNN before sending it through the next layer. In addition, you get to see what happens within each layer, which really helps you understand what each layer is doing as it learns.

I may mess around with the layering a bit more to see if I can attain better results, but we'll see. Check out the resources below, which helped me immensely to grasp some of basic concepts of neural networks.

### Helpful Resources
1. [K Nearest Neighbor](https://www.youtube.com/watch?v=UqYde-LULfs) 
2. [Intro to Gradient Descent](https://spin.atomicobject.com/2014/06/24/gradient-descent-linear-regression/) 