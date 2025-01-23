---
layout: page
title: Software
permalink: /software/
---

One of 640 (as of May 2020) Mathworks contributors to have a submission with [25 five star ratings "5-Star Galaxy Level 5"](https://www.mathworks.com/matlabcentral/profile/badges/114?s_tid=mlc_badge_email_submission).

## Github software

Most of our group's latest software is on github. These are github project or user pages for students who have been in our research group or collaborated with our group:

<div class="twoColumn" markdown=1>

- [Stephen](https://github.com/stephenbeckr) and [cvx/tfocs projects](https://github.com/cvxr) ([paper](../papers#tfocs))
- James: [safe Non-Neg. Least Squares](https://github.com/jamesfolberth/safe_nnls) ([paper](../papers#nnls))
- Farhad: [RandomizedClusteredNystrom](https://github.com/FarhadPourkamali/RandomizedClusteredNystrom/)
- Eric: [SparseKMeans](https://github.com/EricKightley/sparsekmeans) ([paper](../papers#sparsegmm))
- Osman
  - [Tucker-TensorSketch](https://github.com/OsmanMalik/tucker-tensorsketch) ([paper](../papers#tensorsketch))
  - [quadrature-sampling](https://github.com/OsmanMalik/quadrature-sampling)
  - [Tensor-Ring ALS Sampled](https://github.com/OsmanMalik/tr-als-sampled)
  - [Fast matrix/tensor ID](https://github.com/OsmanMalik/countsketch-matrix-tensor-id) ([paper](../papers#tensorid))
- [Claudia](https://github.com/claudiachen1457/)
- [Tzu-Chi](https://github.com/junipertcy/)
  - [Regularized Spring Rank](https://github.com/junipertcy/RegRank)
- Jacob S: [optimal_ultrasound_encoding](https://github.com/jcs15c/optimal_ultrasound_encoding) ([paper](../papers#ultrasound2022))
- Liam: 
  - [sgd](https://github.com/liammadden/sgd) ([paper](../papers#liamSGD))
  - [time-varying opt.](https://github.com/liammadden/time-varying-experiments) ([paper](../papers#time-varying))
- [Jaden](https://github.com/tholdem) 
- Jacob T: [Capstone project on deep learning for genomic data](https://github.com/Jacob-Tie/GraduateSchoolCourseWork/tree/master/Capstone_Project)
- Will Shand: [LSHFunctions.jl](https://github.com/kernelmethod/LSHFunctions.jl)
- Akshay: [minimax-fidelity-estimation](https://github.com/akshayseshadri/minimax-fidelity-estimation) ([paper](../papers#versatilefidelity))
- [Gregor](https://github.com/gregor-robinson/)
- [Erik](https://github.com/erikj540)
- [Lucas](https://github.com/lucas-laird/Hammming_Resolvability)
- Richard: [SL REML](https://github.com/rborder/SL_REML) ([paper](../papers#REML))
- Marc: [MDSpectralAnalysis](https://github.com/MarcThomson/MDSpectralAnalysis)
- Jeff: [Hadamard Transform](https://github.com/jeffeverett/hadamard-transform)
- ["Algorithmic Data Reduction"](https://github.com/AlgorithmicDataReduction) for Cooper and Kevin's work
  - [PyTorch-QuadConv](https://github.com/AlgorithmicDataReduction/PyTorch-QuadConv/tree/main)  ([paper](../papers#quadConv))
- Cooper Simpson
  - [PyTorch-ARC](https://github.com/RS-Coop/PyTorch-ARC) in Python
  - [QuasiNewton.jl](https://github.com/RS-Coop/QuasiNewton.jl) in Julia
- [Kevin](https://github.com/kvndhrty)
  - [QuadConv](https://github.com/kvndhrty/QuadConv), superseded by PyTorch-QuadConv
  - [Mesh-Float-Zip](https://github.com/kvndhrty/Mesh-Float-Zip) for compression
- [Richie Clancy](https://github.com/rclancyc/)
  - [approximate MLE](https://github.com/rclancyc/approximate_mle)  ([paper](../papers#approx_MLE))
  - [MEG](https://github.com/rclancyc/meg) for Magnetoencephalography
- Collaboration with Alireza Doostan's [CU-UQ](https://github.com/CU-UQ) group
- [Noki](https://github.com/NUOJIN): 
  - [monotone lower set sampling](https://github.com/CU-UQ/monotone-lower-set/) with  [Noki](https://github.com/NUOJIN) and Osman ([paper](../papers#monotone-sampling))
  - [Boosted Quad. Sampling](https://github.com/CU-UQ/BF-Boosted-Quadrature-Sampling) ([paper](../papers#bifidelity-boosting))
  - [Bi-fidelity Variational AutoEncoder](https://github.com/CU-UQ/Bi-fidelity-VAE) Noki and Osman  ([paper](../papers#bifiVAE))
- [K. Aditi](https://github.com/Additi-K)
- [Killian Wood](https://github.com/killianrwood)
- Mitchell Krock: [Multivariate Basis Graphical Lasso](https://github.com/mlkrock/MultivariateBasisGraphicalLasso)  ([paper](../papers#Mitch))
- Angran Li: [Data Reduction via ID](https://github.com/truthlive/ASCR_DataReduction)
- Ibrohim Nosirov: [Peeling algorithm](https://github.com/ib-nosirov/peeling_algorithm) for structured matrix approximation
- Alexey Yermakov: [Tutorial on Bayesian Optimization with First-Order information (gradients)](https://github.com/yyexela/botorch/blob/main/tutorials/fobo.ipynb)
  - [BoTorch pull request](https://github.com/pytorch/botorch/pull/2137), and [BoTorch feature request](https://github.com/pytorch/botorch/issues/1679)
- Bhavana Jonnalagadda
  - [Data-drive low-rank factorization](https://github.com/Chocbanana/Research-Becker-Group) ([paper](../papers#Vlasov2025))

</div>

## A few specific software packages

- [Misc Python optimization routines](https://github.com/stephenbeckr/convex-optimization-class/tree/master/utilities) for classic first and second order methods, as part of the optimization class I teach. I think there may be a bug in the one of the linesearch options, but otherwise it should work well.

- [Random sketching operators](https://github.com/stephenbeckr/randomized-algorithm-class/tree/master/Code) in Matlab and Python, as part of the class I teach. This has Gaussian sketch, Fast Johnson Lindenstrauss (with FFT or a fast Hadamard), and count sketch. The Hadamard and count sketch have C functions to make them extra fast.  (For the tensor product sketches, which is more complicated, see [Osman's github page](https://github.com/OsmanMalik/) ).

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

  - Derek Driggs has forked this to make an improved [fastRPCA](https://github.com/derekdriggs/fastRPCA) that uses the tricks from our [RPCA marginalization paper](../papers#RPCA_SISC).


- [zeroSR1](zeroSR1.html) *zero SR1* (2013)  
A Matlab software package that is the only rigorous quasi-Newton method to solve the non-smooth LASSO problem. We use new results from convex analysis to show that a quasi-Newton update can be done in closed-form on a proximal objective.
Existing approaches would solve the update via a slow iterative method, or smooth the problem, or apply quasi-Newton methods to the unsmooth problem in a heurstic fashion.  Our solver is one of the most consistently fast LASSO solvers (it also solves non-linear least-squares problems, among others), and is faster than well-known algorithms like L-BFGS-B.
This is also actively maintained on github under the BSD license.

- [TFOCS](http://cvxr.com/tfocs/)   *Templates for First-Order Conic Solvers* (2010)  
A Matlab software package designed to solve all compressed sensing (and low-rank recovery) problems, but in fact it goes much farther and solves all conic programming problems. Joint work with [Michael Grant](http://cvxr.com/) and [Emmanuel Candès](https://candes.su.domains/). This is actively maintained, and under the BSD license. [Paper](../papers#tfocs)

- [NESTA](https://candes.su.domains/software/nesta/) *Nesterov's Algorithm* (2009)  
A Matlab software package designed to solve some constrained compressed sensing problems, when the measurement matrix is a partial isometry or not too large (however, the analysis dictionary may be very large). Joint work with Jerome Bobin and [Emmanuel Candès](http://www-stat.stanford.edu/~candes).  You can download the paper here: [Paper](../papers#nesta).  A local version of the package is hosted here: [NESTA_v1.1.zip](../assets/docs/NESTA_v1.1.zip).

- [SVD](https://candes.su.domains/software/svt/) *Singular Value Thresholding* (2009)  
A Matlab (with mex files) package for matrix completion via nuclear-norm minimization. Please email me if you have questions about the software (and include information on the verson of Matlab, the operating system, and the hardware -- e.g. 32-bit or 64-bit). I am working on making it more compatible with 64-bit systems and compatible with complex-valued data. We have experimental versions using Nesterov stepsizes and even L-BFGS acceleration, but these are standard optimization tricks so we have not described them in papers.  SVT is now one of the classic "reference" algorithms used in the field. The version provided is very simple and doesn't use a line search feature, and may even diverge if you set the stepsize above the legal limit. For this reason, we recommend using TFOCS, which is a more powerful version of SVT. [Paper](http://www-stat.stanford.edu/~candes/papers/SVT.pdf)   (UPDATE: June 2019, I have put SVT code on [github](https://github.com/stephenbeckr/SVT), but maintenance is minimal)


## Misc. documentation

- Parallel computing  
For working on a cluster (especially a CU one), Richard has some [tips](https://github.com/rborder/ibg_rc_cheatsheet)

- BLAS  
Here is a [quick reference guide to BLAS in PDF](../assets/docs/blasqr_betterFonts.pdf) which I have taken from [netlib's version](http://www.netlib.org/blas/faq.html\#4) and used `pkfix-helper` and `pkfix` to make a PDF that actually has readable fonts.
