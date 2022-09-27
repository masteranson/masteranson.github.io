---
layout: page
title: Modeling Evaporation
permalink: /Molecular Dynamics/
---
### Evaporation Kinetics of Nano Water Droplets using Coarse-Grained Molecular Dynamic Simulations
---
<div align="justify">
I worked as a research assistant in the <a href="http://newri.ntu.edu.sg/Research/NEWRI%20Research%20Domain/EPMC/Pages/Overview.aspx">Environmental Process Modeling Centre</a> at
Nanyang Environmental and Water Research Institute in Singapore between June-August 2018 and May-July 2019.
One of my primary research focus was on some of the science behind interfacial water evaporation.
My research was only possible with my fortunate opportunity to use the Nanyang Technological University's
High Performance Computing Centre to run large scale simulations using <code>LAMMPS</code> .<br />
</div>
<br />

<p align="center">
  <img width="auto" height="auto" src="/assets/photo6.JPG">
  <figcaption>Internal presentation of my research findings to the entire Environmental Process Modeling Centre</figcaption>
</p>

<div align="justify">

Molecular dynamic simulations are the basis of the <a href="https://foldingathome.org/">Folding@Home</a> project, which directly models every single atomic interactions of a protein biomolecule. By simulating a nanoscale system, we can take meaningful statistical averages and interpret the phenomena in macroscopic terms. Though I am not qualified to explain why the data from this type of numerical modeling has any validity in real life, this <a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2800798/pdf/nihms-127989.pdf">paper</a> may provide good insight on this topic.


<p align="center">
  <img width="600" height="auto" src="/assets/photo420.jpg">
  <figcaption>A visualization of the model setup using `VMD`. Approximately 80000 ELBA coarse-grained water molecule was allowed to 'exist' for more than 4 million time-steps.</figcaption>
</p>

As with any computational studies model validation is critical, especially if results are to be meaningfully interpreted. Therefore, we have chosen a well validated coarse grain water model, considering the computational expense and level of accuracy required. Furthermore, we applied various relaxation techniques and measured the bulk vapor pressure and found it in good agreement with empirical values.

<p align="center">
  <img width="600" height="auto" src="/assets/photo106.png">
</p>

One of the biggest accomplishment from this computational study was the ability to visualize thermodynamic properties that is not very well-defined in this simulation environment. We elucidated an evaporation process that is very difficult to replicate in physical experiments. As shown in the figure below,
 a pressure gradient across the interfacial boundary relaxes as net evaporation flux approaches zero.<br />

<br />

Read <a href="https://www.sciencedirect.com/science/article/abs/pii/S0017931019349750?dgcid=rss_sd_all"> Evaporation Kinetics of Nano Water Droplets using Coarse-Grained Molecular Dynamic Simulations</a> here.
</div>
