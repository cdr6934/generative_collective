---
title: "Can we use Simplex Noise to Generate Music?"
date: 2020-12-19T17:00:04-06:00
draft: false
---
> Life is full of beauty. Notice it. Notice the bumble bee, the small child, and the smiling faces. Smell the rain, and feel the wind. Live your life to the fullest potential, and fight for your dreams. - **Ashley Smith**


I have to say that this is going out a little later than usual, but I think you will find some of the articles today to be much more in the details around simplex noise and the like but not all. There is always a little bit of everything. As for now, I wanted to put the following out there.

I've been following a community of virtual instrument designers using analog media to generate digital tools. This community is called [Pianobook](https://www.pianobook.co.uk/).

![](/images/010/010_2.png)

I don't know how many of you have come across Pianobook but this is an exciting project that I have been wanting to see experiments with the two communities. Pianobook is a collection of sampled instruments built in [Kontakt](https://www.native-instruments.com/en/products/komplete/samplers/kontakt-6/) by [Native Instruments](https://www.native-instruments.com/en/). Essentially these are Kontakt users, that use their analog recording equipment and load it into a sampler (Kontakt) from which instruments are then made. 

The downside is that the sampler isn't cheap ($399) full retail. But there are ways to get to it. Anyways, I feel like there is alot more that can be done with things such as simplex noise, rhythm, and sampled instruments that have yet to be discovered and tried. Probably mostly due to the fact the tools to connect the two together isn't quite there yet. The best tool on the market to do some of these projects are Max MSP and Max for Live by [Cycling 74.](https://cycling74.com/) Again another tools that has to be bought which isn't helpful. 

I have come across the following tools called [RenderMan](https://github.com/fedden/RenderMan) and there are some interesting possibilities that could be used with the library since you'd be able to use the library as an interface to a VST. There are other interesting libraries / systems as well such as: 

- [chucK](https://chuck.cs.princeton.edu/) - ChucK is a programming language for real-time sound synthesis and music creation. It is open-source and freely available on MacOS X, Windows, and Linux. ChucK presents a unique time-based, concurrent programming model that's precise and expressive (we call this strongly-timed), dynamic control rates, and the ability to add and modify code on-the-fly.
- [SuperCollider](https://supercollider.github.io/) - "SuperCollider is a platform for audio synthesis and algorithmic composition, used by musicians, artists, and researchers working with sound. It is free and open source software available for Windows, macOS, and Linux."
- [Sonic Pi](https://sonic-pi.net/) - Sonic Pi is a code-based music creation and performance tool.
- And [others](https://github.com/ciconia/awesome-music)..

But I find most of the time they are working with synthesizers and oscillators which is facinating work. I just want to see more of the convergence of instruments and then put to the test the exploration of simplex noise and a recorder for example.

 What would that sound like and how can we then use it to further the discovery of "generative music" and physical instruments? 

I think that many modern composers have done an amazing work mixing in synths into the traditional orchestra such as most great modern film composers. [Hans Zimmer](https://en.wikipedia.org/wiki/Hans_Zimmer), [Junkie XL](https://en.wikipedia.org/wiki/Junkie_XL) and others pushed us into that world rather beautifully and then we continue to see the practice in [Olafur Arnalds](https://en.wikipedia.org/wiki/%C3%93lafur_Arnalds),  [Hildur Gudnadottir](https://en.wikipedia.org/wiki/Hildur_Gu%C3%B0nad%C3%B3ttir) and others. 

But how can we take an instrument that has been sampled, create other worldly patterns in the digital space and then bringing it back to the physical. 

Can we remove the static or predictiable and moving to something that is unacheivable for the human yet continues to sound human? 

And then to take it yet a step further; can we can an entire recording, all tracks and then mutate it in such a way that will generate yet another level of complexity and beauty beyond the pages that we have taken to date. 

Maybe there are more advancements out there than I am already aware of. Reach out to me and let me know what you think. Other ideas that you also might have, and then 

## Code of the Week

![](/images/010/010_4.png)

You will find the code [here](https://gist.github.com/cdr6934/995cb13b974306dee84dfd52066cbb92)

# Inspirations

## Featured Artist

### Sage Jenson

I'm a Berlin-based artist interested in constructing realities. My research involves biocomputation and tactile interaction. I build interactive audiovisual systems and cultivate digital / physical creatures.

![https://payload.cargocollective.com/1/18/598881/13802463/COMET_1080.jpg](https://payload.cargocollective.com/1/18/598881/13802463/COMET_1080.jpg)

The following images come from their collection called mesh creation. These are more "architectural" but have a method of fluidity that make inorganic shapes look extremely organic.  They write about it their proceeding [here](http://archive.bridgesmathart.org/2016/bridges2016-411.pdf). 

---

![https://payload.cargocollective.com/1/18/598881/11312376/BIG_1340_c.jpg](https://payload.cargocollective.com/1/18/598881/11312376/BIG_1340_c.jpg)

![https://payload.cargocollective.com/1/18/598881/11312376/figure_2_1340_c.jpg](https://payload.cargocollective.com/1/18/598881/11312376/figure_2_1340_c.jpg)

![https://payload.cargocollective.com/1/18/598881/11312376/figure_3_3840.jpg](https://payload.cargocollective.com/1/18/598881/11312376/figure_3_3840.jpg)

[Twitter](https://twitter.com/mxsage) / [Instagram](https://www.instagram.com/mxsage/) / [Website](https://sagejenson.com/About)



# 🖌️ Unconventional Media

{{<youtube T0Joqn-Bsw>}}

> Jeff discusses his studio setup, his film projects, and his practical solutions for improving his workflow with Max. Video by Jeff Rona, with additional editing by Ron MacLeod.


{{<youtube vxwP3rFNEaA>}}


> TechGloves is a new interface for musical expression with several different sensors that allow its users to intuitively control audio and musical parameters in a VST – such as the cutoff frequency of a filter, the signal’s panning in a stereo sound field, and the modulation index of a frequency modulated signal.

{{<vimeo 58337434>}}


> Generative Music using FaceOSC, Logic Pro, Osculator, and two handmade Logic Pro instruments.

# 📸 Generative Graphics

{{<vimeo 374483091>}}


> Typography is a way of visualizing language (Cheng, 2006). As designers,it gains even more importance to us as it adds a layer of content. The choice and use of a font gives indications regarding the subject we are addressing. In order to use typography in the best way, many designers study their anatomy and ways to categorize it.

With the digital revolution appeared the personal computers and tools that came to facilitate the design of fonts. As a result, more fonts appeared, but with them the uncertainty of their quality. It is necessary to create tools that established a balance between what the user can determine and what the system does autonomously. On the other hand, the society in which we live is dependent on personalization. Suggestions according to our views become increasingly a requirement on social networks.

# 🏛️ Exhibits / Installations

## [Genuary 2021](https://genuary2021.github.io/) a.k.a Inktober for Generative Artists


![](/images/010/010_5.png)

# 🚤 Motion

{{<vimeo 349935082>}}

## [Saristra](https://saristrafestival.gr/saristra-2019)

> A trailer for the Saristra Festival in 2019; the page is in greet

I just think the point scans (probably LIDAR) really have a beautiful feel to it and is on my "next things to try" list. Well that is after I start using TouchDesigner/Unity as I need to work a little more closely in 3D space. 

# 🔖 Articles and Tutorials

![](/images/010/010_1.png)
## [Simplex Noise Demystified](http://staffwww.itn.liu.se/~stegu/simplexnoise/simplexnoise.pdf)

> In 2001, Ken Perlin presented “simplex noise”, a replacement for his classic noise algorithm. Classic “Perlin noise” won him an academy award and has become an ubiquitous procedural primitive for computer graphics over the years, but in hindsight it has quite a few limitations. Ken Perlin himself designed simplex noise specifically to overcome those limitations, and he spent a lot of good thinking on it.

This paper was insightful and helped really understand what is happening in the simplex noise function. (i.e. noise() in Processing) from a mathematics POV. The noise function is so important to generate aesthetically pleasing randomness. This also helps, if you are so inclined, to perhaps find other ways to randomize such things. 

![https://alessandrocuzzocrea.com/how-i-made-a-ray-tracer/ray-tracer-final-render.jpg](https://alessandrocuzzocrea.com/how-i-made-a-ray-tracer/ray-tracer-final-render.jpg)

## [How I Made a Ray Tracer](https://alessandrocuzzocrea.com/how-i-made-a-ray-tracer/)

> The goal of this particular project is to be able to create a simple ray tracer software tool that will be able to produce some cool images.
Ray tracing is a technique used to generate a two-dimensional image from a tri-dimensional model, and a ray tracer is a piece of software that performs ray-tracing calculations.

---

# Courses


![](/images/010/010_3.png)
## [WebGL Fundamentals](https://webglfundamentals.org/)

> These are a set of articles that teach WebGL from basic principles. They are NOT old rehashed out of date OpenGL articles like many others on the net. They are entirely new, discarding the old out of date ideas and bringing you to a full understanding of what WebGL really is and how it really works.

# Books

## [Music Generation w/ Magenta](https://amzn.to/3pkQKH1)

The importance of machine learning (ML) in art is growing at a rapid pace due to recent advancements in the field, and Magenta is at the forefront of this innovation. With this book, you'll follow a hands-on approach to using ML models for music generation, learning how to integrate them into an existing music production workflow. Complete with practical examples and explanations of the theoretical background required to understand the underlying technologies, this book is the perfect starting point to begin exploring music generation.

 

Attached is a list of books that are [devoted to the generative arts.](https://github.com/cdr6934/awesome-generative-books) 

# Send me your inspirations...