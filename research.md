---
layout: page
title: Research
permalink: /research/
---

This page is not updated too often; looking at our recent publications is the best way to see what the group is up to.

Thanks to our sponsors:

[![NVidia](assets/img/nvidia_logo.png)](https://mynvidia.force.com/HardwareGrant/s/Application)
![NG](assets/img/NG.png)
![NSF](assets/img/NSF.jpg)
![Bloomberg](assets/img/Bloomberg.png)
![DOE](assets/img/DOE.png)

## Research interests
Broadly speaking, our group is interested in /information extraction/ from various types of datasets. We are part of a hybrid field combining applied math with computer science and      signal processing techniques. Some specific topics we research are:
- Optimization: first-order methods, quasi-Newton methods, primal-dual algorithms, convex analysis
- Numerical linear algebra: randomization and its interplay with optimization methods
- Sampling theory: how to make the best use of your resources when confronted with big data
- Mathematical applications: compressed sensing and variants, matrix completion and variants (robust PCA...), non-negative matrix factorization and end-member detection, sparse SVM
- Physical applications: radar ADC using compressed sensing, quantum tomography, MRI, medical imaging, IMRT, renewable      energy, big-data

Students interested in working with our group: If you are not currently a student, please apply to our [undergraduate](http://amath.colorado.edu/content/undergraduate-program) or [graduate program](http://amath.colorado.edu/content/graduate-program) and your application will receive full consideration.


Here's a somewhat more cohesive summary of our research:

> The Becker group focuses on optimization, signal processing, machine learning, and numerical methods. One main thrust is collaboration with engineering groups to design signal recovery algorithms for imaging devices (microscopes, ultrasound, MRI, photoacoustic imaging, brain imaging via MEG) and remote sensing (radar, visible and hyperspectral imaging from             satellites). Another main area is matrix and tensor factorizations designed for streaming data, used for machine learning or scientific computation. Finally, a common factor in much of  our research is optimization, linear algebra, and randomized methods. Sometimes we study these methods on their own, and sometimes we use these methods for applications. For example, we look at convergence of new stochastic optimization methods, either in terms of optimization error or (for machine learning) generalization error. Some recent optimization work considers the case when we cannot find a derivative easily, with applications to shape optimization and other PDE-constrained optimization.  Other recent work uses optimization to design          statistical estimators with rigorous confidence intervals for use in quantum tomography.

### Collaborators at CU and nearby (2020 and recent years)
- [Svenja Knappe](https://www.colorado.edu/mechanical/svenja-knappe) (CU Mechanical Engineering; see [Faculty Spotlight on Svenja Knappe](https://www.colorado.edu/initiative/cubit/2019/11/14/svenja-knappe)) on OPM-MEG (i.e., [wearable brain scanners](https://physicsworld.com/a/meg-in-motion-a-wearable-brain-scanner/))
- [Todd Murray](https://www.colorado.edu/faculty/murray/)(CU Mechanical Engineering) on blind structured-illumination photoacoustics (i.e., [our joint NSF grant](https://www.nsf.gov/awardsearch/showAward?   AWD_ID=1810314))
- [Carol Cogswell](https://www.colorado.edu/lab/moisl/) (CU Electrical Engineering) on super-resolution flourescence microscopy (i.e., our joint paper [Achieving superresolution with illumination-enhanced sparsity](https://doi.org/10.1364/OE.26.009850) )
- [Alireza Doostan](https://www.colorado.edu/aerospace/alireza-doostan) (CU Aerospace Engineering) and [Luis Tenorio](https://inside.mines.edu/~ltenorio/) (Colorado School of Mines) on    derivative-free optimization (i.e., our preprint [Stochastic Subspace Descent](https://arxiv.org/abs/1904.01145) )
- [Manuel Lladser](http://amath.colorado.edu/faculty/lladser/) (CU Applied Math) on computational bio (i.e., our paper [Resolvability of Hamming Graphs](https://arxiv.org/abs/1907.05974)).
- [Will Kleiber](http://amath.colorado.edu/faculty/kleiberw/) (CU Applied Math) on spatial statistics (i.e., our paper [Penalized basis models for very   large spatial datasets](https://arxiv.org/abs/1902.06877)).

### Specific research projects, 2018

See a high-level overview of a few of our projects from a 30 minute colloquium talk I gave in 2018: [Colloquium talk slides](https://drive.google.com/file/d/19oPmpHVjRKCb_MvLeGL29mEns_urYWck/view?usp=sharing)

To give you an idea of what we're up to in 2018:
- Parametric and compressive estimation, for phase retrieval (Jessica) in x-ray imaging, and for discovering archaeological ruins (Abby) in radar imaging without creating a DEM
- Theoretical machine learning: sub-sampling and sketching (Farhad, Eric)
- Avoiding and analyzing saddle points in non-convex optimization: for biconvex programming in program analysis and controls (Jessica), and for dictionary learning and neural network    learning (Leo)
- Improving accuracy of sparse estimation using mixed-integer programming (Eric, Leo)
- Efficient computation of the cross-ambiguity function (CAF) for signal processing, to estimate time-of-arrival of radar signals (James)
- Randomized algorithms for numerical linear algebra and optimization (James, Derek)
- Optimization algorithms in general, and ill-conditioning and pre-conditioning (James, Jessica, Osman)
- Efficient algorithms for GPUs (James, Derek, Jessica)
- Tensor decompositions (Osman, Derek)
- Robust estimation (Richie)
- Misc imaging applications (for optical super-resolution, with Carol Cogswell's group in ECEE; and for photo-acoustic super-resolution, with Todd Murray's group in Mech E)
- Stochastic variance reduction methods for nonlinear inverse problems
- Remote sensing of the Chesapeake bay (Cheryl)
- Behavior genetics (Richard, Farhad)

### Old summary of topics, 2014
#### Optimization
*Topics*: first-order methods, quasi-Newton methods, primal-dual algorithms

Optimization in the 21st century has changed dramatically due to the rapid increase in size of data sets. Interior-point methods, which were the /ne plus ultra/ of the convex optimization community, cannot handle many of these data sets, and thus researchers turn to "older" methods such as first-order methods. The main challenges are handling non-smooth terms and constraints, and accelerating the convergence speed to levels comparable with limited-memory quasi-Newton methods (or at least Nesterov-accelerated methods).

#### Mathematical applications
*Topics*: compressed sensing and variants, matrix completion and variants (robust PCA...), non-negative matrix factorization and end-member detection, sparse SVM

Compressed sensing (CS) has taken the greater applied math community by storm since its introduction in 2004. Besides CS itself, the field has inspired new approaches to old problems in related disciplines. In particular, given the strengths of modern computers and algorithms, signal processing is increasingly relying on /non-linear/ reconstruction algorithms (such as optimization-based algorithms). The main challenges are exploiting all prior information from the signal (going beyond just sparsity models), and solving optimization problems that are sometimes non-convex and usually large scale. The subfield of matrix completion is one exciting direction, and presents a plethora of optimization challenges due to the fundamental difference between matrix and vector optimization (i.e., linear programs vs semi-definite programs).

#### Physical applications
*Topics*: radar ADC using compressed sensing, quantum tomography, MRI, medical imaging, IMRT, renewable energy

I have worked on a CMOS implementation of a compressed-sensing ADC, as well as on quantum tomography. I have interests in pursuing medical applications and energy applications.

#### Supercooled water
Liquid water can be supercooled to below the equilibrium freezing temperature. In this regime, many of water's unusual properties are amplified, and it also has some features, such as a liquid-liquid phase transition, that do not appear at higher temperatures. My undergraduate work on this was supervised by my thesis advisor [Francis Starr](https://fstarr.faculty.wesleyan.edu/) of the [Department of Physics at Wesleyan University](https://www.wesleyan.edu/physics/). My [undergraduate thesis](../assets/docs/thesis.pdf) was focused on the interplay of translational and rotational dynamics in supercooled water. Research was conducted by Molecular Dynamics simulation of ST2 water on computer clusters at both Wesleyan University in Connecticut and St. Francis Xavier University in Nova Scotia. Collaboration was also done with [Peter Poole](https://people.stfx.ca/ppoole/) of St. Francis Xavier University. 