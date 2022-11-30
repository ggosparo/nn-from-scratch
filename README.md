[**Please read the blog post that goes with this code!**](http://www.wildml.com/2015/09/implementing-a-neural-network-from-scratch/)


### iPython notebook setup

```bash
# Create and activate new virtual environment (optional)
virtualenv venv
source venv/bin/activate
# Install requirements
pip install -r requirements.txt
# Start the notebook server
jupyter notebook
```

### Exercises
Here are some things you can try to become more familiar with the code:

1- Instead of batch gradient descent, use minibatch gradient descent ([more info](http://cs231n.github.io/optimization-1/#gd)) to train the network. Minibatch gradient descent typically performs better in practice.

2- We used a fixed learning rate epsilonϵ for gradient descent. Implement an annealing schedule for the gradient descent learning rate ([more info](http://cs231n.github.io/neural-networks-3/#anneal)).

3- We used a tanh activation function for our hidden layer. Experiment with other activation functions (some are mentioned above). Note that changing the activation function also means changing the backpropagation derivative.

4- Extend the network from two to three classes. You will need to generate an appropriate dataset for this.

5- Extend the network to four layers. Experiment with the layer size. Adding another hidden layer means you will need to adjust both the forward propagation as well as the backpropagation code.

