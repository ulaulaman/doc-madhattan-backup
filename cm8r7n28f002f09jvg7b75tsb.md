---
title: "A brief history of pi: part 2"
datePublished: Fri Mar 14 2014 21:39:00 GMT+0000 (Coordinated Universal Time)
cuid: cm8r7n28f002f09jvg7b75tsb
slug: a-brief-history-of-pi-part-2

---


by @ulaulaman about #piday #pi #MachinFormula #EulerIdentity

Today is the _pi day_, so I continue the [brief history of $\\pi$](http://docmadhattan.fieldofscience.com/2013/03/a-very-brief-story-of-pi.html)

[![Flattr this](//api.flattr.com/button/flattr-badge-large.png "Flattr this")](https://flattr.com/submit/auto?user_id=ulaulaman&url=http%3A%2F%2Fdocmadhattan.fieldofscience.com%2F2014%2F03%2Fa-brief-history-of-pi-part-2.html)

After the introduction of $\\pi$ in mathematics, one of the quest linked with the calculation of its digits is the research about its nature, or in other words what kind of number it is. Numbers classification is simple for all: we start with natural numbers (positive and negative), and so we can define rational numbers, as the numbers generated by the ratio between two natural numbers. Every rational number could be expressed like $\\frac{a}{b}$, with $a$, $b$ natural and $b$ not null.  
**Johann Heinrich Lambert** was the first to show the irrational nature of $\\pi$ in 1761 in [_Mémoire sur quelques propriétés remarquables des quantités transcendantes circulaires et logarithmiques_](http://www.kuttaka.org/~JHL/L1768b.html):

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743071281878/0d40a0c2-fb26-48dd-9427-b4e9235b4f31.jpeg)  
[commons](http://commons.wikimedia.org/wiki/File:LambertContinuedFraction.JPG)

that could be written in this way: \\\[\\tan(x) = \\cfrac{x}{1 - \\cfrac{x^2}{3 - \\cfrac{x^2}{5 - \\cfrac{x^2}{7 - {}\\ddots}}}}\\\] Lamberd proved that if $x$ is not null and rational, then the previous expression must be irrational. So the irrationality of $\\pi$ follows from $\\tan (\\pi /4) = 1$. A good synthesis of Lambert's proof is on [The world of $\\pi$](http://www.pi314.net/eng/lambert.php).  
In 1997 **Laczkovich** proposed a simplification of this demonstration, while another variation was proposed in 2009 by **Li Zhou**, using the integral calculus. In particular the second demonstration is inspired by the proof that **Charles Hermite** written in two letters to Paul Gordan and Carl Borchardt in 1873. Following Harold Jeffreys in Scinetific interference (1973), a simplification of this proof, that used a _reductio ab adsurdum_ is proposed by **Mary Cartwright**.  
Another proof of one page about the irrationality of $\\pi$ is dued by **Ivan Niven** in 1946.  
At the other hand, the transcendence of $\\pi$ is a direct consequence of the Lindemann-Weierstrass theorem:

> If $\\alpha\_1$, $\\cdots$, $\\alpha\_n$ are algebraic numbers that are linearly independent over rationals, then $e^{\\alpha\_1}$, $\\cdots$, $e^{\\alpha\_n}$ are algebraically independent over rationals.

where an algebraic number is the solution of a polynomial equation with rational coefficients.  
In 1882 Lindemann, using this theorem, showed that $e$ is transcendental, and, like a consequence of the Euler's identity, also $\\pi$ is transcendental.

**James Constant**. [Elementary proof that $\\pi$ is irrational](http://www.coolissues.com/mathematics/Pi/pi.htm)  
**Xavier Gourdon**, **Pascal Sebah**. [Numbers, constants and computation](http://numbers.computation.free.fr/Constants/constants.html)

* * *

Laczkovich M. (1997). On Lambert's Proof of the Irrationality of π, The American Mathematical Monthly, 104 (5) 439-443. DOI: [10.2307/2974737](http://dx.doi.org/10.2307%2F2974737)  
Li Zhou (2009). Irrationality proofs à la Hermite, arXiv: [0911.1929v2](http://arxiv.org/abs/0911.1929v2)  
Zhou L. & Markov L. (2010). Recurrent Proofs of the Irrationality of Certain Trigonometric Values, American Mathematical Monthly, 117 (4) 360-362. DOI: [10.4169/000298910X480838](http://dx.doi.org/10.4169%2F000298910X480838) ([arXiv](http://arxiv.org/abs/0911.1933))  
Niven I. (1947). A simple proof that $\\pi$ is irrational, Bulletin of the American Mathematical Society, 53 (6) 509-510. DOI: [10.1090/S0002-9904-1947-08821-2](http://dx.doi.org/10.1090%2FS0002-9904-1947-08821-2)  
Chow T.Y. (1999). What is a Closed-Form Number?, The American Mathematical Monthly, 106 (5) 440. DOI: [10.2307/2589148](http://dx.doi.org/10.2307%2F2589148) ([pdf](https://math.mit.edu/~tchow/closedform.pdf))

The $\\pi$ formulas that I examined [last year](http://docmadhattan.fieldofscience.com/2013/03/a-very-brief-story-of-pi.html) are only a little subset of the complete set of pi formulas. This year I would examine some others, starting from the **Machin formula**: \\\[\\frac{1}{4} \\pi = 4 \\tan^{-1} \\frac{1}{5} - \\tan^{-1} \\frac{1}{239}\\\] There are other three Machin formulas, that [you can see them at MathWorld](http://mathworld.wolfram.com/Machin-LikeFormulas.html).  
Another historical formula for $\\pi$ is the **Leibniz-Gregory formula**: \\\[\\frac{\\pi}{4} = \\sum\_{k=1}^n \\frac{(-1)^{k+1}}{2k-1}\\\] This series is also known as the **Leibniz series**: only in a subsequent period it is associated to **James Gregory**'s work, that rediscovered and published in 1668 a series that it was discovered by **Madhava from Sangamagrama**, an indian mathematician and astronomer of 14th century.  
The formula could be modified in order to accelerate its convergence, using the [$\\zeta (s)$ of **Riemann**](http://docmadhattan.fieldofscience.com/2011/09/riemann-hypothesis.html): \\\[\\pi = \\sum\_{k=1}^\\infty \\frac{3^k-1}{4^k} \\zeta (k+1)\\\] Another historical series was discovered in 1717 by **Abarham Sharp**: \\\[\\pi = \\sum\_{k=0}^\\infty \\frac{2 (-1)^k 3^{1/2 - k}}{2k+1}\\\] Also **Euler** discovered a series about $\\pi$: the great swiss mathematician not only named the number $\\pi$, or found the identity that linked the most important math constants (and that in some sense summarize the math itself) \\\[e^{i \\pi} + 1 = 0\\\] but discovered also the following product of sequences, where $p\_n$ is the $n\_{th}$ prime number: \\\[\\pi \\frac{2}{\\prod\_{n=1}^\\infty \\left ( 1 + \\frac{\\sin \\left ( \\frac{1}{2} \\pi p\_n \\right )}{p\_n} \\right )}\\\] This formula could be also plotted:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743071283388/09be495a-026b-4784-9e27-86439c9fde39.gif)

Bailey D.H., Plouffe S.M., Borwein P.B. & Borwein J.M. (1997). The quest for PI, The Mathematical Intelligencer, 19 (1) 50-56. DOI: [10.1007/BF03024340](http://dx.doi.org/10.1007%2FBF03024340) ([pdf](http://docserver.carma.newcastle.edu.au/164/2/96_070-Bailey-Borwein-Borwein-Plouffe.pdf))  
Jesus Guillera (2008). History of the formulas and algorithms for pi, La Gaceta de la RSME, 10 (2007) 159-178, arXiv: [0807.0872v3](http://arxiv.org/abs/0807.0872v3)  
Philippe Flajolet, Ilan Vard. _Zeta Function Expansions of Classical Constants_ ([pdf](http://algo.inria.fr/flajolet/Publications/FlVa96.pdf))  
Wikipedia: [Leibniz formula for $\\pi$](http://en.wikipedia.org/wiki/Leibniz_formula_for_%CF%80)  
Weisstein, Eric W. "[Pi Formulas](http://mathworld.wolfram.com/PiFormulas.html)" From MathWorld--A Wolfram Web Resource.

One of the most interesting math challenge during the last century is the unsolved distribution of prime numbers. We have seen that the Riemann's zeta function, that plays a key role in the research, could also be used to calculate $\\pi$.  
So it is simple to imagine that also the distribution of digits of $\\pi$ are not so random. Indeed **Caldwell** and **Dudner** play with the first 10 digits of $\\pi$ in search of the prime numbers that we could construct with them. And they found 14 prime numbers!

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743071284856/84ef551f-7251-42e9-9ac7-2bee029ced82.jpeg)

And they also calculate the probability to find a pime number of some given digits in a given sequence of digits randomly extracted from $\\pi$:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743071286219/bed00d03-a25b-474c-b773-3582ea8e4b4b.jpeg)

This is an example of a classical problem without a clear practical utility, but that could allow to build new calculus tecnique, analitical or numerical, useful to solve multidisciplinary problems.  
In every case, the digits of $\\pi$ are infinity, and we know only [about 5 trillions](http://www.numberworld.org/misc_runs/pi-5t/details.html). Calculate them is really a great challenge, but also visualize them is not so simple, unless to use the technique based on the random walk.  
This idea born around the quest of the normality of the transcendental numbers: a real number $a$ is called normal in base $b$ if every set of $m$ digits appears with a frequency equals to $1/b^m$. From this the step toward finding the distribution of digits of pi is short, and so the use of random walk in order to visualize $\\pi$:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743071287594/9dd94820-8b40-4528-b192-20bf083871a2.jpeg)

Samuel Arbesman. [A Random Walk with Pi](http://www.wired.com/wiredscience/2012/06/a-random-walk-with-pi/)  
[Walking on Real Numbers](http://walks.carma.newcastle.edu.au/index.html)

* * *

Chris K. Caldwell, Harvey Dubner. _Primes in Pi_. Journal of Recreational Mathematics, Volume 29, Number 4, 1998 ([pdf](http://www.utm.edu/staff/caldwell/preprints/PrimesInPi.pdf))  
Aragón Artacho F.J., Bailey D.H., Borwein J.M. & Borwein P.B. (2013). Walking on Real Numbers, The Mathematical Intelligencer, 35 (1) 42-60. DOI: [10.1007/s00283-012-9340-x](http://dx.doi.org/10.1007%2Fs00283-012-9340-x)  
Bailey D.H., Borwein J.M., Calude C.S., Dinneen M.J., Dumitrescu M. & Yee A. (2012). An Empirical Approach to the Normality of π, Experimental Mathematics, 21 (4) 375-384. DOI: [10.1080/10586458.2012.665333](http://dx.doi.org/10.1080%2F10586458.2012.665333)  
Aistleitner C. (2013). Normal Numbers and the Normality Measure, Combinatorics, Probability and Computing, 22 (03) 342-345. DOI: [10.1017/S0963548313000084](http://dx.doi.org/10.1017%2FS0963548313000084) ([arXiv](http://arxiv.org/abs/1302.1919))