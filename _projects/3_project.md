---
layout: page
title: ZK60 + REE
description: Expanding Tribological Insights on ZK60 Magnesium Alloys with Rare Earth Element Additions
img: assets/img/ZK60_Project.jpg
importance: 3
category: research
related_publications: true
---

During the final year of my MSc program, I was given the exciting opportunity to work with the AMAs Research Group at MERC. This collaboration arose from a project where the team was looking for someone with a solid grasp of the basics of tribosystems as well as experience in finite element (FE) modeling to complement their ongoing research. Since my background included simulation of mechanical problems using Abaqus software and an introduction to tribology from Elastisity and Fatigue courses back in 2017, I was a good fit for this role.

Over a four-month period, I immersed myself in the subject, conducting an in-depth review of the literature and consulting with experts from the University of Tehran. This groundwork enabled me to quickly join the AMAs team's research to investigate the mechanical and microstructural properties of ZK60 magnesium alloys containing rare earth (RE) elements like cerium (Ce) and yttrium (Y).

#### The Research Focus:
The core of the AMAs team's research was centered around enhancing the mechanical properties of ZK60 magnesium alloy, with an emphasis on the role of RE element additions (specifically Ce and Y) and the effect of different extrusion ratios (ER) during processing. They explored how varying amounts of RE elements (1%, 2%, and 3% by weight) and extrusion ratios (12:1 and 18:1) influenced the alloy’s microstructure and tensile properties.

Their findings revealed that alloys with 3 wt.% Ce and 3 wt.% Y, processed with an 18:1 extrusion ratio, exhibited the most promising mechanical properties, such as higher hardness and strength. However, the friction and wear behavior of these RE-containing ZK60 alloys remained unexamined. This gap in the research is where my contribution became particularly valuable.

#### My Role:
To address the unknowns surrounding the friction and wear performance of the developed alloys, I performed a series of tribological experiments using a pin-on-disc (PoD) tribometer. My goal was to assess the friction coefficients, wear rates, and predominant wear mechanisms for ZK60 alloys with Ce and Y additions. The experiments conducted under different load conditions to reveal how these RE elements impacted the alloys' tribological performance in the mild and sever wear regimes.

In addition to experimental works, I also utilized Abaqus software and a user-defined subroutine to develop a finite element model aimed at predicting wear behavior. This 3D model simulated the contact pressure during sliding and used this data as an input for Archard's wear equation, allowing us to estimate wear depth for each alloy composition under specific conditions. The combination of experimental and simulation approaches provided a comprehensive understanding of the tribological behavior of the developed ZK60 alloys.

<div class="row">
    <div class="col-sm mt-3 mt-md-0 text-center">
        {% include figure.liquid loading="eager" path="assets/img/ZK60_WearMechanism.jpg" title="Wear Mechanisms" class="img-fluid rounded z-depth-1" mx-auto %}
    </div>
    <div class="col-sm mt-3 mt-md-0 text-center">
        {% include figure.liquid loading="eager" path="assets/img/ZK60_Simulation.jpg" title="PoD Wear Model" class="img-fluid rounded z-depth-1" mx-auto %}
    </div>
</div>
<div class="caption">
    Summary of dominant wear mechanisms under different load regimes; Wear simulation procedure flowchart.
</div>

#### Outcomes and Publications:
The obtained results showed that the wear resistance of extruded ZK60 alloy was improved by adding 3 wt.% of Ce and Y, while the role of Ce addition was more pronounced. Wear rate predictions provided by FE simulation agreed to within 85% of experimental measurments under mild wear regime, but this value was reduced to 75% under severe wear regime.

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

This project not only broadened my research skills, but also resulted in concrete outcomes. Our research findings were presented at the iMat2019 conference and culminated in the publication of two peer-reviewed journal articles:

- {% cite banijamali2021Ce %}
- {% cite banijamali2022simulation %}

In addition, I co-authored another article that focused on the work hardening behavior of these developed alloys {% cite najafi2021WH %}.
<br>

This experience has not only deepened my knowledge in the field of tribology but also enhanced my skills in experimental design and FE modeling in tribology. Collaborating with such a skilled research team at MERC was a rewarding challenge, and I am proud to have contributed to expanding the understanding of these advanced magnesium alloys.

