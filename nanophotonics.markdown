---
layout: page
title: Leveraging the Coldness of Space
permalink: /nanophotonics/
---

<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id="MathJax-script" async
        src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js">
</script>

<h2 style="color: #5e9ca0; text-align: justify;"><span style="color: #000000;">
  Developing a super-white material that cools itself during the day
</span></h2>
---
<br />

<p align="center">
  <img width="700" height="auto" src="/assets/nanophotonics_2.png">
  <figcaption>Subfigure A is a 6"x6" ePTFE-P(VdF-HFP) bilayer radiative cooler. Subfigure B are scanning electron micrographs of the bilayer with both the top surface and cross-section in view. Subfigure C is the reflectance spectrum of the radiative cooler. The background shows a normalized solar spectrum, and atmospheric irradiance showing cooling potentials for different sky conditions.</figcaption>
</p>

<div align="justify">
The demand for sustainable cooling solutions is growing as climate change intensifies and energy consumption rises. Traditional cooling methods are energy-intensive and contribute to greenhouse gas emissions. Our study presents a novel, scalable design for a radiative cooler that operates without external energy by directly expelling heat to the coldness of space, even in conditions as extreme as the Saharan desert.
<br />
<br />

Daytime radiative cooling materials are an active field of academic research, and in general there are three limitations that prevented the widespread adoption of this technology: high conductive thermal resistance, scalability and stability against extreme weather. We addressed these limitations by designing a thin bilayer structure that is easily fabricated from commercially available materials typically used in extreme environments. This unique approach allows the us to achieve a high cooling power of ~50 W/m^2 under direct sunlight and humid conditions, while maintaining a largely scalable and stable design.

</div>

<br />


### Optical Design Strategy
---

<div align="justify">
To simplify the design process, we opted to seperate the structure into two distinct layers based on spectral regimes at which they operate. In the thermal wavelengths, we aimed to achieve a high emittance by leveraging the effective emissivity of a disordered structure. By leveraging a phase inversion process developed here at Princeton, we were able to create a porous polymer with a high emittance of 0.97 in the longwave infrared. For the bottom layer where solar wavelengths are of primary importance, to achieve an optimal reflecter by leveraging mie scattering, we needed to select a suitable disordered microstucture with the correct lengthscale and geometry. We leveraged FDTD simulations to calculate the scattering cross section of a variety of disordered structures and found that a porous polymer with a 1.5um lengthscale was optimal for our application.
</div>

<br />

<p align="center">
  <img width="850" height="auto" src="/assets/nanophotonics_1.png">
  <figcaption>The subfigure on the left shows the comparison in scattering efficiency between different microgeometries, and The subfigure on the right demonstrates the increase in emittance with effective medium approximation.</figcaption>
</p>

<div align="justify">
Lastly, we conducted outdoor experiments to demonstrate sub-ambient cooling performance in a rooftop setting by using a 6"x6" sample fabricated in our lab. On a hot, humid summer day at Princeton, the radiative cooler was placed on a cooling target and exposed to direct sunlight (~750 Wm^2), and we were able to measure an average of 2.26°C cooling below ambient temperature.
</div>

<br />

<p align="center">
  <img width="800" height="auto" src="/assets/nanophotonics_3.png">
  <figcaption>Experimental validation of radiative cooling performance in rooftop setting.</figcaption>
</p>

<div align="justify">
Read <a href="https://www.degruyter.com/document/doi/10.1515/nanoph-2023-0707/html?lang=en">Porous polymer bilayer with near-ideal solar reflectance and longwave infrared emittance</a> here.
</div>
