---
layout: blog_post
title: The Chaos Game
date: 2022-01-16 
tags: [math]
---

>I have been watching Numberphile from the last 3 years and everytime its something new and interesting from the wonderful community, However, except a few I hardly remember the concepts after days. Information overflow is real!

<!--more-->
Math is beautiful! It comes with a myriad patterns resembling nature. Some are quite obvious, while most of them are quite fascinating.

*"Mathematics is the Science of Patterns and nature exploits just about every pattern that there is."*
-*Ian Stewert*

>Hence I decided to write small scripts to validate the concepts taught in the videos and retrieve the information through this blog whenever I feel like. Thus this effort!


The Chaos Game is based on just interatively finding the mid-point concepts. I am following the Numberphile video by Brady word by word. You can watch Brady's video [here](https://www.youtube.com/watch?v=kbKtFN71Lfs). So, Let's go step by step :

**Step 1**: Randomly plot three points on a canvas. [*Make it truely random - Math doesn't care*]. Say he points are A, B and C.

**Step 2**: Mark a fourth point. Again let it be another random one. Let's say this point is "X".

**Step 3**: Roll a six-faced-dice.
*We have to make some rules here.*

- If the rolled dice shows 1 or 2. The next X will be the mid point between A and previous X.
- If the rolled dice shows 3 or 4. The next X will be the mid point between B and previous X.
- If the rolled dice shows 5 or 6. The next X will be the mid point between C and previous X.

<img class ="blog-inline-image" src="{{ site.baseurl }}/assets/images/chaos-game/image2.png" alt="image2" width='500'/>


**Step 4**: Repeat the steps a lot (?) of times (*may be 1000 or more*).

**Step 5**: Voila! You got the nice and preety pattern. Math did it.

<img class ="blog-inline-image" src="{{ site.baseurl }}/assets/images/chaos-game/chaos.gif" alt="chaos-game" width='500'/>

I have written the script using p5js. The code can be found [here](https://github.com/ReboreExplore/Math-and-Patterns/tree/master/Chaos%20Game). Try it out yourself!