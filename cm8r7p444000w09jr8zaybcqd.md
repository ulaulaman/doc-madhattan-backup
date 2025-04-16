---
title: "Neural networks and astronomy"
seoTitle: "Exploring Neural Networks in Astronomy"
seoDescription: "Explore the role of neural networks in astronomy, from image analysis to redshift calculations, with diverse applications and examples"
datePublished: Sun Nov 24 2013 20:20:00 GMT+0000 (Coordinated Universal Time)
cuid: cm8r7p444000w09jr8zaybcqd
slug: neural-networks-and-astronomy
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1744836477557/09ec08e7-dddc-43db-9f2d-96d98ca25f00.jpeg
tags: neural-networks, astronomy

---

*This post was republished on Mathematics in Europe on 28/02/2017 ([archived version](https://web.archive.org/web/20220523235259/http://mathematics-in-europe.eu/?p=801).*

I published this post some years ago ([archived version](https://web.archive.org/web/20101129170739/http://sciencebackstage.blogosfere.it/2010/10/neural-networks-and-astronomy.html)), but for unilateral decision of the online publisher, it is deleted, so I decide to recover it.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743071378482/4abde75b-cfdd-481c-a936-fc1c090625f9.jpeg align="center")

Neural network is one of the most powered method to analize data. It can be use in most research subject, for example in astronomy: in this case, we can use NNs to examine astronomical images or also the red shift effect. For example, in 2003 **Jorge Núñez** (Universitad de Barcelona) and **Jorge Llacer** (EC Engineering Consultants LLC) published a paper<sup>(1)</sup> in which they describe the develop of an algorithm to study *astronomical image segmentation that uses a self-organizing neural network as basis*. In their work, the scientists examine the separation between some stars and also a Saturn's image: the alghoritm seems quite robust against noise and fragmentation.  
In the same year, a group of italian astronomers published a review of the models used in astronomy and examined some data used by **AstroNeural** collaboration. Finally in 2004 a collaboration between researchers in Italy, Germany and France perform an application of NNs to redshift calculations<sup>(3)</sup>.  
Now you can quest: *What is a neural network?*  
Simply is a system of *node* and *link*. In the structure we can eventually distinguished between different layers, and every layers are fully connected. Such networks are usually called *Multilayer Perceptron* NN, and the interaction between every node is modelled by the following funcition

$$f(x) = k \sum_i w_i g_i(x)$$

where \\(k\\) is some predefined function, \\(g_i\\) is a vector of functions.  
A more simple model is

$$n_j = h \sum_i w_{ij} z_i$$

is the \\(j\\)\-th node, \\(h\\) is a constant, \\(w_{ij}\\) the weights of the link, \\(z_i\\) the previous node.  
There is also the self-organizing maps, in which every node, or neurons, are in competition with each other:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743071379736/c261ddf0-cd42-48b3-b571-18562f4b20a2.jpeg align="center")

It's possible implement NNs with fuzzy logic and perform image segmentation, object detection, noise identification (for example in detection of gravitational waves), estimation of redshifts. The great advantage using NNs in astronomy is, however, to perform complex calculations with usually alghoritms.  
For example, we can see the plots in Vanzella's et al. paper<sup>(3)</sup>. In the work, astronomers used a *Multilayer Perceptron* NN, using real data from Hubble Deep Field North dataset.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743071380981/834324bd-d42f-4e81-9489-f4836822d8ce.jpeg align="center")

This is the first comparison between

> spectroscopic redshift in the HDF-S and the neural redshift using the colors as an input pattern. The training has been done on the HDF-N spectroscopic sample, the estimation of the redshift for each object is the median of 100 predictions and the error bars represent 1- interval. Open circles represent objects with unreliable photometry and triangles are objects with uncertain spectroscopic redshift.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743071382241/2d2318c8-01db-4497-aff0-bce87f76513d.jpeg align="center")

And here there is a comparison after adding informations.  
One of the most important tool in NNs is the ability of these type of networks to learn from data.  
The last plot that I propose you is the *redshift distribution of the spectroscopic sample*:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743071383182/7f1fa1cd-37b7-440c-acdf-134deb7f7c21.jpeg align="center")

And now some tutorials: [**How to build a brain with neural networks**](http://io9.com/5647277/how-to-build-a-brain-with-neural-networks) and, for all geek, **Evolving Neural Networks with SharpNEAT**: [part 1](http://www.nashcoding.com/2010/07/17/tutorial-evolving-neural-networks-with-sharpneat-2-part-1/) and [part 2](http://www.nashcoding.com/?p=177). And, in conclusion, read the [following post about NNs and tea leaves](http://www.science20.com/news_articles/artificial_neural_network_can_distinguish_between_tea_leaves).  
Enjoy!

---

(1) Núñez J. & Llacer J. (2003). Astronomical image segmentation by self-organizing neural networks and wavelets, Neural Networks, 16 (3-4) 411-417. DOI: [10.1016/S0893-6080(03)00011-X](http://dx.doi.org/10.1016%2FS0893-6080%2803%2900011-X)  
(2) Tagliaferri R., Longo G., Milano L., Acernese F., Barone F., Ciaramella A., Rosa R.D., Donalek C., Eleuteri A., Raiconi G. & Sessa S. (2003). Neural neZtworks in astronomy, Neural Networks, 16 (3-4) 297-319. DOI: [10.1016/S0893-6080(03)00028-5](http://dx.doi.org/10.1016%2FS0893-6080%2803%2900028-5) ([pdf](http://people.na.infn.it/~astroneural/documents/nnet_in_astronomy.pdf))  
(3) Vanzella E., Cristiani S., Fontana A., Nonino M., Arnouts S., Giallongo E., Grazian A., Fasano G., Popesso P. & Saracco P. & (2004). Photometric redshifts with the Multilayer Perceptron Neural Network: Application to the HDF-S and SDSS, Astronomy and Astrophysics, 423 (2) 761-776. DOI: [10.1051/0004-6361:20040176](http://dx.doi.org/10.1051%2F0004-6361%3A20040176) ([arXiv](http://arxiv.org/abs/astro-ph/0312064))