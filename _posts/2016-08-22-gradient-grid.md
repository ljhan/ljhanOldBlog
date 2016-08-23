---
tags: [code]
title: Gradient Grid
header:
  teaser: tengradient.png
---

On tumblr, there are a quite few blogs dedicated to showcasing gorgeous gradients, and since I love the look of gradient grids, I wanted to have a simple solution to generating them. A simple Google search yields a <a href="http://enjoycss.com/gallery/gradient_patterns/hA" target="_blank">CSS generator</a>.  

With this code to start with, I began by resizing the grid to 500x500px and separating hellaciously long lines of code into more manageable chunks.  I then started to go through the code, taking things out and putting them back in then changing values, all the while adding plenty of comments to help me understand how it all works.  Once I had a solid grasp of the code, I added my own twists to it (nothing big) - adjusted some of the color stop values for the gradients and setting up two color variables (changing the RGB values for each and every instance would be such a headache).

After I recreated a cleaner, more efficient 5x5 gradient grid, I tackled modifying the code to make a 10x10 grid.  Had to add many more lines of code for the additional gradient stripes, and played around with the color stop values (particularly the alpha values) to get an even color distribution I was satisfied with.  

Overall, I'm happy with this!  Nothing crazy or fancy, but something I've always wanted to make.  Peek the <a href="https://github.com/ljhan/Gradient-Grid" target="_blank">repo</a> and the results below!  

5x5
![Alt text](gradient2.png)

10x10
![Alt text](tengradient.png)
