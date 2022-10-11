---
layout: page
title: Software
permalink: /software/
---

One of 640 (as of May 2020) Mathworks contributors to have a submission with [25 five star ratings "5-Star Galaxy Level 5"](https://www.mathworks.com/matlabcentral/profile/badges/114?s_tid=mlc_badge_email_submission).

## Github software

Most of our group's latest software is on github. These are github project or user pages for students who have been in our research group or collaborated with our group:

<div class="twoColumn" markdown=1>

- [Stephen](https://github.com/stephenbeckr) and [cvx/tfocs projects](https://github.com/cvxr) ([paper](/papers#tfocs))
- James: [safe Non-Neg. Least Squares](https://github.com/jamesfolberth/safe_nnls) [paper](/papers#nnls)
- Farhad: [RandomizedClusteredNystrom](https://github.com/FarhadPourkamali/RandomizedClusteredNystrom/)
- [Eric](https://github.com/EricKightley/sparsekmeans) [paper](/papers#sparsegmm)
- Osman
  - [Tucker-TensorSketch](https://github.com/OsmanMalik/tucker-tensorsketch) for [paper](/papers#tensorsketch)
  - [quadrature-sampling](https://github.com/OsmanMalik/quadrature-sampling)
  - [Tensor-Ring ALS Sampled](https://github.com/OsmanMalik/tr-als-sampled)
  - [Fast matrix/tensor ID](https://github.com/OsmanMalik/countsketch-matrix-tensor-id) for [paper](/papers#tensorid)
- [Angran](https://github.com/truthlive/ASCR_DataReduction)
- [Ibrohim](https://github.com/ib-nosirov/peeling_algorithm)
- Noki: 
  - [monotone lower set](https://github.com/CU-UQ/monotone-lower-set/) for [paper](/papers#monotone-sampling)
  - [Boosted Quad. Sampling](https://github.com/CU-UQ/BF-Boosted-Quadrature-Sampling) for [paper](/papers#bifidelity-boosting)
- [Claudia](https://github.com/claudiachen1457/)
- [Tzu-Chi](https://github.com/junipertcy/)
- [Kevin](https://github.com/kvndhrty)
- Jacob S: [optimal_ultrasound_encoding](https://github.com/jcs15c/optimal_ultrasound_encoding)
- Liam: 
  - [sgd](https://github.com/liammadden/sgd) [paper](/papers#liamSGD)
  - [time-varying opt.](https://github.com/liammadden/time-varying-experiments) for [paper](/papers#time-varying)
- [Jaden](https://github.com/tholdem) 
- Jacob T: [Capstone project on deep learning for genomic data](https://github.com/Jacob-Tie/GraduateSchoolCourseWork/tree/master/Capstone_Project)
- Will Shand: [LSHFunctions.jl](https://github.com/kernelmethod/LSHFunctions.jl)
- Akshay: [minimax-fidelity-estimation](https://github.com/akshayseshadri/minimax-fidelity-estimation) for [paper](/papers#versatilefidelity)
- [Gregor](https://github.com/gregor-robinson/)
- [Erik](https://github.com/erikj540)
- [Richie](https://github.com/rclancyc/)
- [Lucas](https://github.com/lucas-laird/Hammming_Resolvability)
- Richard: [SL REML](https://github.com/rborder/SL_REML) for [paper](/papers#REML)
- Marc: [MDSpectralAnalysis](https://github.com/MarcThomson/MDSpectralAnalysis)
- Jeff: [Hadamard Transform](https://github.com/jeffeverett/hadamard-transform)

</div>

## A few specific software packages

- [Exact linesearch for LASSO](https://github.com/stephenbeckr/exactLASSOlinesearch)  
Simple Matlab code for exact step-size selection for LASSO objectives, and [Exact linesearch for LASSO Tech. Report](exactLinesearchL1.pdf) which describes the method.

- [Sparsified K-Means](https://github.com/stephenbeckr/SparsifiedKMeans) *faster K-means for big data* (2015)  
Uses fast Johnson-Lindenstrauss ideas to appropriately sample from big datasets. This is a one-pass algorithm that performs K-means clustering, suitable for distributed datasets. It also works on in-core problems and is much faster than Matlab's default K-means,
and uses modern ideas on initialization.  Hosted in github, BSD license. 
A [version for GMM](https://github.com/erickightley/sparseklearn), written in Python and C, is also available.

- [L-BFGS-B-C](https://github.com/stephenbeckr/L-BFGS-B-C) *C version of L-BFGS-B* (2015)  
A version of L-BFGS-B 3.0 in C, with Matlab mex wrapper. Hosted on github, BSD license.

- [fastRPCA](https://github.com/stephenbeckr/fastRPCA) *fast robust PCA* (2014)  
A Matlab software package to solve all variants of robust PCA and stable principal component pursuit (SPCP) problems. This is actively maintained, and hosted on github under the BSD license.

- [zeroSR1](zeroSR1.html) *zero SR1* (2013)  
A Matlab software package that is the only rigorous quasi-Newton method to solve the non-smooth LASSO problem. We use new results from convex analysis to show that a quasi-Newton update can be done in closed-form on a proximal objective.
Existing approaches would solve the update via a slow iterative method, or smooth the problem, or apply quasi-Newton methods to the unsmooth problem in a heurstic fashion.  Our solver is one of the most consistently fast LASSO solvers (it also solves non-linear least-squares problems, among others), and is faster than well-known algorithms like L-BFGS-B.
This is also actively maintained on github under the BSD license.

- [TFOCS](http://cvxr.com/tfocs/)   *Templates for First-Order Conic Solvers* (2010)  
A Matlab software package designed to solve all compressed sensing (and low-rank recovery) problems, but in fact it goes much farther and solves all conic programming problems. Joint work with [Michael Grant](http://cvxr.com/) and [Emmanuel Candès](http://www-stat.stanford.edu/~candes). This is actively maintained, and under the BSD license. [Paper](/papers#tfocs)

- [NESTA](https://statweb.stanford.edu/~candes/software/nesta/) *Nesterov's Algorithm* (2009)  
A Matlab software package designed to solve some constrained compressed sensing problems, when the measurement matrix is a partial isometry or not too large (however, the analysis dictionary may be very large). Joint work with Jerome Bobin and [Emmanuel Candès](http://www-stat.stanford.edu/~candes). [Paper](/papers#nesta)

- [SVD](https://candes.su.domains/software/svt/) *Singular Value Thresholding* (2009)  
A Matlab (with mex files) package for matrix completion via nuclear-norm minimization. Please email me if you have questions about the software (and include information on the verson of Matlab, the operating system, and the hardware -- e.g. 32-bit or 64-bit). I am working on making it more compatible with 64-bit systems and compatible with complex-valued data. We have experimental versions using Nesterov stepsizes and even L-BFGS acceleration, but these are standard optimization tricks so we have not described them in papers.  SVT is now one of the classic "reference" algorithms used in the field. The version provided is very simple and doesn't use a line search feature, and may even diverge if you set the stepsize above the legal limit. For this reason, we recommend using TFOCS, which is a more powerful version of SVT. [Paper](http://www-stat.stanford.edu/~candes/papers/SVT.pdf)   (UPDATE: June 2019, I have put SVT code on [github](https://github.com/stephenbeckr/SVT), but maintenance is minimal)


## Misc. documentation

- Parallel computing  
For working on a cluster (especially a CU one), Richard has some [tips](https://github.com/rborder/ibg_rc_cheatsheet)

- BLAS  
Here is a [quick reference guide to BLAS in PDF](../assets/docs/blasqr_betterFonts.pdf) which I have taken from [netlib's version](http://www.netlib.org/blas/faq.html\#4) and used `pkfix-helper` and `pkfix` to make a PDF that actually has readable fonts.
