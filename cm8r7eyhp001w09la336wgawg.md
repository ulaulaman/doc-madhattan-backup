---
title: "A bit of math behind Ant-Man"
datePublished: Thu Jan 28 2016 22:00:00 GMT+0000 (Coordinated Universal Time)
cuid: cm8r7eyhp001w09la336wgawg
slug: a-bit-of-math-behind-ant-man

---


cc @sarofsky

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743070904595/9a7f2bcd-848b-427f-8a2d-58c0a054b50b.jpeg)

I write also for [_Lo Spazio Bianco_](http://www.lospaziobianco.it/) ([_The White Space_](http://lospaziobianco.com/)), a web-zine about comics. Thanks to **Carlo Coratelli**, that contacted _Sarofsky Corp._, we can realize an interview with **Erin Sarofsky**, President, Owner and Executive Creative Director of the company. They realized some titles for Marvel Studios movies, in oparticular _Ant-Man_, and I proposed two questions about this movie. The questions, with Erin's answers, are the following, but you can read the complete interview [here](http://lospaziobianco.com/813-behind-the-scenes-of-marvel-titles-interview-to-erin-sarofsky-sarofsky-design/):

* * *

**We loved the opening animation in _Ant-Man_. It seems it's inspired by the _Power\[s\] of Ten_ of the Eames. Is it really like that?**  
Ab-So-Lutely! We were very inspired by the Eames film. Luckily though, our universe is the Marvel Universe... so being 100% accurate was not necessary.  
**About _Ant-Man_, we also loved the work with the mathematical modeling you used to produce the animation and we think it would be quite interesting to elaborate about the actual realization method. How does it work?**  
We actually worked in reverse. We planned our moves and then did the math after the fact. We used the surface of the grass as our zero; anything above that is positive and anything below is negative.  
Andy Zazzera, CG Director on the job, and our wicked smart math guy did all the estimations. (Again, nothing is exact because our world is fake... but the math is legit).

* * *

For a while I was tempted to quest something of more detailed about the math developing, but I thought that it could not so interesting for our regular readers. However, I'm convinced that it is not for _Field of Science_'s readers!  
The mathematical basis of 3d modeling originate in automotive industry, in particular thanks to **Pierre Bézier** that developed the [Bézier's curves](http://en.wikipedia.org/wiki/B%C3%A9zier_curve) for Renault, starting from an algorithm developed by **Paul de Casteljau** for Citroen.  
Bézier's curves are defined from two or more control points, $P\_i$, and using a parameter $t \\in \[0,1\]$: \\\[B (t) = \\sum\_{i=0}^n b\_{in} (t) P\_i\\\] where $b\_{in}$ are the Bernstein's polynomials \\\[b\_{in} (t) = \\binom{n}{i} t^i (1-t)^{n-i}\\\] with $i = 0, \\cdots, n$.  
In the same way it is possible to define the Bézier' surfaces, that are an important tools in computer graphics.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743070906351/d99ff3e6-e82a-4dae-9ef0-2eae73de09fb.gif)

Another useful tools for 3d modeling is the [continuation method](http://issuu.com/gianluigiulaula/docs/continuation_method/0) (or [numerical continuation](http://en.wikipedia.org/wiki/Numerical_continuation)). Given a system of equations $F(x) = 0$, you can choose an appropriate system $G(x)$ that is more simple and also a continuous evolution of the system $F(x)$. In other words there must be exist a continuous transformation between $F(x)$ and $G(x)$. This method was refined by **Alexander Morgan** in 1980s for General Motors:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743070908370/3060d649-5c9e-4f0e-b1a4-fd2a5a92b4e8.jpeg)

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743070909588/0c6180c5-362e-4ab5-97f6-ab9ddff46b8e.jpeg)