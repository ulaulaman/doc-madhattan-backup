---
title: "Mathgenerator Editions: Differential Analysis"
datePublished: Wed Oct 24 2012 15:27:00 GMT+0000 (Coordinated Universal Time)
cuid: cm8r88i74000x09kz5uxt8alh
slug: mathgenerator-editions-differential-analysis

---


After [the publications of some abstracts](http://docmadhattan.fieldofscience.com/2012/10/journal-of-mathgenerators-vol1-issue-1.html) (with the pdf version) from papers generated with [mathgen](http://thatsmathematics.com/mathgen/) and [scigen](http://pdos.csail.mit.edu/scigen/), Today I propose you a book generated with the [downloadable code of mathgen](https://github.com/neldredge/mathgen). I use the following code:

> ./mathgen.pl --product=book --mode=zip --output=mybook.zip --author="Gianluigi Filippelli"

In this way the software generates also the LaTeX code, and so I could eventually modify the book. For example I add a cover: first of all I generated it using [Magazine Cover](http://bighugelabs.com/magazine.php) generator. In order to add the cover, first of all I insert the following code in the preamble:

> \\usepackage{geometry}  
> \\geometry{top=0cm,bottom=0cm,left=0cm,right=0cm,nohead,nofoot}  
> \\usepackage{graphicx}  
> \\usepackage{calc}

And after I add the following code after \\begin{document}:

> \\frontmatter  
> \\pagenumbering{gobble}  
>   
> \\ begin{center}  
> \\includegraphics\[width=5.8in,height=8.8in\]{cover.jpg}  
> \\ end{center}  
>   
> \\newpage

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743072288022/6e2e6df0-92e3-4eb3-9a40-b42b9b20134c.jpeg)

In order to create an interactive pdf I also add the following package:

> \\usepackage{hyperref}  
> \\hypersetup{  
> pdfpagemode=UseOutlines,  
> %pdfstartview=FitV,  
> bookmarksopen,  
> bookmarksopenlevel=-1,  
> pdftitle=Differential analysis,  
> pdfauthor=Gianluigi Filippelli,  
> pdfsubject=mathematics,  
> pdfkeywords=mathematics  
> %pdfpagemode=FullScreen  
> }

You can download the results from [minus.com](http://minus.com/lbbPXGNe9BeWkf)  
I hope that you can enjoy yourselfs with mathgen and scigen!