# GANs A.I Art
This repository aims to track the various projects I will be developing in the study of Genrative Adversarial Networks ([GAN](https://en.wikipedia.org/wiki/Generative_adversarial_network)), with the goal of learning the skills to generate [AI-based art](https://aiartists.org/ai-generated-art-tools). 
I will rely mostly on the master in Deep Learning that I am following, run by [Deep Learning Italia Academy](https://elearning.academy-dli.com/) I will also use the tutorials and official guides that can be found in the documentation of [TenforFlow](https://www.tensorflow.org/) and [PyThorch](https://pytorch.org/), as well as follow the course [Complete A.I. Art Generation Course - Beginner 2 MASTER](https://www.udemy.com/course/complete-ai-art-generation/).
 
Technologies based on these networks have made possible the creation of "pieces of art" that have also often been used as [NFTs](https://aimade.art/). 

### Here a picture created by AI!
![imgae_mage_by_AI](https://uploads-ssl.webflow.com/61554cf069663530fc823d21/615892bd22b48c2408114c38_1-min.png)
 
 
## In this repository :

- [Mnist GAN](https://github.com/March-08/GANs-A.I-Art-/blob/main/mnist_GAN.ipynb)
   
  This is my first attempt at creating a GAN. The network is able to generate images similar to those of the classic [MNIST dataset](http://yann.lecun.com/exdb/mnist/), starting from simple noise taken from a random   distribution.
I learned to develop a generator and a discriminator and then combine them in the final GAN. Certainly the training phase is more complicated than the development of a classic network because we must consider that we use two networks that fight against each other and it is essential to freeze the weights of the discriminator when appropriate.

- [Cifar 10 GAN](https://github.com/March-08/GANs-A.I-Art-/blob/main/cifar10_GAN.ipynb)
   
  Project very similar to the previous one, the difference is that the [Cifar 10 dataset](https://www.cs.toronto.edu/~kriz/cifar.html) has been used, so I had to treat RGB images and adapt the code to handle 3 channels.
 
- [Gan on custon dataser](https://github.com/March-08/GANs-A.I-Art-/blob/main/GAN_on_custom_dataset.ipynb)
   
  In this project I used a custom dataset. Using the **download all imges** plugin of google chrome, I was able to create a custom dataset that I had to handle resizing all the images in a shape that could match the Neural Network
