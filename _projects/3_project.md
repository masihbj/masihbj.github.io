---
layout: page
title: ZK60 + REE
description: Exploring the Tribological Behavior of ZK60 Magnesium Alloys with Rare Earth Element Additions
img: assets/img/cover_ZK60_Project.jpg
importance: 3
category: research
related_publications: true
---

In the final year of my Master’s program, I had the chance to collaborate with the *AMAs Research Group* at *MERC*—a great opportunity that combined two areas I was already pretty familiar with: **Contact Mechanics** and **FEM Simulation**. The team needed someone who could bring both to the table, and thanks to my earlier work with Abaqus and coursework in Elasticity and Fatigue back in 2017, I was ready to jump in.

Over the course of four months, I dove deep into the subject. I spent a good chunk of time reviewing the literature and getting insights from researchers at *MERC*, *K.N.Toosi University of Technology*, and *University of Tehran*. This helped me quickly get up to speed and start contributing to the team’s ongoing research on ZK60 magnesium alloys—specifically, how adding rare earth (RE) elements like cerium (Ce) and yttrium (Y) impacts their microstructure and mechanical properties.

### The Research Focus:
The goal was to improve the mechanical properties of ZK60 magnesium alloys by tweaking two things: the amount of RE elements (1, 2, and 3 wt.%) and the extrusion ratios used during processing (12:1 and 18:1). The team found that the best results came from adding 3 wt.% of either Ce or Y and using an 18:1 extrusion ratio—these combinations led to stronger and harder alloys. (You can read more about this in their earlier publication [here](https://dx.doi.org/10.1088/2053-1591/ab1fa0).)

But there was still a gap when it came to understanding how these RE-modified alloys would behave in terms of friction and wear. That’s where I came in.

### My Role:
To explore this open question, I ran a series of wear tests using a pin-on-disc (PoD) tribometer. I was mainly looking at friction coefficients, wear rates, and the dominant wear mechanisms, especially under different loads. This helped us see how the alloys performed under both mild and severe wear conditions.

To complement the lab work, I built a 3D finite element model in Abaqus, using a user-defined subroutine to simulate the contact pressure generated during sliding. With that data, I applied Archard’s wear equation to estimate wear depth for each alloy composition. Putting the experimental and simulation results side by side gave us a much fuller picture of how these alloys perform tribologically.

<div class="row">
    <div class="col-sm mt-3 mt-md-0 text-center">
        {% include figure.liquid loading="eager" path="assets/img/ZK60_WearMechanism.JPG" title="Wear Mechanisms" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0 text-center">
        {% include figure.liquid loading="eager" path="assets/img/ZK60_Simulation.JPG" title="PoD Wear Model" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Summary of dominant wear mechanisms under different load regimes; Wear simulation procedure flowchart.
</div>

### Outcomes and Publications:
The results were exciting: adding 3 wt.% of Ce and Y noticeably improved wear resistance, with Ce showing even stronger effects. Our FE model matched the experimental wear data with about 85% accuracy in mild wear, and around 75% in more severe conditions—which is quite solid.

<div class="row">
    <div class="col-sm mt-3 mt-md-0 text-center">
        {% include figure.liquid loading="eager" path="assets/img/ZK60_WearRate.JPG" title="Wear Rate"
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

This project didn’t just teach me a lot—it also led to some meaningful outcomes. We presented our findings at the iMat2019 conference and published two peer-reviewed journal articles from the research {% cite banijamali2021Ce %}, {% cite banijamali2022simulation %}.

I also co-authored another paper on the work hardening behavior of the same alloys {% cite najafi2021WH %}.
<br>

Working on this project sharpened my skills in both experimental design and FE modeling, and deepened my understanding of tribology. Collaborating with the *MERC team* was a challenging and rewarding experience, and I’m proud to have contributed to advancing our knowledge of these high-performance magnesium alloys.

