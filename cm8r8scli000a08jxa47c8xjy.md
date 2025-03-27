---
title: "Ray representations and Galilei group"
datePublished: Wed Aug 24 2011 09:52:00 GMT+0000 (Coordinated Universal Time)
cuid: cm8r8scli000a08jxa47c8xjy
slug: ray-representations-and-galilei-group

---


[![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743073213764/def42cbf-1f16-4f4d-b238-64b9f6c43611.jpeg)](http://www.jstor.org/pss/1969831)

For my PhD thesis I performed a work in group teory, precisely in the theory of representations, applied to **quantum mechanics**. So, in order to describe my work, [recently published by the _Journal of Mathematical Physics_](http://dx.doi.org/10.1063/1.3621518), I need to introduce some concepts. The **group theory** was founded indipendetly by **Niels Abel** and **Evariste Galois** and it is focused on _group_, a set $G$ of elements with a multiplication operation $\\cdot$ and such that the following properties are true(9):

1.  $\\forall a, b \\in G, a \\cdot b \\in G$
2.  $\\forall a, b, c \\in G, a(bc) = (ab) c$
3.  $\\forall a \\in G \\, \\exists e \\in G \\, \\text{:} \\, ae = ea = a$
4.  $\\forall a \\in G \\, \\exists b \\in G \\, \\text{:} \\, ab = ba = e$ and $b = a^{-1}$

A group is called _abelian group_ if

1.  $\\forall a, b \\in G, ab = ba$

For every group, we can write a **representation**, that is a set of operators or functions that act in a mathematical space and change it in a same way at the elements of the group change their own space(1). In other (trivial) words we have a given _world_ with a group (for example our real world with a group of symmetry, for example the rotations), and in order to find properties of this _world_ we must use a mathematical representation.  
If the _world_ is a given physical system (for example a free particle), we have a symmetry group, that is a set of all symmetry transformation(2) of our physical system, and his representation acts in a so called Hilbert space. In this space, following Wigner's theorem(4), the most general representation is a ray (unitary) representation. In order to understand the ray (or projective) representations, we must enunciate the theorem:

> For every transformation of symmetry $T: \\mathcal R \\rightarrow \\mathcal R$ between the rays of a Hilbert space $\\mathcal H$ and such that conserve the transition probabilities, we can define an operator $U$ on the Hilbert space $\\mathcal H$ such that, if $|\\psi> \\in {\\mathcal R}\_\\psi$, then $U |\\psi> \\in {\\mathcal R}'\_\\psi$, where ${\\mathcal R}\_\\psi$ is the radius of the state $|\\psi>$, ${\\mathcal R}'\_\\psi = T {\\mathcal R}\_\\psi$, and $U$ uniform and linear \\\[< U \\psi | U \\varphi> = <\\psi | \\varphi>, \\qquad U |\\alpha \\psi + \\beta \\varphi> = \\alpha U |\\psi> + \\beta U |\\varphi>\\\] or with $U$ antiunitario and antilinear: \\\[< U \\psi | U \\varphi> = <\\varphi | \\psi>, \\qquad U |\\alpha \\psi + \\beta \\varphi> = \\alpha^\* U |\\psi> + \\beta^\* U |\\varphi>\\\] Further, $U$ is uniquely determined except for a phase factor.

So a ray representation is the association between an element of the symmetry group $G$ to a set of unitary (or antiunitary) operators which differ only for a phase: in other worlds a ray of operators(3).  
For two operators $U\_r$, $U\_s$ of the **ray representation** of a given group $G$, their product is given by the following multiplication rule: \\\[U\_r U\_s = \\omega (r,s) U\_{rs}\\\] where $\\omega (r,s)$ is a multiplicator factor such that $|\\omega (r,s)| = 1$. Now, in order to simplify the study of the properties ofthe group (and so of the physical system), we can define a phase exponent $\\xi (r,s)$: \\\[\\omega (r,s) = e^{i \\xi (r,s)}\\\] The phase exponent satisfies the following relations: \\\[\\xi (e,e) = 0\\\] \\\[\\xi (r,s) + \\xi (rs,t) = \\xi (s,t) + \\xi (r, st)\\\] where $e$ is the identity of the symmetry group.  
One physical consequence of the application of ray representations in quantum mechanics is the commutation rule between the operators momentum $P$ and position $Q$: \\\[\[Q,P\] = i \\qquad (1)\\\] Indeed, we can proof the following theorem(10):

> If $P$, $Q$, operators of a given Hilbert space, are such that their unitary representations $U(\\alpha) = e^{i \\alpha P}$, $V(\\beta) = e^{i \\beta Q}$, satisfy the following Weyl's commutation rule: \\\[U (\\alpha) V (\\beta) = e^{i \\alpha \\beta} V (\\beta) U (\\alpha)\\\] where $\\alpha$, $\\beta \\in \\mathbb R$, then $P$, $Q$ are a Schrodinger's couple (or a linear combination of a Schrodinger's couple). Their commutation rule is (1).

If we apply the result to Galilei's group in one dimension, we can interpret $P$ and $Q$ like momentum and position operators respectively.  
Now, if we have a free particle, we can describe its properties studying the corresponding Schrodinger equation, but the symmetry group of a free particle is the Galilei group. So, following Bargmann's work(6), that is the first real work about ray representations, we can calculate the ray representation of Galilei's group in (3+1)-dimensions, with the following phase exponent: \\\[\\xi = \\frac{1}{2} \\gamma \\left ( \\left < u\_r|W\_r v\_s \\right > - \\left < v\_r|W\_r u\_s \\right > + \\eta\_s \\left < v\_r|W\_r v\_s \\right > \\right )\\\] where $v$ is the relative velocity, $u$ is a space translation, $W$ an orthogonal transformation (for example a rotation), $\\eta$ a time translation, and $\\gamma$ is a multiplicative factor, which is interpreted like particle mass. So we have different ray representations for different particles: this is **the first Bargmann's superselection rule**(11).  
And finally, if we would calculate the ray representation of rotation group, $SO(3)$, we discover two different multipliers: one for integer spin, associated to a unitary representation of the group, and one for semi-integer spin, associated to a ray representation of the group. And this is **the second Bargmann's superselection rule**.  
The next step is to calculate the phase exponent of Galilei group in the (2+1)-dimensions. Combining results from **Bose**(12) and **Grigore**(14) we find the following two new phase factors: \\\[\\xi\_1 (r,s) = \\frac{1}{2} (v\_r \\wedge W\_r v\_s)\\\] \\\[\\xi\_2 (r,s) = \\theta\_r \\eta\_s - \\theta\_s \\eta\_r\\\] where $(u \\wedge v) = u\_1 v\_2 - v\_1 u\_2$, with $u$, $v$ two-dimensional vectors. After, according to **Doebner** and **Mann**(13), we can calculate the phase factor also for (1+1)-dimensions: \\\[\\xi\_\\eta(r,s) = \\frac{a\_1}{2} (a\_r v\_s - a\_s v\_r + \\eta\_r v\_r v\_s) + \\frac{a}{2} (u\_r \\eta\_s - u\_s \\eta\_r - \\eta\_r \\eta\_s v\_)\\\] They conclude the work calculating an explicitely time depending representation.  
At this point I inserted my idea. In 2004 Wawrzycki(15) proposed a generalization of the classical Bargmann's theory in which the phase exponent is explicitely depend on time: his objective was resolved the photon localizability problem, but I think that, in this moment, is impossible to resolve. But the generalization let me the idea to try to generalize the approach of Doebner and Mann to the higher dimensions. After some (and probably trivial) calculation I found a new phase exponent that is explicitely depends on time: \\\[\\xi\_t (r,s) = - \\gamma \\left < v\_r | W\_r v\_s \\right > t\\\] and the time ray representation is given by \\\[ U\_t (r) f) (p) = e^{i < p | v\_r > t} (U(r) f)(p) \\\] where $r$ is a given symmetry transformation in $G$, $U(r)$ is the representation of $G$ of Galilei group, $f(p)$ is a function of the momentum $p$, $v\_r$ is the relative velocity associated with the frame of the symmetry transformation $r$, and $t$ is the time.  
Now we can identify every frame system $\\Sigma\_r$ with a corresponding Galilei transformation $r$. So if we examine for some particular transformation $r \\in G$, we can see that pahse exponents for every dimensions correspond to the action of the particle in frame system $\\Sigma\_{rs}$. So, combining the $\\xi\_t (r,s)$ phase exponent with (3+1)- and (2+1)-phase exponent, we have the total action of the particle in $\\Sigma\_{rs}$.

* * *

**Update**: I forget to add [ResearchGate profile](http://www.researchgate.net/profile/Gianluigi_Filippelli/?mnu=p0) and [Mandeley profile](http://www.mendeley.com/profiles/gianluigi-filippelli/). In this last you can donwload the draft approved version of my paper(16).

* * *

(1) We can imagine that every set, in some opportunity condition (for example the product between two elements of the set is also an element of the same set), is a space.  
(2) A symmetry transformation is an operation of the space (for example in our real world) that let be invariant the studied system.  
(3) This concept is a generalization of vectors' ray, founded by Weyl in 1950(5, 7, 8). The usually vectors' ray is a set constituted by wave functions $\\psi$ in Hilbert space that differ only for a phase $\\tau$ such that $|\\tau| = 1$. We can so define the product between two different rays: \\\[R\_\\psi \\cdot R\_\\phi = | < \\psi | \\phi > |\\\] the lenght: |R\_\\psi| = (R\_\\psi \\cdot R\_\\psi)^{\\frac{1}{2}}\\\] and the dinstance \\\[d(R\_\\psi, R\_\\phi) = \\sqrt{2(1-R\_\\psi \\cdot R\_\\psi)}\\\] In the same way we can define a ray of operators like a set of unitary operators that differ only for a phase $\\theta$. Consequence of this fact is that the product between two different operators $U\_r$, $U\_s$ is \\\[U\_r \\cdot U\_s = \\omega (r,s) U\_{rs}\\\] where $r$, $s$ are two symmetry transformations of the same symmetry group, $\\omega (r,s)$ is a function of $r$, $s$ such that $|\\omega (r,s)| = 1$.  
So a **ray** (or _projective_) **representation** is a group representation in which every symmetry transformation is associated to a ray of unitary transformations.

* * *

(4) **Eugene Wigner** (1931), _Gruppentheorie und ihre Anwendung auf die Quantenmechanik der Atomspektrum_  
(5) **Herman Weyl** (1931), _The thoery of groups and quantum mechanics_, London  
(6) **Bargmann, V.** (1954). On Unitary Ray Representations of Continuous Groups The Annals of Mathematics, 59 (1) DOI: [10.2307/1969831](http://dx.doi.org/10.2307/1969831)  
(7) **U. Uhlhorn** (1963), [Representation of symmetry transformations in quantum mechanics](http://www.osti.gov/energycitations/product.biblio.jsp?osti_id=4695249), Ark. Fys. 23, 307–340  
(8) **Bargmann, V.** (1964). Note on Wigner's Theorem on Symmetry Operations Journal of Mathematical Physics, 5 (7) DOI: [10.1063/1.1704188](http://dx.doi.org/10.1063/1.1704188)  
(9) **Lev Semenovich Pontryagin** (1966), _Topological groups_, second edition, Gordon and Breach Science Publisher Inc.  
(10) **C.R.Putnam** (1967), _Commutation properties of Hilbert space Operators_, Springer-Verlag  
(11) **Brennich, R. H.** (1970), [The irreducible ray representations of the full inhomogeneous Galilei group](http://archive.numdam.org/ARCHIVE/AIHPA/AIHPA_1970__13_2/AIHPA_1970__13_2_137_0/AIHPA_1970__13_2_137_0.pdf), Annales de l'institut Henri Poincaré (A) Physique théorique, 13 no. 2, p.137  
(12) **Bose, S.** (1995). Representations of the (2+1)-dimensional Galilean group Journal of Mathematical Physics, 36 (2) DOI: [10.1063/1.531163](http://dx.doi.org/10.1063/1.531163)  
(13) **Doebner, H.**, & **Mann, H.** (1995). Ray representations of N(≤2)+1-dimensional Galilean group Journal of Mathematical Physics, 36 (7) DOI: [10.1063/1.531026](http://dx.doi.org/10.1063/1.531026)  
(14) **Grigore, D.** (1996). The projective unitary irreducible representations of the Galilei group in 1+2 dimensions Journal of Mathematical Physics, 37 (1) DOI: [10.1063/1.531402](http://dx.doi.org/10.1063/1.531402)  
(15) **Wawrzycki, J.** (2004). A Generalization of the Bargmann's Theory of Ray Representations Communications in Mathematical Physics, 250 (2) DOI: [10.1007/s00220-004-1141-4](http://dx.doi.org/10.1007/s00220-004-1141-4)  

(16) Filippelli, G. (2011). Time dependent quantum generators for the Galilei group Journal of Mathematical Physics, 52 (8) DOI: [10.1063/1.3621518](http://dx.doi.org/10.1063/1.3621518)