---
layout: page
title: ZK60 + REE
description: Expanding Tribological Insights on ZK60 Magnesium Alloys with Rare Earth Element Additions
img: assets/img/cover_ZK60_Project.jpg
importance: 3
category: research
related_publications: true
---

During the last year of my Master's program, I had a great opportunity to team up with the AMAs Research Group at MERC. They were looking for someone with a solid understanding of tribosystems and also experience in finite element (FE) modeling to support their ongoing research project. Since I had previously used Abaqus software to simulate mechanical problems and had been introduced to the concept of tribology in my Elasticity and Fatigue classes in 2017, it was a good fit.

Over a four-month period, I immersed myself in the subject, conducting an in-depth review of the literature and consulting with experts at MERC, KNTU, and University of Tehran. This prep work allowed me to quickly contribute to the AMAs team's research on the microstructural evolution and mechanical properties of ZK60 magnesium alloys containing rare earth (RE) elements like cerium (Ce) and yttrium (Y).

### The Research Focus:
The AMAs team's research centered on enhancing the mechanical properties of ZK60 magnesium alloy by investigating the impact of RE element additions (specifically Ce and Y) and varying extrusion ratios (ER) during processing. Their work explored how different concentrations of RE elements (1, 2, and 3 wt.%) and extrusion ratios (12:1 and 18:1) affected the alloy's microstructure and resulting tensile properties.

They found that alloys with 3 wt.% Ce and 3 wt.% Y, processed with an 18:1 extrusion ratio, demonstrated the most promising mechanical properties, achieving higher hardness and strength. However, the friction and wear behavior of these RE-containing ZK60 alloys was still an open question. This research gap became the focus of my contribution.

### My Role:
To address the unknown friction and wear performance of the developed alloys, I performed a series of tribological experiments using a pin-on-disc (PoD) tribometer. My objective was to evaluate the friction coefficients, wear rates, and dominant wear mechanisms for the ZK60 alloys with Ce and Y additions. I ran experiments under different loads to see how these RE elements affected the alloys' tribological performance in both mild and severe wear regimes.

Complementing the experimental work, I developed a finite element model using Abaqus software and a user-defined subroutine to predict wear behavior. This 3D model simulated the contact pressure generated during sliding, which was then used as an input for Archard’s wear equation to estimate wear depth for each alloy composition under various test conditions. The combination of experimental results and simulation data provided a more comprehensive understanding of the tribological performance of the developed ZK60 alloys.

<div class="row">
    <div class="col-sm mt-3 mt-md-0 text-center">
        {% include figure.liquid loading="eager" path="assets/img/ZK60_WearMechanism.jpg" title="Wear Mechanisms" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0 text-center">
        {% include figure.liquid loading="eager" path="assets/img/ZK60_Simulation.jpg" title="PoD Wear Model" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Summary of dominant wear mechanisms under different load regimes; Wear simulation procedure flowchart.
</div>

### Outcomes and Publications:
The results showed that adding 3 wt.% of Ce and Y significantly improved the wear resistance of the extruded ZK60 alloy, with Ce having a stronger effect. The FE simulations accurately predicted wear rates, matching the experimental data up to 85% in mild wear conditions, though the accuracy decreased to 75% in severe wear. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0 text-center">
        {% include figure.liquid loading="eager" path="assets/img/ZK60_WearRate.jpg" title="Wear Rate"
        class="img-fluid rounded z-depth-1 w-50 mx-auto" %}
    </div>
</div>
<div class="caption">
    Comparing experimental and simulation results of wear rate as a function of applied load for all studied alloys.
</div>
<style>
  .caption {
      margin-top: -10px; /* Adjust this value to control the gap */
      font-size: 14px; /* Optional: to customize the font size */
      color: #565B5F; /* Change this to any color you'd like (e.g., hex code, rgb, or named color) */
      text-align: center; /* Optional: Center the caption */
  }
</style>

This project not only expanded my research skills, but also led to concrete outcomes. We presented our findings at the iMat2019 conference and published two peer-reviewed journal articles {% cite banijamali2021Ce %}, {% cite banijamali2022simulation %}.

I also co-authored another article on the work hardening behavior of these developed alloys {% cite najafi2021WH %}.
<br>

This experience has not only deepened my knowledge in the field of tribology but also improved my skills in experimental design and FE modeling in this area. Working with such a skilled research team at MERC was a rewarding challenge, and I am pleased to have contributed to the advancement of knowledge regarding these advanced magnesium alloys.

