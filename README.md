# VAE models
VAE in Pytorch:
The VAE is realized in Pytorch 0.4.The Varaiable container is replaced by Tensor in this version.

Variational autoencoder (MLP encoder/decoder) and related models 
A good introduction of VAE can be found in Jann's blog: https://jaan.io/what-is-variational-autoencoder-vae-tutorial/.

The VAE in pytorch is inspired by the Dmitry Efimov's VAE Tutorials in Theano:http://efimov-ml.com/vae.html.  

Compared with Theano framework, the realiziation in Pytorch has several advantages: The declaration of class is seperated from the other memeber functions like in C++. The forward function in Pytorch is straight forward and the back-propagation is left to the backward() function with optimizer. The update function in Theano is not necessary. The archiecture of Pytorch model is much clearer than model in Theano.   
