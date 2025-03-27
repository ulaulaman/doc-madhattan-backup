---
title: "A prize for a theorem"
datePublished: Thu Mar 24 2016 21:51:00 GMT+0000 (Coordinated Universal Time)
cuid: cm8r7ehey000q08l7hxq997u3
slug: a-prize-for-a-theorem

---


> Pierre de Fermat was born in 1601 in Beaumont-de-Lomagne in southwestern France. He was not even a mathematician; he was a civil servant who devoted himself to mathematics as a hobby. He was regarded as one of the most gifted self-taught mathematicians who ever lived.

I think that this quotation from _The girl who played with fire_ by **Stieg Larson**, the second novel from the series _Millennium_, was the perfect introduction to a post about the _Fermat's Last Theorem_ and **Andrew Wiles**, who proofed it in 1993. And he awarded the Abel Prize just [some days ago](http://www.abelprize.no/nyheter/vis.html?tid=67106).

**Simply a joke?**

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743070884492/3f227b06-e89d-4918-b131-fe23584c6feb.gif)  
Pierre de Fermat by **Bernarda Bryson**

> Cubum autem in duos cubos, aut quadratoquadratum in duos quadratoquadratos, et generaliter nullam in infinitum ultra quadratum potestatem in duos ejusdem nominis fas est dividere: cujus rei demonstrationem mirabilem sane detexi. Hanc marginis exiguitas non caperet.(1)

This is what **Pierre de Fermat** wrote in the margin of _Arithmetica_ by **Diofanto** and it establish the impossibility to find solutions in the field of natural numbers for the _diophantine equation_(2) that generalizes the _Pythagorean theorem_: \\\[a^n + b^n = c^n\\\] Following the Pythagorean theorem, for $n = 2$ the _Fermat's equation_ has solutions in the field of natural numbers, called _Pythagorean triples_. For $n$ greater than 2 the story, instead, becomes more complicated, so that the same Fermat, while writing what follows, never provided a full demonstration, but only for the special case of $n = 4$:

> I have discovered a truly marvelous proof of this theorem, which can't be contained in the too narrow page margin.

So the previous statement becomes a challenge to mathematicians, and many of them, over the centuries, take up it. The problem is that, invariably, every one of them collided against the full formal proof, finally obtaining only partial victories (demonstrations of special cases), and sometimes the discovery of a new mathematical tool, useful for the next demonstration. The first successful step(3) was by **Sophie Germain**, who proved the following theorem(4):

> If $p$ is an odd prime such that $2 p + 1$ is also prime and if $x$, $y$ and $z$ are integers none of which is divisible by $p$ then \\\[x^p + y^p \\neq z^p\\\] Such $x$, $y$ and $z$ cannot therefore be counterexamples to Fermat's Last Theorem for exponent $p$.

Now, if $n$ and $2n+1$ are primes, then $x^n + y^n = z^n$ implies that one of $x$, $y$, $z$ is divisible by $n$, and the Fermat's last theorem splits into two cases:

1.  none of $x$, $y$, $z$ is divisible by $n$;
2.  one and only one of $x$, $y$, $z$ is divisible by $n$.

The Germain's theorem proofed the first caso for all $n$ less than 100, subsequently extended by **Legendre** to all numbers less than 197.  
After this first attempt, many others followed up to the final Wiles' settlement, that while it ends the hunt to the solution, on the other hand leaves open the question closely related to the original Fermat's proof.

**The lost demonstration**

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743070885959/ee862281-2cdd-43c5-8733-d8d1246d864c.jpeg)  
Pierre de Fermat

It is quite obvious, in fact, that Fermat could not know many of the techniques and theorems, tied wings elliptic equations, available to Wiles, so there have been many speculations about the case. Basically there are two main positions: someone believe that he never had a proof of the theorem, apart from the partial for the fourth degree, while others simply believe that the French mathematician realized that his proof was wrong, so he decided to publish only the particular case. It could, however, be another solution.  
Wiles, in his demonstration, made an extensive use of elliptic functions, but this is not surprising considering that Fermat's theorem is actually based on an equation that is part of this class. And the elliptic equations are one of the topics studied by **Niels Abel**, who regardless of **Evariste Galois**, discovered (or created) group theory. So it might not be impossible to imagine that, in fact, Fermat found himself holding a demonstration that anticipated the results of Abel and Galois and, not trusting the results found, he decided to make it disappear forever.  
What is certain is that the [Fermat's little theorem](http://en.wikipedia.org/wiki/Proofs_of_Fermat%27s_little_theorem), which states that for every integer $a$, and every prime $p$, $a^p - a$ is divisible by $p$(5) can be proofed either using group theory, both using the binomial theorem.  
A demonstration that used the binomial theorem and the quest of the solution of a polynomial equation was proposed in 2011 by **Daniele De Pedis**(6).  
Basically, De Pedis uses the development of a polynomial combination of the Fermat's equation in order to reduce the proof of the theorem to proof that the obtained polynomial equation has no solutions, less the trivial solution. The demonstration uses the binomial coefficients (which in modern notation, used in the article, were introduced in 1826), known since the tenth century, and the research of the roots of generic degree equations.  
I don't know if this is the original "_admirable_" Fermat's demonstration, and I don't know if it is complete (I think no), but in every case it is the "_admirable_" demonstration of De Pedis.

**The ultimate demonstration**

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743070887444/a5582b4b-fecf-4afe-9606-58cdfe06d142.jpeg)  
Andrew Wiles

As written before, the ultimate demonstration was ended by the British mathematician Andrew Wiles, presented at a conference held in Cambridge in 1993. Unfortunately, the first demonstration contained a mistake, as **Nick Katz** realized. At the age, Katz was one of the referees who was examining the Wiles' manuscript for publication on _Inventiones Mathematicae_, magazine directed by **Barry Mazur**, friend and acquaintance of both.  
To conclude the proof was more difficult than expected: after many months in which Wiles tried to reproduce the magical alchemy of solitude and concentration that enabled him to get his first important result, could not take the last step, so, after the suggestion of **Peter Sarnak**, he decided to ask for help and assistance to one of his former students and, among other things, one of the referees chosen by the magazine, **Richard Taylor**. Thanks to the merging of the two minds and to an unexpected intuition even this incredible mathematical theorem found the final solution, with the further result of the union between two separated mathematical worlds as ellipticals and modular forms. The proof of Wiles, in fact, is based on the demonstration of **Taniyama** and **Shimura** (now risen to the theorem), two Japanese researchers, two friends very much related each other, but the life's vicissitudes inextricably separated (Taniyama, close to the wedding, killed himself for unspecified reasons, in a story similar to the Majorana's _affair_).  
The ultimate proof was published on _Annals of Mathematics_:

Wiles, A. (1995). Modular elliptic curves and Fermat's last theorem. _Annals of mathematics_, 141(3), 443-551. DOI: [10.2307/2118559](http://www.jstor.org/stable/2118559) ([pdf](http://ar.newsmth.net/att/e92a34d6a3783/Wiles1995.pdf))  
Taylor, R., & Wiles, A. (1995). Ring-theoretic properties of certain Hecke algebras. _Annals of Mathematics_, 141(3), 553-572. DOI: [10.2307/2118560](http://www.jstor.org/stable/2118560) ([pdf](http://bbs.cup.edu.cn/cupbbs/accessory/93/157311d5-09fd-481f-9fed-c9d2bea23648.pdf))

* * *

(1) "_It is impossible to separate a cube into two cubes or a fourth power into two fourth powers or, in general, all the major powers of two as the sum of the same power. I have discovered a truly marvelous proof of this theorem, which can’t be contained in the too narrow page margin._"  
(2) A Diophantine equation is an equation for which we must seek solutions exclusively in the field of natural numbers.  
(3) The first step was dued by **Euler**, but in his demonstration for $n = 3$, there was a mistake. Read [History topic: Fermat's last](theorem http://www-history.mcs.st-and.ac.uk/PrintHT/Fermat's_last_theorem.html)  
(4) via Theorem of the day ([pdf](http://www.theoremoftheday.org/NumberTheory/Germain/TotDGermain.pdf))  
(5) In a more formal way we can wrtite that $a^p \\equiv p (\\mod p)$  
(6) De Pedis, D. (2011). Polynomial representation of Fermat's Last Theorem. arXiv preprint arXiv:[1105.0669](http://arxiv.org/abs/1105.0669).