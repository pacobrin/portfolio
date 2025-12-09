---
layout: project
title: Torque Wrench Analysis
description: Mechanics of Engineering Materials Final Project
technologies: [Autodesk Fusion, ANSYS Workbench]
image: /assets/images/radio-machine-cad.jpg
---

As the final project for Mechanics of Engineering Materials, we were asked to design a torque wrench by selecting the material and adjusting the dimensions to meet specified requirements. The material we chose to use is a quenched and tempered high-strength, low-alloy steel, or AISI 4340 QT 409. We chose this material because it is durable and delivers a high enough output to meet the requirements. The relevant information about this material is the Young's modulus, tensile strength, fracture toughness, and fatigue strength. These properties are as follows:

Young's Mondulus --> E = 30 * 10^6 psi
Poisson's Ratio --> nu = 0.29 
Tensile strength --> su = 210 ksi
Fracture toughness --> KIC = 77 (ksi sqrt(in))
Fatigue stress for 10^6 cycles --> sfatigue = 95 *10^3

The design rendering is very simple geometry, as shown below.

![rendered cad]({{ "/assets/images/rendered_cad.jpg" | relative_url }}){: .inline-image-r style="width: 200px"}
![exploded cad]({{ "/assets/images/exploded_cad.jpg" | relative_url }}){: .inline-image-r style="width: 200px"}

Diagram communicating how loads and boundary conditions were applied to the FEM model:

![boundary FEM]({{ "/assets/images/boundary_CAD.jpg" | relative_url }}){: .inline-image-r style="width: 200px"}

Normal strain contours (in the strain gauge direction):



Contour plot of maximum principal stress from FEM:

Summarize results from FEM calculation showing maximum normal stress (anywhere),
load point deflection, strains at the strain gauge locations

Torque wrench sensitivity in mV/V using strains from the FEM analysis

Strain gauge selected (give type and dimensions). Note that design must physically have enough space to bond the gauges.

![Shaded rendering of earlier version]({{ "/assets/images/radio-machine.jpg" | relative_url }}){: .inline-image-r style="width: 200px"}

![Photo of old radio]({{ "/assets/images/old-radio.jpg" | relative_url }}){: .inline-image-l}
