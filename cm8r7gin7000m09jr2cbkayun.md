---
title: "Balloon, art and mathematics"
datePublished: Tue Jun 30 2015 16:52:00 GMT+0000 (Coordinated Universal Time)
cuid: cm8r7gin7000m09jr2cbkayun
slug: balloon-art-and-mathematics

---


After (or before?) @StartsWithABang's balloon animals' post?

A couple of week ago [**Ethan Siegel** published a post about ballon animals](https://medium.com/starts-with-a-bang/weekend-diversion-a-new-twist-on-the-art-of-balloon-animals-64d0a73f8c18), so I decide to repost [an old piece that I wrote in 2011](http://dropseaofulaula.blogspot.it/2011/03/palloncini-arte-e-matematica.html) for my italian blog: the english version is lost, but it is magically reposted here!

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743070975818/925bca30-e2fd-4e09-89dc-d4a33d2cbadd.jpeg)  
Two one-balloon constructions and their associated graphs

I recently discovered this interesting site, [vihart](http://vihart.com/). In the site there are some interesting paper and today I want to write something about [_Computational Balloon Twisting: The Theory of Balloon Polyhedra_](http://vihart.com/papers/balloon/) by [**Erik**](http://erikdemaine.org/) and [**Martin Demaine**](http://martindemaine.org/) and **Vi Hart** (the paper was [reported in 2010 by the Improbable Research blog](http://www.improbable.com/2010/08/03/mathematical-balloon-twisting/)).  
The interest about ballon twisting was motivated by...

> Balloon twisting is fun: the activity can both entertain and engage children of all ages. Thus balloon twisting can be a vehicle for teaching mathematical concepts inherent in balloons. As we will see, these topics include graph theory, graph algorithms, Euler tours, Chinese postman tours, polyhedra (both 3D and 4D), coloring, symmetry, and even NP-completeness. Even the models alone are useful for education, e.g., in [illustrating molecules in chemistry](http://www.balloonmolecules.com/).

There's also a second motivation: _building architectural structures with air beams_ ([Army blows up building](http://www.architectsjournal.co.uk/home/army-blows-up-building/146865.article), [Center manages technology of inflatable composite structures](http://www.natick.army.mil/about/pao/05/05-19.htm)).

> Our approach suggests that one long, low-pressure tube enables the temporary construction of inflatable shelters, domes, and many other polyhedral structures, which can be later reconfigured into different shapes and re-used at different sites. In contrast to previous work, which designs a different inflatable shape specifically for each desired structure, we show the versatility of a single tube.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743070976748/740ab029-0c31-4033-b6ef-acbe871d27cc.jpeg)  
Twisting baloons

The problem of the researchers is to determine the _twistable_ graphs. Referring to a phisical balloon like a _bloon_, we have the following definitions:

> (...) a bloon is a (line) segment which can be _twisted_ at arbitrary points to form _vertices_ at which the bloon can be bent like a hinge. The endpoints of a bloon are also vertices. Two vertices can be _tied_ to form permanent point connections. A twisted bloon is _stable_ if every vertex is either tied to another vertex or held at a nonzero bending angle.

The three researchers also defined two models

1.  _(Simple) twisting_: Every subsegment of a bloon between two vertices forms an edge in the associated graph, representing an inflated portion of a balloon.
2.  _Pop twisting_: Some subsegments of a bloon between two vertices can be marked as deflated, causing them not to appear in the associated graph. Such deflated segments can be achieved with physical balloons by squeezing or sucking the air down the balloon or by popping a segment between two existing vertices (a practice common in balloon twisting, though requiring some care and skill).

Now with every bloon we can construct an euleran graph. So...

> **Th.1**: A graph has bloon number $1$ if and only if the graph is Eulerian

and

> **Th.2**: A graph with $o > 0$ odd vertices has bloon number $o/2$.

In the pop twisting model the main problem is to minimize the bloon's lenght. The problem is equivalent to the Chinese postman problem ([Nist](http://xlinux.nist.gov/dads//HTML/chinesePostman.html), [MathWorld](http://mathworld.wolfram.com/ChinesePostmanProblem.html)): we must find a cyclic path of minimum lenght in a undirected graph. If the graph has an eulerian circuit, that circuit is _an optimal solution_ ([Wikipedia](http://en.wikipedia.org/wiki/Route_inspection_problem "route inspection problem Wikipedia")).  
In the case of the pop twisting model the following theorem is true:

> **Th.3**: There is a polynomial-time algorithm that, given a graph and a desired $k \\geq 1$, finds the $k$ bloons of minimum total length that pop-twist the graph.

where $k$ is the numbers of bloon's paths.  
Now, before see the applications of the theory, there's the last theorems about **Hoyler's problem** in bloon model. We can define the problem in these therms:

> decide whether the edges of a graph can be decomposed into copies of a fixed graph $H$.

In 2009 **Krzysztof Bryś** and **Zbigniew Lonc** [resolved the problem](http://dx.doi.org/10.1016/j.disc.2008.01.054), and from this starting point researchers proof the following theorem:

> **Th.4**: Every graph with unit edge lengths can be twisted from doubloons and possibly one demidoubloon (when the graph has an odd number of edges).

In this case we can define an $l$-bloon like a bloon with lenght $l$, where $l$ is integer.  
Using Th.4 and the following two theorems we can mathematically proof the _platinic twisting_.

> **Th.5**: It is _NP_\-complete to decide whether a planar bipartite graph with unit edge lengths can be simply twisted from $l$-bloons.

> **Th.6**: It is strongly _NP_\-complete to decide whether a planar 3-connected graph with $o$ odd vertices can be simply twisted from $o/2$ equal-length bloons.

I remeber that for _NP_\-problems we intend a class of decisional problems that we can resolve in a polynomial time.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743070977609/c5aeab12-4067-458f-a66b-f0046cfa4fb7.jpeg)  
Constructing two platonic solids

And now the real baloons:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743070978728/e89214f3-71ed-4e79-8a87-f1750b573392.jpeg)  
Examples of one-balloon polyhedra

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743070979839/8a2f6810-fe60-45e1-94a9-941899c4f8d3.jpeg)  
![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743070980789/4c8adf5d-a51c-4c00-9bed-d6cf11ecdf62.jpeg)  
Platonic balloons

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743070982298/2f36fd28-4df3-4919-ab59-6c525d71bf7e.jpeg)  
Five intersecting tetrahedra (fifteen balloons).

* * *

Demaine E.D., Demaine M.L. & Hart V. (2008). Computational balloon twisting: The theory of balloon polyhedra., [Proceedings of the 20th Canadian Conference on Computational Geometry (CCCG2008)](http://cccg.ca/proceedings/2008/), 139-142.  
Bryś K. & Lonc Z. (2009). Polynomial cases of graph decomposition: A complete solution of Holyer's problem, Discrete Mathematics, 309 (6) 1294-1326. DOI: [10.1016/j.disc.2008.01.054](http://dx.doi.org/10.1016%2Fj.disc.2008.01.054)