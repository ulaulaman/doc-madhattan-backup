---
title: "Genetics, evolution and Turing's patterns"
datePublished: Thu Dec 27 2012 18:20:00 GMT+0000 (Coordinated Universal Time)
cuid: cm8r87jfq000e09l13cn0hbs5
slug: genetics-evolution-and-turings-patterns

---


posted by @ulaulaman about #Turing #genetics #biology #evolution #morphogenesis reaction-diffusion system

I've just written a post about the [theory of patterns in nature started by **Alan Turing**](http://docmadhattan.fieldofscience.com/2012/06/turing-patterns-in-coats-and-sounds.html), and I describe the _reaction-diffusion system_: in the system there are an activator and an inhibitor molecule of morphogenesis. The dynamics between activator and inhibitor generates tha patterns and we can describe it with the following mathematica relation: \\\[u\_t = d \\Delta u + f (\\gamma, u)\\\] where $u$ is the position of the gene, $u\_t$ the diffusion speed, $d$, $\\gamma$ real constants.  
It's really interesting observe that recently the Turing model about patterns was applied also to the study of the evolution of genes, in particular to study the generation of digit patterning.  
The story start from the [_Hox genes_](http://en.wikipedia.org/wiki/Hox_gene):

> Hox genes are a group of related genes that control the body plan of the embryo along the anterior-posterior (head-tail) axis. After the embryonic segments have formed, the Hox proteins determine the type of segment structures (e.g. legs, antennae, and wings in fruit flies or the different vertebrate ribs in humans) that will form on a given segment. Hox proteins thus confer segmental identity, but do not form the actual segments themselves.

So the team try to mute some of the Hox genes in order to see if the number of digits decrease, but they surprisingly observed that they can add more and more digits in their mutant mouses (they arrived at 14 digits!). And they can explain this behavour with the reaction-diffusion model: in the following picture you can see the experimental results (the first three rows) and the computer simulation that used Turing's model:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743072241262/ab63f0fb-3993-4879-a6d0-0c283cd9cb80.jpeg)

> our data provide evidence that an ancestral Turing-like mechanism patterning fins has been conserved in tetrapods and modified by the implementation of regulatory changes in the evolution of digits. In particular, our data suggest that the equilibrium resulting from the cross-regulation between Shh-Gli3 and distal Hox genes may have led to the stabilization of the pentadactyl state more than 360 million years ago.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743072242675/cdbce94e-464f-4b5d-93e5-914c08f610d4.jpeg)

After this results I'm really excited for the answer to this question: Could Turing's model became the mathematical theory for the biology and life sciences?

* * *

Sheth, R., Marcon, L., Bastida, M., Junco, M., Quintana, L., Dahn, R., Kmita, M., Sharpe, J., & Ros, M. (2012). Hox Genes Regulate Digit Patterning by Controlling the Wavelength of a Turing-Type Mechanism Science, 338 (6113), 1476-1480 DOI: [10.1126/science.1226804](http://dx.doi.org/10.1126/science.1226804)  
Vogel, G. (2012). Turing Pattern Fingered for Digit Formation Science, 338 (6113), 1406-1406 DOI: [10.1126/science.338.6113.1406](http://dx.doi.org/10.1126/science.338.6113.1406)