---
title: "Pi Day and the BBP formula"
datePublished: Wed Mar 14 2012 22:05:00 GMT+0000 (Coordinated Universal Time)
cuid: cm8r8e2o8000d0al4gojj6osv
slug: pi-day-and-the-bbp-formula

---


In the last few days I must write the [47th italian Carnival of Mathematics](http://dropseaofulaula.blogspot.com/2012/03/carnevale-della-matematica-47.html) ([Google translation](http://goo.gl/bsKsq)), so I cannot write something about [**Pi Day**](http://www.piday.org/). So, in the end of the day, I try to write a little post about this day.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743072547777/71287140-12fe-418b-bb57-2eb9dba0553f.jpeg)

$\\pi$ is one of the irrational numbers: we cannot write an irrational numbers like a ratio between twointeger numbers, so Pitagora's team called them _irrational_ and hidden their existence. We can define $\\pi$ like the ratio between circle and his diameter, and it's impossible that they are contemporary integer. This assertion was proofed in 1761 by **Johann Heinrich Lambert**, while in 1882 **Ferdinand von Lindemann** proofed that $\\pi$ is a trascendental number, where a trascendental number is a number that we cannot calculate with usual algebric operations.  
In ancient times, the first mathematician who evaluate $\\pi$ was **Archimedes**, who used the method of exhaustion, that is a method to evaluate the area of a shape by inscribing inside it a series of polygons that converge to area's shape. In this way Archimedes find $\\pi = \\frac{211875}{67441} = 3.14163 \\cdots$  
Today we know 5 triolions of digits, thanks to the work of **Shigeru Kondo**, who modify a usual home pc in order to perform the calculations using the softwerdeveloped by **Alexander Yee**. They design an [internet site to describe methods, software and results](http://www.numberworld.org/misc_runs/pi-5t/announce_en.html).  
Following **David Bailey** and **Jonathan Borwein**(1), I find some others interesting site about the calculations of $\\pi$'s digits ([Inverse Symbolic Calculator](http://web.archive.org/web/20041204173054/http://www.cecm.sfu.ca/projects/ISC/), [Electronic Geometry Models](http://www.eg-models.de/)). Other links at [Experimental mathematics](http://www.experimentalmath.info/). But... what is _experimental mathematics_?

> (...) namely the utilization of modern computer technology as an active tool in mathematical research.(1)

For example using the [PSLQ algorithm](http://mathworld.wolfram.com/PSLQAlgorithm.html)(2) in 1995 was found the BBP formula for $\\pi$: \\\[\\pi = \\sum\_{k=0}^\\infty \\frac{1}{16^k} \\left ( \\frac{4}{8k+1} - \\frac{2}{8k+4} - \\frac{1}{8k+5} - \\frac{1}{8k+6} \\right )\\\]

> This formula permits one to directly calculate binary or hexadecimal digits beginning at the $n$-th digit, without needing to calculate any of the first $n − 1$ digits, using a simple scheme that requires very little memory and no multiple-precision arithmetic software.(1)

You can find others BBP formulas in the **David Bailey**'s compendium ([pdf](http://crd-legacy.lbl.gov/~dhbailey/dhbpapers/bbp-formulas.pdf)).

(1) Jonathan M. Borwein, David H. Bailey. [_Experimental Mathematics: Examples, Methods and Implications_](http://www.ams.org/notices/200505/fea-borwein.pdf). Notices of the American Mathematical Society, vol.52, 5, (2005)  
(2) PSLQ algorithm, _which, compared with other integer relation algorithms in the literature, features superior performance and excellent numerical stability_, _will produce lower bounds on the (Frobenius) norm of any possible relation for $x$_, where $x$ is an arbitrary vector defined on some number field.  
Ferguson, H., Bailey, D., & Arno, S. (1999). Analysis of PSLQ, an integer relation finding algorithm Mathematics of Computation, 68 (225), 351-370 DOI: [10.1090/S0025-5718-99-00995-3](http://dx.doi.org/10.1090/S0025-5718-99-00995-3)

* * *

_Image source: [Brainfreeze Puzzles](http://brainfreezepuzzles.com/main/piday2009.html)_