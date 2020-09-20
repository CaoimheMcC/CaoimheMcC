+++
showonlyimage = false
draft = false
image = "img/portfolio/IvyScene.jpg"
date = "2016-11-05T18:25:22+05:30"
title = "  Procedural Ivy Generator HDA"
weight = 0
+++


This project demonstrates the generation of a Houdini Digital Asset for ivy growth.  This procedural tool can generate a variety of different scenes based on user defined parameter values.  The ivy is generated using a sort of particle based method first introduced in 1985 by Reeves and Blau [1].  <!--more--> Using this as the basis for the growth algorithm, the HDA also simulates external tropisms such as gravitropism and phototropism. Along with the ability to automatically generate ivy, this tool allows the user the more stylistic approach of drawing ivy directly onto the environment geometry. This highly art-directable procedural tool demonstrates an easy way to generate climbing ivy.

The HDA was primarily created using the Houdini expression language, VEX. The full thesis report can be found [here](https://nccastaff.bournemouth.ac.uk/jmacey/MastersProject/MSc20/05/index.html).



{{<vimeo 450938534>}}  <br/>

**References**

[1] *Reeves W. T. and Blau R., 1985. Approximate and probabilistic algorithms for
shading and rendering structured particle systems. SIGGRAPH ’85, New
York, NY, USA. Association for Computing Machinery, 313–322*