# Sparse Optimization

We now focus on nonconvex nonsmooth optimization problems involving l0 norm, including
- [Surveys](#Surveys)
- [Regularized Optimization](#Regularized_Optimization)
- [Constrained Optimization](#Constrained_Optimization)
- [Structured Optimization](#Structured_Optimization)
- [Applications](#Applications)
  - [Sparse PCA](#Sparse_PCA)
  - [Sparse LDA](#Sparse_LDA)
  - [Sparse_CCA](#Sparse_CCA)
- [Journals](#Journals)
  
<strong> Last Update: October 23, 2023 </strong>



<a name="Surveys" />

### Surveys
- [2022] 稀疏优化二阶算法研究进展, 数值计算与计算机应用 [[paper](https://computmath.cjoe.ac.cn/szjs/CN/10.12288/szjs.s2021-0759)]
- [2020] 稀疏优化理论与算法若干新进展, 运筹学学报 [[paper](https://www.ort.shu.edu.cn/CN/10.15960/j.cnki.issn.1007-6093.2020.04.001)]
- [2020] Statistical Foundations of Data Science, CRC Press  [[paper](https://www.taylorfrancis.com/books/mono/10.1201/9780429096280/statistical-foundations-data-science-jianqing-fan-runze-li-cun-hui-zhang-hui-zou)]
- [2018] Sparse Optimization Theory and Methods, CRC Press [[paper](https://www.taylorfrancis.com/books/mono/10.1201/9781315113142/sparse-optimization-theory-methods-yun-bin-zhao)]
- [2015] Statistical Learning with sparsity: The Lasso and Generalizations, CRC Press [[paper](https://hastie.su.domains/StatLearnSparsity_files/SLS_corrected_1.4.16.pdf)]
- [2014] Sparse Modeling: Theory, Algorithms, and Applications, CRC Press [[paper](https://www.taylorfrancis.com/books/mono/10.1201/b17758/sparse-modeling-irina-rish-genady-grabarnik)]
- [2012] 压缩感知, 中国科学 [[paper](https://dds.sciengine.com/cfs/files/pdfs/view/1674-7216/bevBnqMiAzjDxRHki.pdf)]
- [2012] 压缩感知和稀疏优化简介, 运筹学学报  [[paper](https://www.ort.shu.edu.cn/CN/Y2012/V16/I3/49)]


<a name="Regularized_Optimization" />

## Regularized Optimization

### First-Order Methods 
- [2020] An Active Set Barzilar-Borwein Algorithm for l0 Regularized Optimization, Journal of Global Optimization [[paper](https://link.springer.com/article/10.1007/s10898-019-00830-w)]
- [2020] A Smoothing Proximal Gradient Algorithm for Nonsmooth Convex Regression with Cardinality Penalty, SIAM Journal on Numerical Analysis [[paper](https://epubs.siam.org/doi/abs/10.1137/18M1186009)]
- [2018] Proximal Mapping for Symmetric Penalty and Sparsity, SIAM Journal on Optimization  [[paper](https://epubs.siam.org/doi/abs/10.1137/17M1116544)]
- [2016] Image Restoration by Minimizing Zero Norm of Wavelet Frame Coefficients, Inverse Problems [[paper](https://iopscience.iop.org/article/10.1088/0266-5611/32/11/115004/meta)]
- [2015] Homotopy Based Algorithms for l0-Regularized Least-Squares, IEEE TSP [[paper](https://ieeexplore.ieee.org/abstract/document/7084156)]
- [2015] CGIHT: Conjugate Gradient Iterative Hard Thresholding for Compressed Sensing and Matrix Completion, Information and Inference [[paper](https://ieeexplore.ieee.org/abstract/document/8189185)]
- [2014] Iterative Hard Thresholding Methods for l0 Regularized Convex Cone Programming, Mathematical Programming [[paper](https://link.springer.com/article/10.1007/s10107-013-0714-4)]
- [2013] Sparse Approximation via Penalty Decomposition Methods, SIAM Journal on Optimization [[paper](https://epubs.siam.org/doi/abs/10.1137/100808071)]
- [2009] Iterative Hard Thresholding for Compressed Sensing, Applied and Computational Harmonic Analysis [[paper](https://www.sciencedirect.com/science/article/pii/S1063520309000384)]


### Second-Order Methods
- [2023] Revisiting Lq (0<=q<1) Norm Regularized Optimization, ArXiv [[paper](https://arxiv.org/abs/2306.14394)] [[code](https://github.com/ShenglongZhou/PSNP)]
- [2022] Newton Method for L0-Regularized Optimization, Numerical Algorithms [[paper](https://link.springer.com/article/10.1007/s11075-021-01085-x)] [[code](https://github.com/ShenglongZhou/NL0R)]
- [2018] A Constructive Approach to l0 Penalized Regression, Journal of Machine Learning Research [[paper](https://www.jmlr.org/papers/volume19/17-194/17-194.pdf)]
- [2015] A Primal Dual Active Set with Continuation Algorithm for the l0-Regularized Optimization Problem, Applied and Computational Harmonic Analysis  [[paper](https://www.sciencedirect.com/science/article/pii/S1063520314001250)]
- [2013] A Variational Approach to Sparsity Optimization Based on Lagrange Multiplier Theory, Inverse Problems [[paper](https://iopscience.iop.org/article/10.1088/0266-5611/30/1/015001/meta)]

<a name="Constrained_Optimization" />

## Constrained Optimization

### First-Order Methods 
- [2017] Gradient Hard Thresholding Pursuit, Journal of Machine Learning Research [[paper](https://www.jmlr.org/papers/volume18/14-415/14-415.pdf)]
- [2017] A Convergent Iterative Hard Thresholding for Nonnegative Sparsity Optimization, Pacific Journal of Optimization  [[paper](http://www.yokohamapublishers.jp/online2/oppjo/vol13/p325.html)] [[code](https://github.com/ShenglongZhou/IIHT)]
- [2016] On the Minimization over Sparse Symmetric Sets: Projections, Optimality Conditions, and Algorithms, Mathematics of Operations Research [[paper](https://pubsonline.informs.org/doi/abs/10.1287/moor.2015.0722)] 
- [2015] On Solutions of Sparsity Constrained Optimization, Journal of the Operations Research Society of China [[paper](https://link.springer.com/article/10.1007/s40305-015-0101-3)]
- [2013] Greedy Sparsity-Constrained Optimization, Journal of Machine Learning Research [[paper](https://www.jmlr.org/papers/volume14/bahmani13a/bahmani13a.pdf)]
- [2013] Sparsity Constrained Nonlinear Optimization: Optimality Conditions and Algorithms, SIAM Journal on Optimization [[paper](https://epubs.siam.org/doi/abs/10.1137/120869778)]
- [2012] Accelerated Iterative Hard Thresholding, Signal Processing [[paper](https://www.sciencedirect.com/science/article/abs/pii/S0165168411003197)]
- [2011] Hard Thresholding Pursuit: An Algorithm for Compressive Sensing, SIAM Journal on Numerical Analysis [[paper](https://epubs.siam.org/doi/abs/10.1137/100806278)]
- [2010] Normalized Iterative Hard Thresholding: Guaranteed Stability and Performance, IEEE JSTSP [[paper](https://ieeexplore.ieee.org/abstract/document/5419091)]
- [2009] CoSaMP: Iterative Signal Recovery from Incomplete and Inaccurate Samples, Applied and Computational Harmonic Analysis [[paper](https://www.sciencedirect.com/science/article/pii/S1063520308000638)] [[code](https://ww2.mathworks.cn/matlabcentral/fileexchange/32402-cosamp-and-omp-for-sparse-recovery)]
- [2007] Gradient Projection for Sparse Reconstruction: Application to Compressed Sensing and Other Inverse Problems, IEEE JSTSP [[paper](https://ieeexplore.ieee.org/abstract/document/4407762)]
- [2007] Signal Recovery From Random Measurements Via Orthogonal Matching Pursuit, IEEE TIT [[paper](https://ieeexplore.ieee.org/abstract/document/4385788)]
- [1993] Orthogonal Matching Pursuit: Recursive Function Approximation with Applications to Wavelet Decomposition, ACSSC  [[paper](https://ieeexplore.ieee.org/abstract/document/342465)]

  
### Second-Order Methods
- [2022] Gradient Projection Newton Pursuit for Sparsity Constrained Optimization, Applied and Computational Harmonic Analysis [[paper](https://www.sciencedirect.com/science/article/pii/S1063520322000458)] [[code](https://github.com/ShenglongZhou/GPNP)]
- [2022] A Lagrange-Newton Algorithm for Sparse Nonlinear Programming, Mathematical Programming [[paper](https://link.springer.com/article/10.1007/s10107-021-01719-x)]
- [2021] Global and Quadratic Convergence of Newton Hard-Thresholding Pursuit, Journal of Machine Learning Research [[paper](https://jmlr.org/papers/volume22/19-026/19-026.pdf)] [[code](https://github.com/ShenglongZhou/NHTP)]
- [2020] Greedy Projected Gradient-Newton Method for Sparse Logistic Regression, IEEE TNNLS [[paper](https://ieeexplore.ieee.org/abstract/document/8688642)]
- [2017] Newton-Type Greedy Selection Methods for l0 -Constrained Minimization, IEEE TPAMI [[paper](https://ieeexplore.ieee.org/abstract/document/7814339)]
- [2017] Fast Newton Hard Thresholding Pursuit for Sparsity Constrained Non-Convex Optimization, KDD [[paper](https://dl.acm.org/doi/abs/10.1145/3097983.3098165)]
- [2013] Greedy Sparsity-Constrained Optimization, Journal of Machine Learning Research [[paper](https://www.jmlr.org/papers/volume14/bahmani13a/bahmani13a.pdf)]



<a name="Structured_Optimization" />

## Structured Optimization  
- [2023] Fast Unsupervised Feature Selection With Bipartite Graph and l2,0-Norm Constraint, IEEE TKDE [[paper](https://ieeexplore.ieee.org/abstract/document/9695194)]
- [2022] Column L2,0-norm Regularized Factorization Model of Low-Rank Matrix Recovery and Its Computation, SIAM Journal on Optimization [[paper](https://epubs.siam.org/doi/abs/10.1137/20M136205X)]
- [2022] Unsupervised Feature Selection With Constrained l2,0-Norm and Optimized Graph, IEEE TNNLS [[paper](https://ieeexplore.ieee.org/abstract/document/9309097)]
- [2019] Optimization Problems Involving Group Sparsity Terms, Mathematical Programming [[paper](https://link.springer.com/article/10.1007/s10107-018-1277-1)]
- [2016] Structured Sparse Regression via Greedy Hard Thresholding, NIPS [[paper](https://proceedings.neurips.cc/paper_files/paper/2016/hash/8e82ab7243b7c66d768f1b8ce1c967eb-Abstract.html)]
- [2017] Tree Structure Sparsity Pattern Guided Convex Optimization for Compressive Sensing of Large-Scale Images, IEEE TIP [[paper](https://ieeexplore.ieee.org/abstract/document/7762896)]
- [2016] Group-Sparse Model Selection: Hardness and Relaxations, IEEE TIT [[paper](https://ieeexplore.ieee.org/abstract/document/7549088)]
- [2013] Exact Top-k Feature Selection via L2, 0-norm Constraint, IJCAI [[paper](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=246737333a8e2e42b92be7a79f9508700b64c290)]
- [2011] Structured Compressed Sensing: From Theory to Applications, IEEE TIP [[paper](https://ieeexplore.ieee.org/abstract/document/5954192)]
- [2009] Learning with Structured Sparsity, ICML [[paper](https://dl.acm.org/doi/abs/10.1145/1553374.1553429)]



<a name="Applications" />

## Applications

<a name="Sparse_PCA" />

### Sparse PCA 
- [2023] Sparse PCA via l2,p-Norm Regularization for Unsupervised Feature Selection, IEEE TPAMI [[paper](https://ieeexplore.ieee.org/abstract/document/9580680)] [[code](https://github.com/quiter2005/algorithm)]
- [2023] Learning Feature-Sparse Principal Subspace, IEEE TPAMI [[paper](https://ieeexplore.ieee.org/abstract/document/9941008)] [[code](https://github.com/icety3/FSPCA)]
- [2023] Fast Unsupervised Feature Selection With Bipartite Graph and l2,0-Norm Constraint, IEEE TKDE [[paper](https://ieeexplore.ieee.org/abstract/document/9695194)]
- [2023] A Communication-Efficient and Privacy-Aware Distributed Algorithm for Sparse PCA, Computational Optimization and Applications [[paper](https://link.springer.com/article/10.1007/s10589-023-00481-4)] [[code](http://lsec.cc.ac.cn/~liuxin/Solvers/DSSAL1.zip)]
- [2022] FAST-PCA: A Fast and Exact Algorithm for Distributed Principal Component Analysis, IEEE TSP [[paper](https://ieeexplore.ieee.org/abstract/document/10012289)]
- [2022] Solving Large-Scale Sparse PCA to Certifiable (Near) Optimality, Journal of Machine Learning Research [[paper](https://dl.acm.org/doi/abs/10.5555/3586589.3586602)]
- [2021] Communication-Efficient Distributed Covariance Sketch, With Application to Distributed PCA, Journal of Machine Learning Research [[paper](https://dl.acm.org/doi/abs/10.5555/3546258.3546338)]
- [2021] Distributed Principal Component Analysis with Limited Communication, NIPS [[paper](https://proceedings.neurips.cc/paper_files/paper/2021/hash/1680e9fa7b4dd5d62ece800239bb53bd-Abstract.html)] [[code](https://github.com/IST-DASLab/QRGD)]
- [2020] Communication-Efficient Distributed PCA by Riemannian Optimization, ICML [[paper](https://proceedings.mlr.press/v119/huang20e.html)]
- [2021] Learning Sparse PCA with Stabilized ADMM Method on Stiefel Manifold, IEEE TKDE [[paper](https://ieeexplore.ieee.org/abstract/document/8807218)]
- [2018] A Review of Distributed Algorithms for Principal Component Analysis, P IEEE [[paper](https://ieeexplore.ieee.org/abstract/document/8425655)]
- [2018] A Selective Overview of Sparse Principal Component Analysis, P IEEE [[paper](https://ieeexplore.ieee.org/abstract/document/8412518)]


<a name="Sparse_LDA" />

### Sparse LDA
- [2023] Self-Weighted Unsupervised LDA, IEEE TNNLS [[paper](https://ieeexplore.ieee.org/abstract/document/9524457)] 
- [2023] Fisher's Linear Discriminant Analysis With Space-Folding Operations, IEEE TPAMI [[paper](https://ieeexplore.ieee.org/abstract/document/10005006)] 
- [2023] Linear Discriminant Analysis With Generalized Kernel Constraint for Robust Image Classification, Pattern Recognition [[paper](https://www.sciencedirect.com/science/article/abs/pii/S0031320322006756)]
- [2022] Neighborhood Linear Discriminant Analysis, PR [[paper](https://www.sciencedirect.com/science/article/pii/S0031320321005987)]
- [2021] Unsupervised Linear Discriminant Analysis for Jointly Clustering and Subspace Learning, IEEE TKDE [[paper](https://ieeexplore.ieee.org/abstract/document/8823955)]
- [2021] Large-Dimensional Characterization of Robust Linear Discriminant Analysis, IEEE TSP [[paper](https://ieeexplore.ieee.org/abstract/document/9415133)]
- [2020] Self-weighted Robust LDA for Multiclass Classification with Edge Classes, ACM TIST [[paper](https://dl.acm.org/doi/abs/10.1145/3418284)]
- [2020] Robust and Sparse Linear Discriminant Analysis via an Alternating Direction Method of Multipliers, IEEE TNNLS [[paper](https://ieeexplore.ieee.org/abstract/document/8710607)] 
- [2019] Robust Sparse Linear Discriminant Analysis, IEEE TCSVT [[paper](https://ieeexplore.ieee.org/abstract/document/8272002)] [[code](https://github.com/ckghostwj/RSLDA)]
- [2019] Multi-View Linear Discriminant Analysis Network, IEEE TIP [[paper](https://ieeexplore.ieee.org/abstract/document/8704986)] [[code](https://github.com/penghu-cs/MvLDAN)]
- [2016] Sparse Uncorrelated Linear Discriminant Analysis for Undersampled Problems, IEEE TNNLS [[paper](https://ieeexplore.ieee.org/abstract/document/7160770)] 

<a name="Sparse_CCA" />

### Sparse CCA
- [2023] Discriminative Deep Generalized Dependency Analysis for Multi-View Data, IEEE TAI [[paper](https://ieeexplore.ieee.org/abstract/document/10225322)] 
- [2023] Communication-Efficient Federated Linear and Deep Generalized Canonical Correlation Analysis, IEEE TSP [[paper](https://ieeexplore.ieee.org/abstract/document/10099447)] [[code](https://github.com/XiaoFuLab/federated_max_var_gcca)]
- [2023] Tensor Generalized Canonical Correlation Analysis, Information Fusion [[paper](https://www.sciencedirect.com/science/article/pii/S1566253523003615)] 
- [2023] Discriminative Deep Canonical Correlation Analysis for Multi-View Data, IEEE TNNLS [[paper](https://ieeexplore.ieee.org/abstract/document/10143374)] 
- [2023] Learning High-Order Multi-View Representation by New Tensor Canonical Correlation Analysis, IEEE TCSVT [[paper](https://ieeexplore.ieee.org/document/10091146)] 
- [2022] Tensor Canonical Correlation Analysis Networks for Multi-View Remote Sensing Scene Recognition, IEEE TKDE [[paper](https://ieeexplore.ieee.org/abstract/document/9167483)]  [[code](https://github.com/AdvAttack/TCCANet-TKDE)]
- [2022] Deep Tensor CCA for Multi-View Learning, IEEE TBD [[paper](https://ieeexplore.ieee.org/document/9428614)] 
- [2021] A Survey on Canonical Correlation Analysis, IEEE TKDE [[paper](https://ieeexplore.ieee.org/abstract/document/8928538)]
- [2021] Tensor canonical correlation analysis with convergence and statistical guarantees, Journal of Computational and Graphical Statistics [[paper](https://www.tandfonline.com/doi/full/10.1080/10618600.2020.1856118)] [[code](https://github.com/youlinchen/TCCA)]
- [2021] From Canonical Correlation Analysis to Self-supervised Graph Neural Networks, NIPS [[paper](https://proceedings.neurips.cc/paper/2021/hash/00ac8ed3b4327bdd4ebbebcb2ba10a00-Abstract.html)]
- [2020] Cross-Modal Subspace Clustering via Deep Canonical Correlation Analysis, AAAI [[paper](https://ojs.aaai.org/index.php/AAAI/article/view/5808)]
- [2019] Deep RGB-D Canonical Correlation Analysis For Sparse Depth Completion, NIPS [[paper](https://proceedings.neurips.cc/paper_files/paper/2019/hash/e2c61965b5e23b47b77d7c51611b6d7f-Abstract.html)]
- [2019] Graph Multiview Canonical Correlation Analysis, IEEE TSP [[paper](https://ieeexplore.ieee.org/abstract/document/8686218)] 
- [2017] Canonical Correlation Analysis Networks for Two-View Image Recognition, Information Sciences [[paper](https://www.sciencedirect.com/science/article/pii/S0020025517300208)]
- [2016] Sparse Tensor Canonical Correlation Analysis for Micro-Expression Recognition, Neurocomputing [[paper](https://www.sciencedirect.com/science/article/pii/S0925231216305501)]
- [2015] On Deep Multi-View Representation Learning, ICML  [[paper](http://proceedings.mlr.press/v37/wangb15.html)] [[code](https://bitbucket.org/qingming_tang/deep-canonical-correlation-analysis/src/master/)]
- [2015] Tensor Canonical Correlation Analysis for Multi-View Dimension Reduction, IEEE TKDE [[paper](https://ieeexplore.ieee.org/abstract/document/7123622)]  [[code](https://github.com/rciszek/mdr_tcca)]
- [2013] Deep Canonical Correlation Analysis, ICML  [[paper](https://proceedings.mlr.press/v28/andrew13.html)] [[code](https://github.com/Michaelvll/DeepCCA)]
- [2009] Canonical Correlation Analysis of Video Volume Tensors for Action Categorization and Detection, IEEE TPAMI [[paper](https://ieeexplore.ieee.org/abstract/document/4547427)]  
- [2007] Tensor Canonical Correlation Analysis for Action Classification, CVPR [[paper](https://ieeexplore.ieee.org/abstract/document/4270162)]


<a name="Journals" />

## Journals
- Mathematical Programming [[link](https://www.springer.com/journal/10107/)]
- SIAM Journal on Optimization [[link](https://www.siam.org/publications/journals/siam-journal-on-optimization-siopt)]
- Mathematics of Operations Research [[link](http://mor.journal.informs.org/)]
