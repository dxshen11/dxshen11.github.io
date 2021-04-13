---
layout: simple
title:  "5 DOF Printhead Flexure System"
description: "This project was completed for a graduate level compliant mechanisms course at UCLA (MAE C294A). The printhead was designed to have 5 degrees of freedom using only flexure geometries and was actuated by linear actuators."
---
**Goal:** <br>
As part of the requirements for a graduate level compliant mechanisms course for my M.S. degree, I needed to design a printhead system designed to be used by self-propelled ink deposition robots (SPIDRs) in space based and micro-gravity applications. The project specifications and applications of such a printhead can be provided on request.

Some of the system requirements were:
+ Fit within a 1 cubic ft. volume.
+ Be able to withstand linear vibrations with amplitudes of up to 0.25 cm and angular vibrations with amplitudes of up to 3 degrees.
+ Have a actuation resolution of at least 0.1 mm.
+ Manufacturable with planar processes.
<br>

**Work Completed:** <br>
Using the freedom and constraint topologies (FACT) framework developed by Professor Jonathan Hopkins, I designed a flexure printhead system with 5 actuated degrees of freedom. A paper describing the theory of FACT is available [here](http://web.mit.edu/mact/www/Blog/Flexures/Parallel1.pdf) or on Professor Hopkins' YouTube page.
<br><br>
After synthesizing the necessary flexure types, the printhead was modeled in Solidworks. Solidworks FEA was used to perform modal analysis, which demonstrates the principal DOFs of the system (3 translations, 3 rotations), and structural analysis, to ensure that the flexures do not yield in their actuation range. The material chosen for the flexures was alloy 7075 aluminum, due to their relatively high yield strength and low elastic modulus. The actuator that was chosen was the M-232 High Resolution Linear Actuator from Physics Instruments, with a travel range of 17mm, a resolution of 0.1um, and a push/pull force of 40N. 

**CAD & FEA Model:** <br>
![Model](/assets/Model.png)

The first 6 modeshapes corresponding to the first 6 resonant frequencies actually captures the principal DOFs of the system. This printhead actually has 6 DOFs available, but is only actuated in 5 because controlling the rotation of the printhead about the Z-axis is not of concern for a SPIDR.
<br><br>
X-axis rotation:
![Test 1](/assets/Amplitude1-1.gif)
Y-axis rotation:
![Test 2](/assets/Amplitude2-1.gif)
Z-axis translation:
![Test 3](/assets/Amplitude3-1.gif)
X-axis translation:
![Test 6](/assets/Amplitude6-1.gif)
Y-axis translation:
![Test 7](/assets/Amplitude7-1.gif)







