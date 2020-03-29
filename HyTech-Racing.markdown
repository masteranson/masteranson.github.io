---
layout: page
title: HyTech Racing 🏎
permalink: /HyTech Racing/
---

<script>
function resizeIframe(obj) {
  obj.style.height = obj.contentWindow.document.body.scrollHeight + 'px';
}
</script>

<h1 style="color: #5e9ca0; text-align: justify;"><span style="color: #000000;">
  I lead a team of over 20 undergraduate/graduate students in the design, manufacture and testing of a 5kWh battery pack
  for the <a href="https://www.sae.org/attend/student-events/formula-sae-electric/about">Formula SAE electric competition</a>.
</span></h1>
---
<br />

<p align="center">
  <img width="auto" height="auto" src="/assets/photo30.JPG">
</p>

<br />


### The Design
---
<div align="justify">
The issue of keeping the battery temperature within an accepted operating range is one of the biggest issue that even teams in Formula E regularly faces.
However, all teams are required to use the same battery pack designed by McLaren Applied Technologies.
In those cases, the way the car is driven becomes an important element in maintaining battery temperature.
Instead, our lightweight convective air cooling system dissipates enough heat to allow the driver to push the car without having to <a href="https://www.formula1.com/en/latest/article.a-beginners-guide-to-f1-slang.1Pg6tvGZ2y7u4KAnc8WXGl.html">"lift and coast"</a>.
<br />


<iframe src="https://masteranson.github.io/jekyll-slideshow/slides/my-pics4.html" onload="resizeIframe(this)" width="100%" scrolling="no" style="border: none;" ></iframe>


With sufficient cooling, we can safely adopt an extreme 72s1p <img width="auto" height="auto" src="https://render.githubusercontent.com/render/math?math=LiCoO_%7B2%7D"> cell configuration, taking our pack voltage to over 300V.
To both attenuate high frequency vibration and maximize cycle life, 10psi of compression is uniformaly applied to every cell under ~10% cell expansion using non-linear Bisco BF-2000 scilicone foam.
With no parallel circuitry, this simplifies both the mechanical and electrical systems, while not compromising on power.
The battery pack is also designed to be highly serviceable, with 4 modular battery segments and power electronics. Significant weight was also saved by switching to all aluminum high current bus-bars.
</div>

<iframe src="https://masteranson.github.io/jekyll-slideshow/slides/my-pics5.html" onload="resizeIframe(this)" width="100%" scrolling="no" style="border: none;"></iframe>


<center>
  <iframe src="https://www.facebook.com/plugins/post.php?href=https%3A%2F%2Fwww.facebook.com%2FHyTechRacing%2Fposts%2F2506645326071881&width=500"
width="500" height="764" style="border:none;overflow:hidden" scrolling="no" frameborder="0" allowTransparency="true" allow="encrypted-media"></iframe>
</center>



### Bringing the beast to life
---
<div align="justify">
Putting together the battery pack requires sourcing and manufacturing thousands of components with an extremely limited budget.
A lot of our custom components are manufactured in house, including the cell withstraining plates at each ends of a battery module. After optimizing the part using FEA static analysis
 to reduce weight while maintaining machinability and minimal deflection, we program the CAM to manufacture the parts on a Haas 3-axis CNC mill. <br />

<iframe src="https://masteranson.github.io/jekyll-slideshow/slides/my-pics6.html" width="100%" scrolling="no" style="border: none;" onload="resizeIframe(this)"></iframe>

<br />

However, as a student team we do not have access to all of the various manufacturing equipment to make every piece. Instead we rely on the support of our sponsors, located
all over the US, for their assistance. I directly coordinate manufacturing with local and international OEM manufacturers, some of them shown below. <br />
<iframe src="https://masteranson.github.io/jekyll-slideshow/slides/my-pics2.html" onload="resizeIframe(this)" width="100%" scrolling="no" style="border: none;" ></iframe>

<br />

But perhaps the most exciting development of this season is our partnership with Melasta Co Ltd, a small battery manufacturer from China. Due to our unique geometric and performance requirements,
there are no suitable battery cells that is perfect for our application. Instead, we needed to work with a company who is willing to work with us to engineer and develop a custom cell. <br />
<iframe src="https://masteranson.github.io/jekyll-slideshow/slides/my-pics1.html" onload="resizeIframe(this)" width="100%" scrolling="no" style="border: none;"></iframe>

After fully characterizing the performance characteristics of every cell, the data is directly used in our real time state-of-charge estimation model:

<p align="center">
  <img width="200" height="auto" src="/assets/photo35.png">
    <figcaption>Initial SOC determined from SoC vs. OCV lookup table stored in EEPROM.</figcaption>
</p>


<br />

Ultimately, the 2020 competition transitioned to an 'online' event format due to the COVID-19 Pandemic.
Along with school cancellation, I was unable to complete the battery pack as of {{ site.time | date: '%b %d, %Y' }}. <br />

<br />
You can still check the team out on: <a href="http://hytechracing.gatech.edu">HyTech Racing</a>


</div>
