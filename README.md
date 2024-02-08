# Week02-Noc-Vector-Noise 

Question: Better ways to "move" through the noise space? Create better visualizations of movement.
Registering a 3D grid to a 1D array - Numbering a 3D grid properly.

In three.js a lot of the creation of things is done through objects and its positions are recorded using 3d vectors with x,y,z values. So I decided to try and investigate using noise with three.js. I found a [noise node package](https://www.npmjs.com/package/simplex-noise?activeTab=readme) and incorporated it into this project. I don't think the effect I have created here is exactly what I intended as the animation here updates too fast and randomly. So I then updated it to create an XYZ coordinate within the noise space and move through it instead of just constantly increasing the offset. However, now I have created an effect where my noise cube seems to be divided into slices. I'm guessing that this problem is due to the way I created an array within a triple for-loop and will need to investigate the assignment of variables more.

[Link to page](https://dannoblem.github.io/Week02-Noc-Vector-Noise/)


Project that uses vectors as a force: [Symbiosis](https://github.com/DanNoblem/SymbiosisThreeJS)
