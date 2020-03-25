---
layout: page
title: Molecular Dynamics ⚛️
permalink: /Molecular Dynamics/
---
### Research Project: Evaporation Kinetics of Nano Water Droplets using Coarse-Grained Molecular Dynamic Simulations
---
<div align="justify">
I worked as a research assistant in the <a href="http://newri.ntu.edu.sg/Research/NEWRI%20Research%20Domain/EPMC/Pages/Overview.aspx">Environmental Process Modeling Centre</ a> at
Nanyang Environmental and Water Research Institute in Singapore between June-August 2018 and May-July 2019.
One of my principle investigations during that period were on some of the science behind interfacial water evaporation.
I was fortunate enough to be given the opportunity to use the Nanyang Technological University's
High Performance Computing Centre to run large scale simulations using <code>LAMMPS</code> .<br />
</div>
<br />

<p align="center">
  <img width="auto" height="auto" src="/assets/photo6.JPG">
  <figcaption>Internal presentation of my research findings to the entire lab</figcaption>
</p>

<div align="justify">

This simulation technique is the same as the <a href="https://foldingathome.org/">Folding@Home</a> project you may have heard of. Essentially by simulating a nanoscale system, we can take meaningful statistical averages and interpret the phenomea in macroscopic terms while assuming sufficient ergodicity.
Though I am not qualified to explain why we should trust the results from this type of numerical model, you can read more about MD <a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2800798/pdf/nihms-127989.pdf">here</a>.


<p align="center">
  <img width="auto" height="auto" src="/assets/photo420.jpg">
  <figcaption>A visualization of the model setup using `VMD`. Approximately 80000 ELBA coarsegrained water molecule was allowed to 'exist' for more than 4 million timesteps.</figcaption>
</p>

As with any computational studies model validation is critical, especially if any results were to be meaningfully interpreted. That is why we have choosen a well validated coarse grain water model,
 while keeping in mind computational expense and level of accuracy required. Furthermore, we applied various relaxation techniques and measured the bulk vapor pressure and found it in good agreeement with
 empirical values.

<p align="center">
  <img width="auto" height="auto" src="/assets/photo106.png">
</p>

One of the biggest discoveries from this computational study was it how we were able to visualize thermodynamic properties that is not very well defined in such a simulation environment.
We were able to elucidate an evaporation process that is very difficult to replicate in physical experiments. As shown in the figure below,
we see how a pressure gradient across the interfacial boundary relaxes as net evaporation flux approaches zero.

<br />

Detail findings are submitted in a manuscript to the International Journal of Heat and Mass Transfer pending acceptance.
</div>
