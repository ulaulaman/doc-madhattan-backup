---
title: "Square deal: a solution"
seoDescription: "Explore a geometric puzzle involving congruence and area calculation using squares. Learn why the yellow area equals four square inches"
datePublished: Fri May 20 2011 22:14:00 GMT+0000 (Coordinated Universal Time)
cuid: cm8r8tqt5003y0aju13ulaa09
slug: square-deal-a-solution
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1745484069873/dc7d08de-62c2-45ca-93e3-6a47acc93260.jpeg
tags: mathematics, geometry, euclid

---

On Futility Closet, **Greg Ross** proposed an [interesting puzzle](http://www.futilitycloset.com/2011/05/20/square-deal-3/) that i reproduce in the following picture, using GeoGebra:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743073279149/b77c6305-cc7a-4d05-b8ff-8334e4b5048a.jpeg align="center")

The result of the quest (calculate yellow area, or \\(A{EIBM}\\) is 4 inch2. Why?  
First of all we must proof the congruence between \\(T_{AEIBM}\\) and \\(T_{EKCJ}\\), who is a square's quarter, and so \\(A_{EKCJ} = 4\\).  
First of all I proof the congruence between

1. \\(\widehat{LEM} = \beta\\) (definition)
    
2. \\(\widehat{IJE} = \pi = \widehat{ELM}\\)
    
3. \\(\widehat{IEL} = \pi + \beta = \widehat{LEJ} + \widehat{IEJ} = \pi + \widehat{IEJ}\\) (using 2 and 3)
    
4. So \\(\widehat{IEJ} = \beta = \widehat{LEM}\\)
    
5. \\(\widehat{IJE} = \pi = \widehat{MLE}\\)
    
6. \\(EJ = EL\\) (construction)  
    Following (4), (5), (6) (according to Euclide) \\(T_{EJI} = T_{ELM}\\)

The conclusion is very simple:  
\\(S_{EKCJ} = S_{EJBL}\\) for construction.  
Now, some calculation:

$$A_{EKCI} = A_{EKCJ} - A_{EIJ} = A_{EJBL} - A_{ELM} = A_{EJBM}$$

So we can calculate the requested area:

$$A_{EJI} + A_{EJBM} = A_{EJI} + A_{EKCI} = 4$$