# Fashion-Generator
A Conditional Generative Adversarial Network trained on 10 classes of fashion mnist dataset that could generate new fashion sense such as clothing designs and accessories based on the given class. 
## OVERVIEW
Generative Adversarial Networks, or GANs, are an architecture for training generative models, such as deep convolutional neural networks for generating images.
The conditional generative adversarial network, or cGAN for short, is a type of GAN that involves the conditional generation of images by a generator model. Image generation can be conditional on a class label, if available, allowing the targeted generated of images of a given type.
## ARCHITECTURE
![alt text](https://github.com/25abhishek/Fashion-Generator/blob/master/Images/gans_architecture.png)
Figure above depicts the generator model in full with the point in latent space and class label as input, and the connection of the output of the generator and the same class label as input to the discriminator model (last box at the bottom of the plot) and the output of a single class label classification of real or fake.
## RESULTS
![alt text](https://github.com/25abhishek/Fashion-Generator/blob/master/Images/gans%20out.png)
