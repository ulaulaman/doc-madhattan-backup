---
title: "The expansion entropy"
datePublished: Wed Sep 09 2015 19:34:00 GMT+0000 (Coordinated Universal Time)
cuid: cm8r7fsfy000u09jyb70md705
slug: the-expansion-entropy

---


[![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743070948209/9c0a8721-fcb6-4627-a296-bffa4ebf2514.jpeg)](http://arxsec.com/post/121628590722/entropy-and-the-art-of-secure-software)

In simply: the _expansion entropy_ is a new way to calculate the entropy of a given system.  

> Expansion entropy uses the linearization of the dynamical system and a notion of a volume on its state space

From a mathematical point of view, we can describe the evolution of a given system $M$ using a map (a function, an application) that acts in the same system $M$: $f: M \\rightarrow M$. Every maps $f$ are depending on time, that it could be discrete or continuous.  
Using these maps we can construct the so called _derivative matrix_ $Df$, that is constituted by the partial derivatives of $f$ respect the coordinates of the $n$-space $M$.  
At this point with $Df$, you can calculate the function $G(Df)$, that is

> a _local_ volume growth ratio for the (typically nonlinear) $f$.

or in other words a way to measure the growth of $M$ in time.  
Now $G(Df)$ will be integrated on the whole $n$-space and renormalized on the volume, and the new quantity $E(f, S)$, will be used to define the expansion entropy: \\\[H\_0 (f, S) = \\lim\_{t' \\rightarrow \\infty} \\frac{\\ln E\_{t', t} (f, S)}{t'-t}\\\] where $t'$ is the final time, $t$ is the initial time.  
In this way the expansion entropy measure the disorder of the system, like the topological entropy, but using the expansion entropy we can define the chaos when $H\_0 > 0$.

* * *

Hunt, B., & Ott, E. (2015). Defining chaos Chaos: An Interdisciplinary Journal of Nonlinear Science, 25 (9) DOI: [10.1063/1.4922973](http://dx.doi.org/10.1063/1.4922973) ([arXiv](http://arxiv.org/abs/1501.07896))