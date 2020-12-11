# Machine-Learning-
GAN model vs VAE model 
I compared the effciency of GAN and VAE model 
In VAE model, I construct 2 convolutional layers in the encoder network, and 2 convolutional layers in the decoder network. Each convolutional layer is followed by a batch normalization layer and a ReLU activation layer, training data for 200 epochs.

In GAN model, generator will contain 3 layers, using ReLU activation function for previous 2 layers and using tanh activation function for last layer. For the discriminator, it consists 3 layers with ReLU as activation function, using Sigmoid activation function for last layer, training data for 200 epochs
