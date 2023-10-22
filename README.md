# Statistical Optimization

We now focus on nonconvex nonsmooth optimization problems in statistical machine learning, including 
  - [Sparse Optimization](#Sparse_Optimization)
  - [Manifold Optimization](#Manifold_Optimization)
  - [Distributed Optimization](#Distributed_Optimization)
- [Applications](#Applications)
  - [PCA](#PCA)
  - [LDA](#LDA)
  - [CCA](#CCA)
- [Journals](#Journals)
  
<strong> Last Update: October 22, 2023 </strong>


<a name="Sparse_Optimization" />

## Sparse Optimization
- [2022] Gradient Projection Newton Pursuit for Sparsity Constrained Optimization, ACHA [[paper](https://www.sciencedirect.com/science/article/pii/S1063520322000458)] [[code](https://github.com/ShenglongZhou/GPNP)]
- [2022] A Lagrange-Newton Algorithm for Sparse Nonlinear Programming, MP [[paper](https://link.springer.com/article/10.1007/s10107-021-01719-x)]
- [2021] Global and Quadratic Convergence of Newton Hard-Thresholding Pursuit, JMLR [[paper](https://jmlr.org/papers/volume22/19-026/19-026.pdf)] [[code](https://github.com/ShenglongZhou/NHTP)]
- [2021] Newton Method for L0-Regularized Optimization, NA [[paper](https://link.springer.com/article/10.1007/s11075-021-01085-x)] [[code](https://github.com/ShenglongZhou/NL0R)]
- [2017] Newton-Type Greedy Selection Methods for l0-Constrained Minimization, IEEE TPAMI [[paper](https://ieeexplore.ieee.org/abstract/document/7814339)]
- [2017] Gradient Hard Thresholding Pursuit, JMLR [[paper](https://www.jmlr.org/papers/volume18/14-415/14-415.pdf)]
- [2013] Greedy Sparsity-Constrained Optimization, JMLR [[paper](https://www.jmlr.org/papers/volume14/bahmani13a/bahmani13a.pdf)]
- [2012] Accelerated Iterative Hard Thresholding, SP [[paper](https://www.sciencedirect.com/science/article/abs/pii/S0165168411003197)]
- [2011] Hard Thresholding Pursuit: An Algorithm for Compressive Sensing, SINUM [[paper](https://epubs.siam.org/doi/abs/10.1137/100806278)] 
- [2010] Normalized Iterative Hard Thresholding: Guaranteed Stability and Performance, IEEE JSTSP [[paper](https://ieeexplore.ieee.org/abstract/document/5419091)] 
- [2010] CoSaMP: Iterative Signal Recovery from Incomplete and Inaccurate Samples, ACHA [[paper](https://www.sciencedirect.com/science/article/pii/S1063520308000638)]   [[code](https://ww2.mathworks.cn/matlabcentral/fileexchange/32402-cosamp-and-omp-for-sparse-recovery)]

<a name="Manifold_Optimization" />

## Manifold Optimization
- [2023] A Semismooth Newton Based Augmented Lagrangian Method for Nonsmooth Optimization on Matrix Manifolds, MP [[paper](https://link.springer.com/article/10.1007/s10107-022-01898-1)]
- [2022] Fast and Accurate Optimization on the Orthogonal Manifold Without Retraction, ICAIS [[paper](https://proceedings.mlr.press/v151/ablin22a)]
- [2022] CDOpt: A Python Package for A Class of Riemannian Optimization, arXiv [[paper](https://arxiv.org/abs/2212.02698)]
- [2021] Exact Penalty Function for L2,1 Norm Minimization over the Stiefel Manifold, SIOPT [[paper](https://epubs.siam.org/doi/abs/10.1137/20M1354313)]
- [2021] Orthogonal Deep Neural Networks, IEEE TPAMI [[paper](https://ieeexplore.ieee.org/abstract/document/8877742)]
- [2021] Majorization-Minimization on the Stiefel Manifold With Application to Robust Sparse PCA, IEEE TSP [[paper](https://ieeexplore.ieee.org/abstract/document/9354027)]
- [2021] Clustering by Orthogonal NMF Model and Non-Convex Penalty Optimization, IEEE TSP [[paper](https://ieeexplore.ieee.org/abstract/document/9508841)]
- [2020] Proximal Gradient method for Nonsmooth Optimization over the Stiefel Manifold, SIOPT [[paper](https://epubs.siam.org/doi/abs/10.1137/18M122457X)] [[code](https://github.com/chenshixiang/ManPG)]
- [2020] A Brief Introduction to Manifold Optimization, JOSRC [[paper](https://link.springer.com/article/10.1007/s40305-020-00295-9)]
- [2019] Parallelizable Algorithms for Optimization Problems With Orthogonality Constraints, SISC [[paper](https://epubs.siam.org/doi/abs/10.1137/18M1221679)]
- [2019] Structured Quasi-Newton Methods for Optimization With Orthogonality Constraints, SISC [[paper](https://epubs.siam.org/doi/abs/10.1137/18M121112X)]
- [2018] A New First-Order Algorithmic Framework for Optimization Problems with Orthogonality Constraints, SIOPT [[paper](https://epubs.siam.org/doi/abs/10.1137/16M1098759)] [[code](https://epubs.siam.org/doi/abs/10.1137/16M1098759)]
- [2018] Can We Gain More from Orthogonality Regularizations in Training Deep Networks?, NIPS [[paper](https://proceedings.neurips.cc/paper_files/paper/2018/hash/bf424cb7b0dea050a42b9739eb261a3a-Abstract.html)]
- [2015] A Framework of Constraint Preserving Update Schemes for Optimization on Stiefel Manifold, MP [[paper](https://link.springer.com/article/10.1007/s10107-014-0816-7)]
- [2014] A Splitting Method for Orthogonality Constrained Problems, JSC [[paper](https://link.springer.com/article/10.1007/s10915-013-9740-x)]
- [2013] A Feasible Method for Optimization With Orthogonality Constraints, MP [[paper](https://link.springer.com/article/10.1007/s10107-012-0584-1)]
  

<a name="Distributed_Optimization" />

## Distributed Optimization
- [2023] Federated Learning via Inexact ADMM, IEEE TPAMI [[paper](https://ieeexplore.ieee.org/abstract/document/10040221)] [[code](https://github.com/ShenglongZhou/FedADMM)]
- [2023] FedGiA: An Efficient Hybrid Algorithm for Federated Learning, IEEE TPAMI [[paper](https://ieeexplore.ieee.org/abstract/document/10106001)] [[code](https://github.com/ShenglongZhou/FedGiA)]
- [2022] Decentralized Optimization Over the Stiefel Manifold by an Approximate Augmented Lagrangian Function, IEEE TSP [[paper](https://ieeexplore.ieee.org/abstract/document/9798866)] [[code](http://lsec.cc.ac.cn/~liuxin/Solvers/DEST.zip)]
- [2022] Distributed Adaptive Newton Methods with Global Superlinear Convergence, Automatica [[paper](https://www.sciencedirect.com/science/article/pii/S0005109821006865)]
- [2022] Achieving Geometric Convergence for Distributed Optimization with Barzilai-Borwein Step Sizes, SCIS  [[paper](http://scis.scichina.com/en/2022/149204.pdf)]
- [2021] On Distributed Nonconvex Optimization: Projected Subgradient Method for Weakly Convex Problems in Networks, IEEE TAC [[paper](https://ieeexplore.ieee.org/abstract/document/9345428)]
- [2021] Decentralized Riemannian gradient descent on the Stiefel manifold, ICML [[paper](https://proceedings.mlr.press/v139/chen21g.html)] [[code](https://github.com/chenshixiang/Decentralized_Riemannian_gradient_descent_on_Stiefel_manifold)]
- [2021] A Penalty Alternating Direction Method of Multipliers for Convex Composite Optimization Over Decentralized Networks, IEEE TSP [[paper](https://ieeexplore.ieee.org/abstract/document/9466405)] 
- [2021] A Comprehensive Survey of Privacy-preserving Federated Learning: A Taxonomy, Review, and Future Directions, ACM CSUR [[paper](https://dl.acm.org/doi/abs/10.1145/3460427)] 
- [2020] Secure, Privacy-Preserving and Federated Machine Learning in Medical Imaging, Nature MI [[paper](https://www.nature.com/articles/s42256-020-0186-1)] 
- [2019] Federated Machine Learning: Concept and Applications, ACM TIST [[paper](https://dl.acm.org/doi/abs/10.1145/3298981)]
- [2016] On the Convergence of Decentralized Gradient Descent, SIOPT [[paper](https://epubs.siam.org/doi/abs/10.1137/130943170)]
- [2015] EXTRA: An Exact First-Order Algorithm for Decentralized Consensus Optimization, SIOPT [[paper](https://epubs.siam.org/doi/abs/10.1137/14096668X)]
- [2010] Distributed Stochastic Subgradient Projection Algorithms for Convex Optimization, JOTA [[paper](https://link.springer.com/article/10.1007/s10957-010-9737-7)]



<a name="Applications" />

## Applications

<a name="PCA" />

### PCA
- [2023] Sparse PCA via l2,p-Norm Regularization for Unsupervised Feature Selection, IEEE TPAMI [[paper](https://ieeexplore.ieee.org/abstract/document/9580680)] [[code](https://github.com/quiter2005/algorithm)]
- [2023] Learning Feature-Sparse Principal Subspace, IEEE TPAMI [[paper](https://ieeexplore.ieee.org/abstract/document/9941008)] [[code](https://github.com/icety3/FSPCA)]
- [2023] Fast Unsupervised Feature Selection With Bipartite Graph and l2,0-Norm Constraint, IEEE TKDE [[paper](https://ieeexplore.ieee.org/abstract/document/9695194)]
- [2023] A Communication-Efficient and Privacy-Aware Distributed Algorithm for Sparse PCA, COAP [[paper](https://link.springer.com/article/10.1007/s10589-023-00481-4)] [[code](http://lsec.cc.ac.cn/~liuxin/Solvers/DSSAL1.zip)]
- [2022] FAST-PCA: A Fast and Exact Algorithm for Distributed Principal Component Analysis, IEEE TSP [[paper](https://ieeexplore.ieee.org/abstract/document/10012289)]
- [2022] Solving Large-Scale Sparse PCA to Certifiable (Near) Optimality, JMLR [[paper](https://dl.acm.org/doi/abs/10.5555/3586589.3586602)]
- [2021] Communication-Efficient Distributed Covariance Sketch, With Application to Distributed PCA, JMLR [[paper](https://dl.acm.org/doi/abs/10.5555/3546258.3546338)]
- [2021] Distributed Principal Component Analysis with Limited Communication, NIPS [[paper](https://proceedings.neurips.cc/paper_files/paper/2021/hash/1680e9fa7b4dd5d62ece800239bb53bd-Abstract.html)] [[code](https://github.com/IST-DASLab/QRGD)]
- [2020] Communication-Efficient Distributed PCA by Riemannian Optimization, ICML [[paper](https://proceedings.mlr.press/v119/huang20e.html)]
- [2021] Learning Sparse PCA with Stabilized ADMM Method on Stiefel Manifold, IEEE TKDE [[paper](https://ieeexplore.ieee.org/abstract/document/8807218)]
- [2018] A Review of Distributed Algorithms for Principal Component Analysis, P IEEE [[paper](https://ieeexplore.ieee.org/abstract/document/8425655)]
- [2018] A Selective Overview of Sparse Principal Component Analysis, P IEEE [[paper](https://ieeexplore.ieee.org/abstract/document/8412518)]


<a name="LDA" />

### LDA
- [2023] Self-Weighted Unsupervised LDA, IEEE TNNLS [[paper](https://ieeexplore.ieee.org/abstract/document/9524457)] 
- [2023] Fisher's Linear Discriminant Analysis With Space-Folding Operations, IEEE TPAMI [[paper](https://ieeexplore.ieee.org/abstract/document/10005006)] 
- [2023] Linear Discriminant Analysis With Generalized Kernel Constraint for Robust Image Classification, PR [[paper](https://www.sciencedirect.com/science/article/abs/pii/S0031320322006756)]
- [2022] Neighborhood Linear Discriminant Analysis, PR [[paper](https://www.sciencedirect.com/science/article/pii/S0031320321005987)]
- [2021] Unsupervised Linear Discriminant Analysis for Jointly Clustering and Subspace Learning, IEEE TKDE [[paper](https://ieeexplore.ieee.org/abstract/document/8823955)]
- [2021] Large-Dimensional Characterization of Robust Linear Discriminant Analysis, IEEE TSP [[paper](https://ieeexplore.ieee.org/abstract/document/9415133)]
- [2020] Self-weighted Robust LDA for Multiclass Classification with Edge Classes, ACM TIST [[paper](https://dl.acm.org/doi/abs/10.1145/3418284)]
- [2020] Robust and Sparse Linear Discriminant Analysis via an Alternating Direction Method of Multipliers, IEEE TNNLS [[paper](https://ieeexplore.ieee.org/abstract/document/8710607)] 
- [2019] Robust Sparse Linear Discriminant Analysis, IEEE TCSVT [[paper](https://ieeexplore.ieee.org/abstract/document/8272002)] [[code](https://github.com/ckghostwj/RSLDA)]
- [2019] Multi-View Linear Discriminant Analysis Network, IEEE TIP [[paper](https://ieeexplore.ieee.org/abstract/document/8704986)] [[code](https://github.com/penghu-cs/MvLDAN)]
- [2016] Sparse Uncorrelated Linear Discriminant Analysis for Undersampled Problems, IEEE TNNLS [[paper](https://ieeexplore.ieee.org/abstract/document/7160770)] 

<a name="CCA" />

### CCA
- [2023] Discriminative Deep Generalized Dependency Analysis for Multi-View Data, IEEE TAI [[paper](https://ieeexplore.ieee.org/abstract/document/10225322)] 
- [2023] Communication-Efficient Federated Linear and Deep Generalized Canonical Correlation Analysis, IEEE TSP [[paper](https://ieeexplore.ieee.org/abstract/document/10099447)] [[code](https://github.com/XiaoFuLab/federated_max_var_gcca)]
- [2023] Tensor Generalized Canonical Correlation Analysis, IF [[paper](https://www.sciencedirect.com/science/article/pii/S1566253523003615)] 
- [2023] Discriminative Deep Canonical Correlation Analysis for Multi-View Data, IEEE TNNLS [[paper](https://ieeexplore.ieee.org/abstract/document/10143374)] 
- [2023] Learning High-Order Multi-View Representation by New Tensor Canonical Correlation Analysis, IEEE TCSVT [[paper](https://ieeexplore.ieee.org/document/10091146)] 
- [2022] Tensor Canonical Correlation Analysis Networks for Multi-View Remote Sensing Scene Recognition, IEEE TKDE [[paper](https://ieeexplore.ieee.org/abstract/document/9167483)]  [[code](https://github.com/AdvAttack/TCCANet-TKDE)]
- [2022] Deep Tensor CCA for Multi-View Learning, IEEE TBD [[paper](https://ieeexplore.ieee.org/document/9428614)] 
- [2021] A Survey on Canonical Correlation Analysis, IEEE TKDE [[paper](https://ieeexplore.ieee.org/abstract/document/8928538)]
- [2021] Tensor canonical correlation analysis with convergence and statistical guarantees, JCGS [[paper](https://www.tandfonline.com/doi/full/10.1080/10618600.2020.1856118)] [[code](https://github.com/youlinchen/TCCA)]
- [2021] From Canonical Correlation Analysis to Self-supervised Graph Neural Networks, NIPS [[paper](https://proceedings.neurips.cc/paper/2021/hash/00ac8ed3b4327bdd4ebbebcb2ba10a00-Abstract.html)]
- [2020] Cross-Modal Subspace Clustering via Deep Canonical Correlation Analysis, AAAI [[paper](https://ojs.aaai.org/index.php/AAAI/article/view/5808)]
- [2019] Deep RGB-D Canonical Correlation Analysis For Sparse Depth Completion, NIPS [[paper](https://proceedings.neurips.cc/paper_files/paper/2019/hash/e2c61965b5e23b47b77d7c51611b6d7f-Abstract.html)]
- [2019] Graph Multiview Canonical Correlation Analysis, IEEE TSP [[paper](https://ieeexplore.ieee.org/abstract/document/8686218)] 
- [2017] Canonical Correlation Analysis Networks for Two-View Image Recognition, IS [[paper](https://www.sciencedirect.com/science/article/pii/S0020025517300208)]
- [2016] Sparse Tensor Canonical Correlation Analysis for Micro-Expression Recognition, Neurocomputing [[paper](https://www.sciencedirect.com/science/article/pii/S0925231216305501)]
- [2015] On Deep Multi-View Representation Learning, ICML  [[paper](http://proceedings.mlr.press/v37/wangb15.html)] [[code](https://bitbucket.org/qingming_tang/deep-canonical-correlation-analysis/src/master/)]
- [2015] Tensor Canonical Correlation Analysis for Multi-View Dimension Reduction, IEEE TKDE [[paper](https://ieeexplore.ieee.org/abstract/document/7123622)]  [[code](https://github.com/rciszek/mdr_tcca)]
- [2013] Deep Canonical Correlation Analysis, ICML  [[paper](https://proceedings.mlr.press/v28/andrew13.html)] [[code](https://github.com/Michaelvll/DeepCCA)]
- [2009] Canonical Correlation Analysis of Video Volume Tensors for Action Categorization and Detection, IEEE TPAMI [[paper](https://ieeexplore.ieee.org/abstract/document/4547427)]  
- [2007] Tensor Canonical Correlation Analysis for Action Classification, CVPR [[paper](https://ieeexplore.ieee.org/abstract/document/4270162)]


<a name="Journals" />

## Journals
- IEEE Transactions on Pattern Analysis and Machine Intelligence  [[link](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=34)]
- IEEE Transactions on Signal Processing [[link](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=78)]
- IEEE Transactions on Neural Networks and Learning Systems  [[link](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=5962385)]
- IEEE Transactions on Automatic Control  [[link](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=9)]
- IEEE Journal of Selected Topics in Signal Processing  [[link](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=4200690)]
- IEEE Signal Processing Letters [[link](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=97)]
