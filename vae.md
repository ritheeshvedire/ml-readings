## Introductory

* [The Variational Auto-encoder](https://ermongroup.github.io/cs228-notes/extras/vae/)
* [VAE Explained](http://anotherdatum.com/vae.html) - Yoel Zeldes
* [VAE Explained in detail](http://anotherdatum.com/vae2.html) - Yoel Zeldes - this and the previous one are very good introductions and starting points to read
* [VAE Intuition and Implementation](https://wiseodd.github.io/techblog/2016/12/10/variational-autoencoder/)
* [From Auto Encoder to beta-VAE](https://lilianweng.github.io/lil-log/2018/08/12/from-autoencoder-to-beta-vae.html) - excellent explanation in the section on VAE especially the math part
* [A Beginner's Guide to Variational Methods: Mean-Field Approximation](https://blog.evjang.com/2016/08/variational-bayes.html) - an introductory post but contains a great explanation of *why we should use reversed KL as opposed to forward KL* for minimizing the Loss Function of a VAE
* [Variational Autoencoders](https://ryanloweift6266.wordpress.com/2016/02/28/variational-autoencoders/) - This blog post is a usual introduction to the subject. But the best part I liked is the section *Problem Setup*, which is very intuitive.
* [Notes on Variational Autoencoders](http://www.1-4-5.net/~dmm/ml/vae.pdf) - Very detailed introduction.

## Original

* [Autoencoding Variational Bayes](https://arxiv.org/abs/1312.6114) - Kingma and Welling
* [Variational Lossy Autoencoder](https://arxiv.org/abs/1611.02731) - Xi Chen, Diederik P. Kingma, Tim Salimans, Yan Duan, Prafulla Dhariwal, John Schulman, Ilya Sutskever, Pieter Abbeel
* [Neural Discrete Representation Learning](https://arxiv.org/abs/1711.00937) - Aaron van den Oord, Oriol Vinyals, Koray Kavukcuoglu
* [Generating Diverse High-Fidelity Images with VQ-VAE-2](https://arxiv.org/abs/1906.00446) - Ali Razavi, Aaron van den Oord, Oriol Vinyals

## Tutorials

* [Variational AutoEncoders and Extensions](http://dpkingma.com/wordpress/wp-content/uploads/2015/12/talk_nips_workshop_2015.pdf) - NIPS 2015 tutorial by Kingma and Welling
* [Tutorial on Variational Encoders](https://arxiv.org/abs/1606.05908) - Carl Doersch

## Reparamaterization Trick for VAEs

* [Useful StackExchange thread](https://stats.stackexchange.com/questions/199605/how-does-the-reparameterization-trick-for-vaes-work-and-why-is-it-important)
* [The Reparameterization Trick](http://gregorygundersen.com/blog/2018/04/29/reparameterization/) - an excellent blog post that really explains why we need the trick and what it actually means to say that *we cannot backpropagate through a random node*

## Background Readings

* [Predicting prob distributions using NNs](https://engineering.taboola.com/predicting-probability-distributions/) - discusses an approach to modeling probability distributions using NNs. Uses the Mixed Density Model of Bishop.
* [Neural variational inference and learning in belief networks](https://www.cs.toronto.edu/~amnih/papers/nvil.pdf) -  Mnih and Gregor
* [Transformations and expectations of random variables](http://www.its.caltech.edu/~mshum/stats/lect2.pdf)
* [Log Derivative Trick](http://blog.shakirm.com/2015/11/machine-learning-trick-of-the-day-5-log-derivative-trick/) by Shakir - a very useful trick used in section 2.2 of the original VAE paper (Autoencoding Variational Bayes). This blog post has a great explanation of this trick along with other places where it is used.
* [Notes on Multivariate Gaussian](http://cs229.stanford.edu/section/gaussians.pdf)
* [Variational Bayesian Inference with Stochastic Search](https://arxiv.org/abs/1206.6430) - John Paisley (UC Berkeley), David Blei (Princeton University), Michael Jordan (UC Berkeley)
