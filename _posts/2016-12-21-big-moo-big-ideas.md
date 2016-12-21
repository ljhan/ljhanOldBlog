---
published: false
---
tags: [code]
title: Big Moo, Big Ideas
header:
  teaser: big-moo-egg.png

<img src="{{ site.url }}{{ site.baseurl }}/images/big-moo-egg.png" alt="">
<img src="{{ site.url }}{{ site.baseurl }}/images/big-moo-cat.png" alt="">
<img src="{{ site.url }}{{ site.baseurl }}/images/big-moo-dog.png" alt="">
<img src="{{ site.url }}{{ site.baseurl }}/images/big-moo-shapes.png" alt="">

Throwback to <a href="http://wildhacks.org/" target="_blank">Wildhacks 2016</a>!  Hosted at Northwestern, this was the first hackathon I attended back in 2014.  Now, this is my 5th hackathon :)  My best friend from high school <a href="https://github.com/gmnicke2" target="_blank">G</a> came from UIUC to make something cool, and we wanted to keep the project relatively lowkey - we just wanted to have fun, especially with the increasingly intense pressures from school (heh).  Since receiving my <a href="https://vr.google.com/cardboard/" target="_blank">Google Cardboard</a> at Grace Hopper, I've really wanted to make music-related VR experience for the platform.

Let's get down to our process, shall we?

## Friday, November 18th 2016
- We found a really amazing library for making VR experiences using web technology, <a href="https://webvr.info/" target="_blank">WebVR</a>, and from this we found the framework we would ultimately use, <a href="https://aframe.io/" target="_blank">A-Frame</a> (It's pure magic!!! Do check out their dazzling samples)
- After forking the A-Frame repo, we began brainstorming concepts (including: sampling beats on 3D objects, visualizing music in VR, incorporating moos and quacks (some longrunning jokes between us), and creating a music player with 'sick visuals')
- We familiarized ourselves with the framework by playing around with the Hello World demo and the provided boilerplate
- and created a Slack channel to keep all of our links and files neatly organized in one place

(no, we did not pull all nighters - 36 hours are brutal)

## Saturday, November 19th 2016
- We set up our repo with a Github pages branch (had to brush up on my git!)
- and tested the Hello World demo
- For our music, we selected and downloaded various sample packs from <a href="https://primeloops.com/" target="_blank">Prime Loops</a>, and then combed through them to find suitable tracks and sound bites
- Now, the learning phase - we went through the tutorials and documentation, slowly picking apart the Metaverse demo, changing and adding entities (mostly geometric shapes) to the scene 
- We figured out how to change the "sky" to a custom galaxy background, as well as make entities animated and interactive (finally we can play music!)
- There are several types of interactive shapes in our scene: 
	>1. a loopy, morphing overhead "sun" shape that continuously plays a looping track
    >2. several linked geometric shapes playing samples that are controlled by a central shape that acts like a switch
    >3. other spinning geometric shapes that play 
    
Overall, I was blown away by how much A-Frame streamlines the process of creating a VR experience!  I've taken a computer graphics course

<a href=“https://devpost.com/software/big-moo-big-ideas” target=“_blank”></a>
<a href=“https://gmnicke2.github.io/big-moo-big-ideas/” target=“_blank”></a>