# Sparse Optimization
I am currently working on nonconvex optimization problems involving L0 norm instead of convex/nonconvex surrogates.
- [Surveys](#Surveys)
- [Constrained Methods](#Constrained_Methods)
- [Regularized Methods](#Regularized_Methods)
- [Other Methods](#Other_Methods)
- [Applications](#Applications)
- [Links](#Links)

  
<strong> Last Update: 2024/2/5 </strong>



<a name="Surveys" />

### Surveys
- [2022] High-Dimensional Data Analysis with Low-Dimensional Models: Principles, Computation, and Applications, Cambridge University Press [[Book](https://book-wright-ma.github.io/)]
- [2022] Foundations of Computational Imaging: A Model-Based Approach, SIAM [[Book](https://epubs.siam.org/doi/book/10.1137/1.9781611977134)]
- [2022] 稀疏优化二阶算法研究进展, 数值计算与计算机应用 [[Paper](https://computmath.cjoe.ac.cn/szjs/CN/10.12288/szjs.s2021-0759)]
- [2020] 稀疏优化理论与算法若干新进展, 运筹学学报 [[Paper](https://www.ort.shu.edu.cn/CN/10.15960/j.cnki.issn.1007-6093.2020.04.001)]
- [2020] Statistical Foundations of Data Science, CRC Press [[Book](https://www.taylorfrancis.com/books/mono/10.1201/9780429096280/statistical-foundations-data-science-jianqing-fan-runze-li-cun-hui-zhang-hui-zou)]
- [2018] Optimization Methods for Large-Scale Machine Learning, SIAM Review [[Paper](https://epubs.siam.org/doi/abs/10.1137/16M1080173)]
- [2018] Sparse Optimization Theory and Methods, CRC Press [[Book](https://www.taylorfrancis.com/books/mono/10.1201/9781315113142/sparse-optimization-theory-methods-yun-bin-zhao)]
- [2017] Feature Selection Based on Structured Sparsity: A Comprehensive Study [[Paper](https://ieeexplore.ieee.org/document/7458185)]  [[Matlab](https://github.com/guijiejie/Feature-selection/tree/master/Feature%20selection%20based%20on%20structured%20sparsity)]
- [2017] Non-convex Optimization for Machine Learning, Foundations and Trends in Machine Learning [[Paper](https://www.nowpublishers.com/article/Details/MAL-058)]
- [2015] Statistical Learning with Sparsity: The Lasso and Generalizations, CRC Press [[book](https://hastie.su.domains/StatLearnSparsity_files/SLS_corrected_1.4.16.pdf)]
- [2014] Sparse Modeling: Theory, Algorithms, and Applications, CRC Press [[Book](https://www.taylorfrancis.com/books/mono/10.1201/b17758/sparse-modeling-irina-rish-genady-grabarnik)]
- [2012] Optimization with Sparsity-Inducing Penalties, Foundations and Trends in Machine Learning [[Paper](https://www.nowpublishers.com/article/Details/MAL-015)]
- [2012] 压缩感知和稀疏优化简介, 运筹学学报 [[Paper](https://www.ort.shu.edu.cn/CN/Y2012/V16/I3/49)]
- [2012] 压缩感知, 中国科学 [[Paper](https://dds.sciengine.com/cfs/files/pdfs/view/1674-7216/bevBnqMiAzjDxRHki.pdf)]



<a name="Constrained_Methods" />

## Constrained Methods

### First-Order Algorithms
- [2017] Gradient Hard Thresholding Pursuit, Journal of Machine Learning Research [[Paper](https://www.jmlr.org/papers/volume18/14-415/14-415.pdf)]
- [2017] A Convergent Iterative Hard Thresholding for Nonnegative Sparsity Optimization, Pacific Journal of Optimization  [[Paper](http://www.yokohamapublishers.jp/online2/oppjo/vol13/p325.html)] [[Matlab](https://github.com/ShenglongZhou/IIHT)]
- [2016] On the Minimization over Sparse Symmetric Sets: Projections, Optimality Conditions, and Algorithms, Mathematics of Operations Research [[Paper](https://pubsonline.informs.org/doi/abs/10.1287/moor.2015.0722)] 
- [2015] On Solutions of Sparsity Constrained Optimization, Journal of the Operations Research Society of China [[Paper](https://link.springer.com/article/10.1007/s40305-015-0101-3)]
- [2013] Greedy Sparsity-Constrained Optimization, Journal of Machine Learning Research [[paper](https://www.jmlr.org/papers/volume14/bahmani13a/bahmani13a.pdf)]
- [2013] Sparsity Constrained Nonlinear Optimization: Optimality Conditions and Algorithms, SIAM Journal on Optimization [[Paper](https://epubs.siam.org/doi/abs/10.1137/120869778)]
- [2012] Accelerated Iterative Hard Thresholding, Signal Processing [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0165168411003197)]
- [2011] Hard Thresholding Pursuit: An Algorithm for Compressive Sensing, SIAM Journal on Numerical Analysis [[Paper](https://epubs.siam.org/doi/abs/10.1137/100806278)]
- [2010] Normalized Iterative Hard Thresholding: Guaranteed Stability and Performance, IEEE JSTSP [[Paper](https://ieeexplore.ieee.org/abstract/document/5419091)]
- [2009] CoSaMP: Iterative Signal Recovery from Incomplete and Inaccurate Samples, Applied and Computational Harmonic Analysis [[Paper](https://www.sciencedirect.com/science/article/pii/S1063520308000638)] [[Matlab](https://ww2.mathworks.cn/matlabcentral/fileexchange/32402-cosamp-and-omp-for-sparse-recovery)]
- [2007] Gradient Projection for Sparse Reconstruction: Application to Compressed Sensing and Other Inverse Problems, IEEE JSTSP [[Paper](https://ieeexplore.ieee.org/abstract/document/4407762)]
- [2007] Signal Recovery From Random Measurements Via Orthogonal Matching Pursuit, IEEE TIT [[Paper](https://ieeexplore.ieee.org/abstract/document/4385788)]
- [1993] Orthogonal Matching Pursuit: Recursive Function Approximation with Applications to Wavelet Decomposition, IEEE ACSSC  [[Paper](https://ieeexplore.ieee.org/abstract/document/342465)]

  
### Second-Order Algorithms
- [2022] Sparse SVM for Sufficient Data Reduction, IEEE TPAMI [[Paper](https://ieeexplore.ieee.org/document/9415153)] [[Matlab](https://github.com/ShenglongZhou/NSSVM)]
- [2022] Gradient Projection Newton Pursuit for Sparsity Constrained Optimization, Applied and Computational Harmonic Analysis [[Paper](https://www.sciencedirect.com/science/article/pii/S1063520322000458)] [[Matlab](https://github.com/ShenglongZhou/GPNP)]
- [2022] A Lagrange-Newton Algorithm for Sparse Nonlinear Programming, Mathematical Programming [[Paper](https://link.springer.com/article/10.1007/s10107-021-01719-x)]
- [2021] Newton Hard-Thresholding Pursuit for Sparse Linear Complementarity Problem via A New Merit Function, SIAM Journal on Scientific Computing  [[Paper](https://epubs.siam.org/doi/10.1137/19M1301539)] [[Matlab](https://github.com/ShenglongZhou/NHTP)]
- [2021] Global and Quadratic Convergence of Newton Hard-Thresholding Pursuit, Journal of Machine Learning Research [[Paper](https://jmlr.org/papers/volume22/19-026/19-026.pdf)] [[Matlab](https://github.com/ShenglongZhou/NHTP)]
- [2020] Greedy Projected Gradient-Newton Method for Sparse Logistic Regression, IEEE TNNLS [[Paper](https://ieeexplore.ieee.org/abstract/document/8688642)]
- [2017] Newton-Type Greedy Selection Methods for L0-Constrained Minimization, IEEE TPAMI [[Paper](https://ieeexplore.ieee.org/abstract/document/7814339)]
- [2017] Fast Newton Hard Thresholding Pursuit for Sparsity Constrained Non-Convex Optimization, KDD [[Paper](https://dl.acm.org/doi/abs/10.1145/3097983.3098165)]
- [2013] Greedy Sparsity-Constrained Optimization, Journal of Machine Learning Research [[Paper](https://www.jmlr.org/papers/volume14/bahmani13a/bahmani13a.pdf)]


<a name="Regularized_Methods" />

## Regularized Methods

### First-Order Algorithms
- [2020] An Active Set Barzilar-Borwein Algorithm for L0 Regularized Optimization, Journal of Global Optimization [[Paper](https://link.springer.com/article/10.1007/s10898-019-00830-w)]
- [2020] A Smoothing Proximal Gradient Algorithm for Nonsmooth Convex Regression with Cardinality Penalty, SIAM Journal on Numerical Analysis [[paper](https://epubs.siam.org/doi/abs/10.1137/18M1186009)]
- [2018] Proximal Mapping for Symmetric Penalty and Sparsity, SIAM Journal on Optimization  [[Paper](https://epubs.siam.org/doi/abs/10.1137/17M1116544)]
- [2016] Image Restoration by Minimizing Zero Norm of Wavelet Frame Coefficients, Inverse Problems [[Paper](https://iopscience.iop.org/article/10.1088/0266-5611/32/11/115004/meta)]
- [2015] Homotopy Based Algorithms for L0-Regularized Least-Squares, IEEE TSP [[Paper](https://ieeexplore.ieee.org/abstract/document/7084156)]
- [2015] CGIHT: Conjugate Gradient Iterative Hard Thresholding for Compressed Sensing and Matrix Completion, Information and Inference [[Paper](https://ieeexplore.ieee.org/abstract/document/8189185)]
- [2014] Iterative Hard Thresholding Methods for L0 Regularized Convex Cone Programming, Mathematical Programming [[Paper](https://link.springer.com/article/10.1007/s10107-013-0714-4)]
- [2013] Sparse Approximation via Penalty Decomposition Methods, SIAM Journal on Optimization [[Paper](https://epubs.siam.org/doi/abs/10.1137/100808071)]
- [2009] Iterative Hard Thresholding for Compressed Sensing, Applied and Computational Harmonic Analysis [[Paper](https://www.sciencedirect.com/science/article/pii/S1063520309000384)]



### Second-Order Algorithms
- [2023] Revisiting Lq (0<=q<1) Norm Regularized Optimization, ArXiv [[Paper](https://arxiv.org/abs/2306.14394)] [[Matlab](https://github.com/ShenglongZhou/PSNP)]
- [2022] Newton Method for L0-Regularized Optimization, Numerical Algorithms [[Paper](https://link.springer.com/article/10.1007/s11075-021-01085-x)] [[Matlab](https://github.com/ShenglongZhou/NL0R)]
- [2018] A Constructive Approach to l0 Penalized Regression, Journal of Machine Learning Research [[Paper](https://www.jmlr.org/papers/volume19/17-194/17-194.pdf)]
- [2015] A Primal Dual Active Set with Continuation Algorithm for the l0-Regularized Optimization Problem, Applied and Computational Harmonic Analysis  [[Paper](https://www.sciencedirect.com/science/article/pii/S1063520314001250)]
- [2013] A Variational Approach to Sparsity Optimization Based on Lagrange Multiplier Theory, Inverse Problems [[Paper](https://iopscience.iop.org/article/10.1088/0266-5611/30/1/015001/meta)]



<a name="Other_Methods" />

## Other Methods
- [2023] Sparse Plus Low Rank Matrix Decomposition: A Discrete Optimization Approach, Journal of Machine Learning Research [[Paper](https://www.jmlr.org/papers/volume24/21-1130/21-1130.pdf)] [[Julia](https://github.com/NicholasJohnson2020/SparseLowRankSoftware)]
- [2022] A Comparative Study of Multi-Objective Optimization Algorithms for Sparse Signal Reconstruction, Artificial Intelligence Review [[Paper](https://link.springer.com/article/10.1007/s10462-021-10073-5)]
- [2022] Learning to Optimize: A Primer and A Benchmark, Journal of Machine Learning Research [[Paper](https://dl.acm.org/doi/abs/10.5555/3586589.3586778)] [[Python](https://github.com/VITA-Group/Open-L2O)]
- [2020] ADMM-CSNet: A Deep Learning Approach for Image Compressive Sensing, IEEE TPAMI [[Paper](https://ieeexplore.ieee.org/abstract/document/8550778)] [[Python](https://github.com/yangyan92/Pytorch_ADMM-CSNet)]
- [2019] Evolutionary Multitasking Sparse Reconstruction: Framework and Case Study, IEEE TEVC [[Paper](https://ieeexplore.ieee.org/abstract/document/8540026)]
- [2018] FFDNet: Toward a Fast and Flexible Solution for CNN-Based Image Denoising, IEEE TIP [[Paper](https://ieeexplore.ieee.org/abstract/document/8365806)] [[Matlab](https://github.com/cszn/FFDNet)]
- [2017] Learning Proximal Operators: Using Denoising Networks for Regularizing Inverse Imaging Problems, ICCV [[Paper](https://openaccess.thecvf.com/content_iccv_2017/html/Meinhardt_Learning_Proximal_Operators_ICCV_2017_paper.html)] [[Python](https://github.com/tum-vision/learn_prox_ops)]
- [2017] Compressed Sensing using Generative Models, ICML  [[Paper](http://proceedings.mlr.press/v70/bora17a.html)]
- [2016] Maximal Sparsity with Deep Networks? NIPS [[Paper](https://proceedings.neurips.cc/paper_files/paper/2016/hash/0d73a25092e5c1c9769a9f3255caa65a-Abstract.html)]
- [2014] An Evolutionary Multiobjective Approach to Sparse Reconstruction, IEEE TEVC [[Paper](https://ieeexplore.ieee.org/abstract/document/6646243)]
- [2010] Learning Fast Approximations of Sparse Coding, ICML [[Paper](https://dl.acm.org/doi/abs/10.5555/3104322.3104374)] [[Matlab](https://github.com/minhnhat93/lfa_sc)]



<a name="Applications" />

## Applications

### Feature Selection
- [2023] Structured Sparsity Optimization With Non-Convex Surrogates of L2,0-Norm: A Unified Algorithmic Framework, IEEE TPAMI [[Paper](https://ieeexplore.ieee.org/abstract/document/9916142)]
- [2023] Learning Feature-Sparse Principal Subspace, IEEE TPAMI [[Paper](https://ieeexplore.ieee.org/abstract/document/9941008)] [[Matlab](https://github.com/icety3/FSPCA)]
- [2023] Fast Unsupervised Feature Selection With Bipartite Graph and L2,0-Norm Constraint, IEEE TKDE [[Paper](https://ieeexplore.ieee.org/abstract/document/9695194)]
- [2022] Column L2,0-norm Regularized Factorization Model of Low-Rank Matrix Recovery and Its Computation, SIAM Journal on Optimization [[Paper](https://epubs.siam.org/doi/abs/10.1137/20M136205X)]
- [2022] Unsupervised Feature Selection With Constrained l2,0-Norm and Optimized Graph, IEEE TNNLS [[Paper](https://ieeexplore.ieee.org/abstract/document/9309097)]
- [2022] Low-Rank Tensor Learning with Nonconvex Overlapped Nuclear Norm Regularization, Journal of Machine Learning Research  [[Paper](https://dl.acm.org/doi/abs/10.5555/3586589.3586725)]  [[Matlab](https://github.com/quanmingyao/FasTer)]
- [2019] Large-Scale Low-Rank Matrix Learning with Nonconvex Regularizers, IEEE TPAMI  [[Paper](https://ieeexplore.ieee.org/abstract/document/8416722)]  [[Matlab](https://github.com/quanmingyao/FaNCL)]
- [2013] Exact Top-k Feature Selection via L2,0-norm Constraint, IJCAI [[Paper](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=246737333a8e2e42b92be7a79f9508700b64c290)]  [[Matlab](https://github.com/guijiejie/Feature-selection/tree/master/Feature%20selection%20based%20on%20structured%20sparsity/Exact%20top-k%20feature%20selection%20via%20l2%2C0-norm%20constraint)]


### One-Bit Compressive Sensing

- [2023] 1-Bit Compressive Sensing for Efficient Federated Learning Over the Air, IEEE TWC [[Paper](https://ieeexplore.ieee.org/abstract/document/9912341)]
- [2022] Computing One-Bit Compressive Sensing via Double-Sparsity Constrained Optimization, IEEE TSP [[Paper](https://ieeexplore.ieee.org/abstract/document/9729395)] [[Matlab](https://github.com/ShenglongZhou/GPSP)]
- [2022] One-Bit Compressive Sensing: Can We Go Deep and Blind?, IEEE SPL  [[Paper](https://ieeexplore.ieee.org/abstract/document/9812512)]
- [2022] NBIHT: An Efficient Algorithm for 1-Bit Compressed Sensing With Optimal Error Decay Rate, IEEE ITI  [[Paper](https://ieeexplore.ieee.org/abstract/document/9597562)]
- [2021] Robust Recovery in 1-Bit Compressive Sensing via Lq-Constrained Least Squares, Signal Processing [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0165168420303662)]
- [2020] Model-Based Deep Learning for One-Bit Compressive Sensing, IEEE TSP [[Paper](https://ieeexplore.ieee.org/abstract/document/9187438)]
- [2020] Feature Selection and Classification of Noisy Proteomics Mass Spectrometry Data Based on One-Bit Perturbed
Compressed Sensing, Bioinformatics [[Paper](https://academic.oup.com/bioinformatics/article/36/16/4423/5838182)]
- [2019] One-Bit Compressive Sensing via Schur-Concave Function Minimization, IEEE TSP [[Paper](https://ieeexplore.ieee.org/abstract/document/8747470)] 
- [2019] Sparse Recovery and Dictionary Learning From Nonlinear Compressive Measurements, IEEE TSP [[Paper](https://ieeexplore.ieee.org/abstract/document/8834789)] 
- [2019] Computationally Efficient Sinusoidal Parameter Estimation From Signed Measurements: ADMM Approaches, IEEE SPL  [[Paper](https://ieeexplore.ieee.org/abstract/document/8882283)]
- [2019] Superset Technique for Approximate Recovery in One-Bit Compressed Sensing, NIPS [[Paper](https://proceedings.neurips.cc/paper_files/paper/2019/hash/c900ced7451da79502d29aa37ebb7b60-Abstract.html)] 
- [2018] Nonconvex Penalties with Analytical Solutions for One-Bit Compressive Sensing, Signal Processing [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0165168417303821)] 
- [2018] Robust Decoding from 1-Bit Compressive Sampling with Ordinary and Regularized Least Squares, SIAM Journal on Scientific Computing  [[Paper](https://epubs.siam.org/doi/abs/10.1137/17M1154102)] 
- [2018] Pinball Loss Minimization for One-Bit Compressive Sensing: Convex Models and Algorithms, Neurocomputing [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0925231218308087)] 
- [2018] A Survey on One-Bit Compressed Sensing: Theory and Applications, Frontiers of Computer Science  [[Paper](https://link.springer.com/article/10.1007/s11704-017-6132-7)]
- [2016] One-Bit Compressive Sensing With Norm Estimation, IEEE TIT [[Paper](https://ieeexplore.ieee.org/abstract/document/7434599)]
- [2016] Noisy 1-Bit Compressive Sensing: Models and Algorithms, Applied and Computational Harmonic Analysis [[Paper](https://www.sciencedirect.com/science/article/pii/S1063520314001419)]
- [2015] Robust One-Bit Bayesian Compressed Sensing with Sign-Flip Errors, IEEE SPL  [[Paper](https://ieeexplore.ieee.org/abstract/document/6963346)]
- [2014] Efficient Algorithms for Robust One-Bit Compressive Sensing, ICML [[Paper](http://proceedings.mlr.press/v32/zhangc14.html)]
- [2013] One-Bit Compressed Sensing by Linear Programming, Communications on Pure and Applied Mathematics  [[Paper](https://onlinelibrary.wiley.com/doi/abs/10.1002/cpa.21442)]
- [2013] One-Bit Compressed Sensing: Provable Support and Vector Recovery, ICML [[Paper](http://proceedings.mlr.press/v28/gopi13.html)]
- [2013] Robust 1-Bit Compressed Sensing and Sparse Logistic Regression: A Convex Programming Approach, IEEE ITI  [[Paper](https://ieeexplore.ieee.org/abstract/document/6294516)]
- [2013] Robust 1-Bit Compressive Sensing via Binary Stable Embeddings of Sparse Vectors, IEEE TIT [[Paper](https://ieeexplore.ieee.org/abstract/document/6418031)] 
- [2012] Robust 1-bit Compressive Sensing Using Adaptive Outlier Pursuit, IEEE TSP [[Paper](https://ieeexplore.ieee.org/abstract/document/6178284)]
- [2011] Trust, But Verify: Fast and Accurate Signal Recovery From 1-Bit Compressive Measurements, IEEE TSP [[Paper](https://ieeexplore.ieee.org/abstract/document/5955138)]
- [2009] Greedy Sparse Signal Reconstruction from Sign Measurements, IEEE ACSSC [[Paper](https://ieeexplore.ieee.org/abstract/document/5469926)]
- [2008] 1-Bit Compressive Sensing, IEEE CISS  [[Paper](https://ieeexplore.ieee.org/abstract/document/4558487)]




<a name="Links" />

## Links

### Journals
- Mathematical Programming [[Link](https://www.springer.com/journal/10107/)]
- SIAM Journal on Optimization [[Link](https://www.siam.org/publications/journals/siam-journal-on-optimization-siopt)]
- Mathematics of Operations Research [[Link](http://mor.journal.informs.org/)]

### Tools
- TFOCS: Templates for First-Order Conic Solvers [[Link](http://cvxr.com/tfocs/)]
- Scikit-feature: 40 Popular Feature Selection Algorithms With 25+ Datasets [[Link](https://github.com/jundongl/scikit-feature)]

