---
title: "Gravity vs height"
datePublished: Sun Apr 15 2012 13:54:00 GMT+0000 (Coordinated Universal Time)
cuid: cm8r8damp000x09jueg3c3rvm
slug: gravity-vs-height

---


![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743072511656/4e01ed08-71dd-4103-b7a9-d638861fa2c7.jpeg)  
(powered by [scilab](http://www.scilab.org/))

Source code:

> G = 6.67428 \* 10^(-11);  
> R = 12745594/2;  
> M = 5.9742 \* 10^(24);  
> function g = myg (x)  
> g = G\*M/(R+x)^2  
> endfunction  
> xdata=linspace(0,2\*R,5000);  
> plot(xdata,myg)  
> eps = 10^(-1);  
> d0 = sqrt(G\*M/eps) - R