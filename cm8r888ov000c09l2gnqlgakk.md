---
title: "Looking through an opaque material"
datePublished: Fri Nov 09 2012 10:16:00 GMT+0000 (Coordinated Universal Time)
cuid: cm8r888ov000c09l2gnqlgakk
slug: looking-through-an-opaque-material

---


posted by @ulaulaman about #JacopoBertolotti #physics #optics #opaque #matter

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743072265738/3580fbab-f5bb-43bf-9918-27442dc3777a.jpeg)

_I am proud to publish a feature article about the research word of a [Wikipedia's friend](http://it.wikipedia.org/wiki/Utente:Jb) like **Jacopo Bertolotti**. The work was finally published on "Nature", that decided also to honor the paper with the cover.  
I admit to have received the paper a couple of weeks ago, so I hope to have made ​​a good service to Jacopo and all of his colleagues._  
  
Recently one of my students asked me why glass is transparent while other materials are not. Its transparency is substantially due to the interaction between the electrons of the glass and the incident light, and so from the interaction between the photons (or electromagnetic radiation) and matter. A photon, when it interacts with matter, can be [absorbed, reflected or continue on its way without change](http://science.howstuffworks.com/question4041.htm). These different behaviors are due to the energy levels occupied by the electrons of the atoms that constitute matter, in particular by the energy difference between these levels. We know, thanks to the photoelectric effect and [the explanation given to it by Einstein](http://en.wikisource.org/wiki/On_a_Heuristic_Point_of_View_about_the_Creation_and_Conversion_of_Light), that the electrons are excited by the incident photons only if the energy of these photons is equal to (or greater than) the energy required to jump to another level. This means that if the light does not excite the electrons of the material, this is transparent to its passage, just as occurs in the glass: the visible light, in fact, has not enough energy to excite the electrons of the glass, which is therefore transparent to its passage, despite the rays of light are reflected.  
Now, if we take a sheet of glass and do hit by light from one of its ends, a part of the rays will be reflected and then detected by a device (such as our eyes) placed for example at the opposite end. Not all reflected rays, however, follow an equal path and therefore not all the rays reach the eyes at the same time.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743072266941/085c07bc-9724-4392-a9a3-237ccc788435.jpeg)

Something similar also occurs when light passes through the glass of our windows: the light rays don't travel all at the same speed.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743072268307/5b2fd170-4b5e-40ea-a7f3-4c0238c216ee.jpeg)

In order to enable to all the rays of light to reach the detection point at the same time one can construct a structure which gradually tapering as it approaches the ends, i.e. it builds a lens.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743072269561/0753cf09-48de-4b04-92b9-972ac1ef9a7e.jpeg)

One of the ways to use a lens is for example for the magnification of objects, but not all magnifications can be made using the lenses that take advantage of the visible light. If, for example, we have some objects that are at a scale of less than 200 nm, the usual optical lenses are not able to resolve their details. Unless you build a **HIRES**(1) (_High Resolution Enhancement by Scattering Index_) lens.  
This lens, developed by the group of **van Putten** and **Bertolotti** (our Jacopo!) consists of:

> (...) of a homogeneous slab of high-index material on top of a strongly disordered scattering layer. The disordered layer breaks the translational invariance of the interface, which enables incident light to be coupled to all propagating angles inside the highrefractive-index material as shown in figure.
> 
> ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743072270934/a1fc9f5f-c50e-4dfd-82ec-3fbbe33e06d0.jpeg)
> 
> Yet multiple scattering also scrambles the wavefront creating a speckle-like pattern on the object plane that itself cannot be used for imaging. Therefore we manipulate the incident wavefront in order to force constructive interference of the scattered light at a position in the object plane of our HIRES-lens.(1)

The lens developed by Dutch laboratories [COPS](http://cops.nano-cops.com/) is able to detect gold nanoparticles of the order of 100 nm or less, as you can see in the picture below that compares the observation of these particles with a magnifying glass commercial high quality (left) and with the HIRES(1) (right):

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743072271981/71e5fcf6-2237-4332-ba4a-59e0b84743e9.jpeg)

But if we want to observe an object in the sky hidden by the clouds, we can enlarge the portion of the sky until we want, but we will never take more than a few details. In fact **JR Fienup**, thinking about atmospheric turbulence, developed a modified version of the [Gerchberg-Saxton algorithm](http://en.wikipedia.org/wiki/Gerchberg%E2%80%93Saxton_algorithm)(2).  
The idea is simple: every object, even hidden, sends light information that we are able to detect, but may not be sufficient to give us an idea of ​​the shape and details that characterize it. Then it is possible to derive this information extracting them with a suitable iterative algorithm starting from the Fourier transforms of the scattered light(2).  
The method, already tested by Fienup, has recently been refined and adapted again at the COPS for the detection of objects in the order of micrometers(3) or even nanometer, like **Allard Mosk** stated in the [official press release](http://www.utwente.nl/en/archive/2012/11/looking_through_an_opaque_material.docx/):

> This will be very useful in nanotechnology. We would like to bring structures to light that are hidden inside a complex environments like computer chips.

Let suppose you have a fluorescent object completely hidden by an opaque screen with respect to the scattering of light. One way to reconstruct the hidden object is

> (...) to separate the small amount of light that did not change direction owing to random scattering (ballistic light) from the scattered background using a gated technique such as optical coherence tomography.(3)

In this way it is possible to recover the information within a semi-transparent means, but it is very difficult, if not impossible, to use non-invasive methods with increasing diffusion. You could use diffuse optical tomography, but this only allows the location of the object but not the reconstruction of the details. The idea then becomes to retrieve the details thanks to the correlations in scattered light.  
In order to retrieve this information you must first hit the object, which in this case was modeled in the form of $\\pi$, with the laser light that pass through the opaque surface. What we get from scattered light, however, is something quite incomprehensible, if we observe results with naked eyes:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743072273358/d9021183-70c8-4fcc-ab00-56772a28c6bb.jpeg)

At this point the iterative algorithm is used to retrieve the correlations between the points of the previous figure and from these correlations researchers retrieve the details of the object itself:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743072274775/dc13dc32-6e0a-4d20-a1e4-7067515b0829.jpeg)

The method, however, has enormous potentials: it was also tested with a complex biological structure as the stem of _Convallaria majalis_ (lily of the valley) and the results are very encouraging:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1743072275848/fd1af8e3-b984-4fa7-8eb4-2faf70afc284.jpeg)

If the main limitation of the method is dued

> (...) by the background signal, which can distort the measured autocorrelation(3)

possible future developments of the technique are therefore the detection of small subcutaneous structures, and possible subsequent medical applications.  
The research, finally, also received the honor of the cover of _Nature_ released two days ago and the draft title of this post was _A Wikipedian on the cover of Nature_. When I talked to Jacopo, he timidly remmbered me that he was no longer an active Wikipedian, but as far as I'm concerned, paraphrasing the famous Avengers,

> Once a wikipedian, always a wikipedian!

* * *

P.S.: the first three images are from the book _QED_ by **Richard Feynman**

* * *

**Video**: Why is glass transparent?

* * *

(1) van Putten, E., Akbulut, D., Bertolotti, J., Vos, W., Lagendijk, A., & Mosk, A. (2011). Scattering Lens Resolves Sub-100 nm Structures with Visible Light Physical Review Letters, 106 (19) DOI: [10.1103/PhysRevLett.106.193905](http://dx.doi.org/10.1103/PhysRevLett.106.193905) ([arXiv](http://arxiv.org/abs/1103.3643))  
(2) Fienup, J. (1978). Reconstruction of an object from the modulus of its Fourier transform Optics Letters, 3 (1) DOI: [10.1364/OL.3.000027](http://dx.doi.org/10.1364/OL.3.000027) ([pdf](http://mit.edu/joke021/Public/Spring%202012%20:%20Spatial%20Light%20Modulators/GerchbergandSaxton.pdf))  
(3) Bertolotti J., van Putten E.G., Blum C., Lagendijk A., Vos W.L. & Mosk A.P. (2012). Non-invasive imaging through opaque scattering layers, Nature, 491 (7423) 232-234. DOI: [10.1038/nature11578](http://dx.doi.org/10.1038%2Fnature11578)