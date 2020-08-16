---
layout: page
title: AMPD Energy
permalink: /AMPD Energy/
---

<h3>  Mechanical Engineering Intern at <a href="https://www.ampd.energy"> AMPD Energy</a> </h3>

<p align="center">
  <img width="auto" height="auto" src="//masteranson.github.io/assets/photo6969.jpg">
  <h6 > Group photo with the entire AMPD team during our Friday happy hour!</h6>
</p>


<div align="justify">
I am very fortunate to have such an amazing experience at AMPD Energy during the Summer of 2020. As part of a small mechanical engineering team, I was able to hold direct responsibility in a multiple projects. In particular, I was able to utilize different modeling techniques to analyze the thermal performance of the Enertainer, a lithium ion battery replacement for diesel generators. By taking two different approaches to thermal modeling, we were able to identify key bottlenecks in the existing system and identified key components that could benefit significant from a top-down redesign. I was also involved with various structural redesigns within the battery compartment that lead a weight saving of over 200 kilograms!
</div>

<br />

## Lumped-Element Dynamical Model

---

<div align="justify">
My primary project during the internship was determining what influences the temperature the most. Whether it was due to ohmic heating of the battery cells, or from external environmental factors. By utilizing  <a href="https://pvpmc.sandia.gov/applications/pv_lib-toolbox/"> PV-Lib</a> and <a href="https://www.mathworks.com/products/simscape.html"> Simscape</a> libraries on MATLAB, we were able to develop a data driven, multi-physics thermal model to study the dynamical response for the Enertainer. By incorporating field data collected through the on board thermistor sensors, as well as <a href="http://www.cityu.edu.hk/bst/BEET/project_page/research%20projects/typical%20weather%20year/typical%20weather%20year.htm?AspxAutoDetectCookieSupport=1"> typical meteorological year data</a>, we were able to model the temperature fluctuations observed over a time period of months. By parameterizing various different conditions, we believed that this model reviews solar radiation as the main cause of the cyclical temperature variations observed during outdoor operation.
</div>

<p align="center">
  <img width="auto" height="auto" src="//masteranson.github.io/assets/Picture1.png">
  <h6 > High level model implementation in Simulink</h6>
</p>

<br />

## Conjugate Heat Transfer CFD Model
---
<div align="justify">
A natural progression would then be to study the efficiency of our existing cooling system. Ensuring homogeneity in temperature distribution across the pack is paramount in order to extend the cycle life of lithium batteries. To study the efficiency of our convective pack cooling system, a heat transfer CFD model was implemented on ANSYS to determine the surface heat transfer coefficient values, and even using the result back in our dynamical model.
</div>

<p align="center">
  <img width="auto" height="auto" src="//masteranson.github.io/assets/FLU.png">
    <h6 > Side view of air velocity render from CFD-Post</h6>
</p>
