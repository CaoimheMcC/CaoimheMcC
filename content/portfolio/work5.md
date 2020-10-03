+++
showonlyimage = false
draft = false
image = "img/portfolio/spreadGrowth.jpg"
date = "2016-11-05T18:25:22+05:30"
title = " Growth Simlutaions"
weight = 0
+++

The video here demonstrates several different growth algorithms implemented in Houdini. Each are done using the VEX programming language. <!--more-->  

The growth algirthms used are Diffusion Limited Aggregation (DLA) and an infection spread effect. 

Put simply, DLA refers to a noisy growth restricted by diffusion. The algorithm is relatively easy to visualise in 2D, consider a seed or particle placed in a fixed location on a grid. Using this principals of DLA described in [1] as a foundation, futher customisations were made, such as adding specific noise and probability.

Infection spread effects are used frequently in the industry. Similar to DLA, the infection effect begins with one infected point and spreads iteratively to its nearest
neighbours. The variables created when implementing an infection spread can be modified to generate whatever visual reuslts an artist may require.

Simple geometry was used to demonstrate the growth patterns. The procedural methods used could be implemented using high-poly geometry for a more finished peice. 


{{<vimeo 458149989>}}   <br/>  

**References**

[1] *Sander L., 11 2010. Diffusion-limited aggregation: A kinetic critical
phenomenon? Contemporary Physics, 41, 203–218*

[2] *Witten T. and Sander L., 1981. Diffusion-limited aggregation, a
kinetic critical phenomenon. prl, 47, 1400*