---
title: "When gaming is NP-hard"
datePublished: Sun Mar 30 2014 10:14:00 GMT+0000 (Coordinated Universal Time)
cuid: cm8r7mt4r000s09ld4al6fme6
slug: when-gaming-is-np-hard

---


by @ulaulaman about #candycrush #bejeweled #shariki #nphard #computerscience

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743071275801/27435ae1-7388-48c7-af3f-d073886f11df.jpeg)

[_Shariki_](http://en.wikipedia.org/wiki/Shariki) is a puzzle game developed by the russian programmer **Eugene Alemzhin** in 1994. The rules are simple:

> (...) matching three or more balls of the same color in line (vertical or horizontal). These balls then explode and a new ones appear in their place.

The first _Shariki_'s clone is _Tetris Attack_, a fusion between _Shariki_ and the most famous _Tetris_, also this developed in Soviet Union by **Alexey Pajitnov**. But the most famous clone is _Bejeweled_ (2001) by PopCap Games, from which is derived the _Candy Crush Saga_. During this March, **Toby Walsh** and the italian team composed by **Luciano Gualà**, **Stefano Leucci**, **Emanuele Natale** proved that _Candy Crush_ and other similar games are [NP-hard](http://www.scottaaronson.com/blog/?p=459):

> The twentieth century has seen the rise of a new type of video games targeted at a mass audience of "casual" gamers. Many of these games require the player to swap items in order to form matches of three and are collectively known as _tile-matching match-three games_. Among these, the most influential one is arguably _Bejeweled_ in which the matched items (gems) pop and the above gems fall in their place. _Bejeweled_ has been ported to many different platforms and influenced an incredible number of similar games. Very recently one of them, named _Candy Crush Saga_ enjoyed a huge popularity and quickly went viral on social networks. We generalize this kind of games by only parameterizing the size of the board, while all the other elements (such as the rules or the number of gems) remain unchanged. Then, we prove that answering many natural questions regarding such games is actually _NP-Hard_. These questions include determining if the player can reach a certain score, play for a certain number of turns, and others.

The italian team realized also a [web-based implementation of their technique](http://candycrush.isnphard.com/).

* * *

Toby Walsh (2014). Candy Crush is NP-hard, arXiv: [1403.1911v1](http://arxiv.org/abs/1403.1911v1)  
Luciano Gualà, Stefano Leucci & Emanuele Natale (2014). Bejeweled, Candy Crush and other Match-Three Games are (NP-)Hard, arXiv: [1403.5830v1](http://arxiv.org/abs/1403.5830v1)