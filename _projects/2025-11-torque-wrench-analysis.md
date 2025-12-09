---
layout: project
title: Torque Wrench Analysis
description: Mechanics of Engineering Materials Final Project
technologies: [Autodesk Fusion, ANSYS Workbench]
image: /assets/images/normal_stress.jpg
---

As the final project for Mechanics of Engineering Materials, we were asked to design a torque wrench by selecting the material and adjusting the dimensions to meet specified requirements. The material we chose to use is a quenched and tempered high-strength, low-alloy steel, or AISI 4340 QT 409. We chose this material because it is durable and delivers a high enough output to meet the requirements. The relevant information about this material is the Young's modulus, tensile strength, fracture toughness, and fatigue strength. These properties are as follows:

Young's Mondulus --> E = 30 * 10^6 psi
Poisson's Ratio --> nu = 0.29 
Tensile strength --> su = 210 ksi
Fracture toughness --> KIC = 77 (ksi sqrt(in))
Fatigue stress for 10^6 cycles --> sfatigue = 95 *10^3

The full written analysis and report can be found [here]({{ "/assets/Materials Final HW.pdf" | relative_url }}).

The design rendering is very simple geometry, as shown below.

![rendered cad]({{ "/assets/images/rendered_cad.jpeg" | relative_url }}){: .inline-image} 

![exploded cad]({{ "/assets/images/exploded_cad.jpg" | relative_url }}){: .inline-image} 

Diagram communicating how loads and boundary conditions were applied to the FEM model:

![boundary FEM]({{ "/assets/images/boundary_cad.jpg" | relative_url }}){: .inline-image} 

Normal strain contours (in the strain gauge direction):

![normal strain]({{ "/assets/images/normal_strain.jpg" | relative_url }}){: .inline-image} 

Contour plot of maximum principal stress from FEM:

![normal stress]({{ "/assets/images/normal_stress.jpg" | relative_url }}){: .inline-image} 

The FEM analysis shows a maximum normal stress of 40.972 ksi, occurring between the strain gauge and the wrench knob. The strain at the strain gauge location is 1060 microstrain. The deflection at the load point is 0.36641 in, which is the maximum displacement under the applied load.

Using strains from the FEM analysis, the torque wrench sensitivity is 1.06 mV/V.

Strain gauge selected (give type and dimensions). Note that design must physically have enough space to bond the gauges.

We have selected 
