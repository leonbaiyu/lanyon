---
layout: post
title: 2D Kinetic Theory of Gases Model
---

A 2D Kinetic Theory of Gases Model was developed in Python, in particular, using the Mesa agent-based modelling package. Some results of this model were visualised and can be seen below:

### Animation of 2D Gas model alongside evolving energy distribution

The below animation was created using matplotlib.

<img src="/2D_Gas_Joint_Animation.gif" alt="GIF of 2D Gas Visualisation and Velocity Distribution of particles">

(LHS) Animation visualising movement of particles within 2D Kinetic Theory of Gases Model. Particles have colour based on their energies. (RHS) Parallel visualisation of velocity distribution of particles synchronised to the visualisation in the LHS. Depicts relaxation from initially equal velocity of all agents to a Maxwell-Boltzmann distribution, indicated by the distribution in orange. Note that the MB distribution was fitted to an averaged final velocity distribution.

#### Understanding 2D Collision dynamics

The 2D collision dynamics of this model are explained in the below diagram. The key aspect being rotating the frame of reference to separate the independent components of the velocities of the particles from the components involved in the collision. For further details, consult the thesis:

<img src="/Elastic_Collision_Explanation.png" alt="Diagram explaining the calculation of 2D elastic collision dynamics">
