# A Handbook on Riemannian Optimization
This repo contains papers, books, tutorials and resources on Riemannian optimization.

⚡ This repo is currently under-developed. Any suggestions are welcome!⚡


<details open>
  <summary><h2><b> Contents </b></h2></summary>

[A Handbook on Riemannian Optimization](#a-handbook-on-riemannian-optimization)
- [1. Books](#1-books)
- [2. Papers](#2-papers)
  - [Acceleration](#acceleration)
  - [Conjugate Gradient Methods](#conjugate-gradient-methods)
  - [Quasi-Newton Methods](#quasi-newton-methods)
  - [Second-order Methods](#second-order-methods)
  - [Zeroth-Order Optimization](#zeroth-order-optimization)
  - [Stochastic Optimization](#stochastic-optimization)
    - [Variance Reduction](#variance-reduction)
    - [Adaptive Gradient](#adaptive-gradient)
  - [Geodesic Convex and Nonconvex Optimization](#geodesic-convex-and-nonconvex-optimization)
  - [Nonsmooth Optimization](#nonsmooth-optimization)
  - [Constrained Optimization](#constrained-optimization)
  - [Bilevel and Min-max Optimization](#bilevel-and-min-max-optimization)
    - [Bilevel Optimization](#bilevel-optimization)
    - [Min-max Optimization](#min-max-optimization)
  - [Scalable Riemannian Optimization](#scalable-riemannian-optimization)
    - [Stiefel (Orthogonal) Manifold](#stiefel-orthogonal-manifold)
    - [SPD Manifold](#spd-manifold)
    - [General Manifold](#general-manifold)
  - [Differentially Private Optimization](#differentially-private-optimization)
- [3. Software](#3-software)
</details>

# 1. Books

1. [Optimization Algorithms on Matrix Manifolds](https://press.princeton.edu/absil?srsltid=AfmBOorlfmgaTCzFeGcEDw9mxNrVvWMaKhY578kDlMOKlYY9D-G9ar3n) *Cambridge University Press*. 2023
2. [Convex Analysis and Optimization in Hadamard Spaces](https://www.degruyter.com/document/doi/10.1515/9783110361629/html) *De Gruyter* 2014
3. [An introduction to Optimization on smooth manifolds](https://www.nicolasboumal.net/book/) *Princeton University Press*. 2008
4. [Convex Functions and Optimization Methods on Riemannian Manifolds](https://link.springer.com/book/10.1007/978-94-015-8390-9) *Kluwer Academic Publishers Group* 1994

# 2. Papers

## Acceleration
> Accelerated gradient methods and analysis on Riemannian manifolds.

[Accelerated Gradient Dynamics on Riemannian Manifolds: Faster Rate and Trajectory Convergence](https://arxiv.org/pdf/2312.06366) *Arxiv*. 2023.

[Riemannian accelerated gradient methods via extrapolation](https://proceedings.mlr.press/v206/han23a/han23a.pdf) *AISTATS*. 2023.

[Accelerated Riemannian Optimization: Handling Constraints with a Prox to Bound Geometric Penalties](https://proceedings.mlr.press/v195/martinez-rubio23a/martinez-rubio23a.pdf) *COLT*. 2023.

[Riemannian Anderson Mixing Methods for Minimizing C2-Functions on Riemannian Manifolds](https://arxiv.org/pdf/2309.04091) *Arxiv*. 2023.


[An Accelerated First-Order Method for Non-convex Optimization on Manifolds](https://link.springer.com/article/10.1007/s10208-022-09573-9) *Found. Comput. Math.* 2022.

[Understanding Riemannian acceleration via a proximal extragradient framework](https://proceedings.mlr.press/v178/jin22a/jin22a.pdf) *COLT*. 2022.

[A variational formulation of accelerated optimization on Riemannian manifolds](https://epubs.siam.org/doi/abs/10.1137/21M1395648) *SIAM J. Math. Data Sci.* 2022.

[Global Riemannian acceleration in hyperbolic and spherical spaces](https://proceedings.mlr.press/v167/martinez-rubio22a/martinez-rubio22a.pdf) *ALT*. 2022.

[Accelerated Gradient Methods for Geodesically Convex Optimization: Tractable Algorithms and Convergence Analysis](https://proceedings.mlr.press/v162/kim22k/kim22k.pdf) *ICML*. 2022.

[Accelerated optimization with orthogonality constraints](https://www.global-sci.org/intro/article_detail.html?journal=undefined&article_id=18372) *J. Comp. Math.* 2021.

[Momentum Improves Optimization on Riemannian Manifolds](https://proceedings.mlr.press/v130/alimisis21a/alimisis21a.pdf) *AISTATS*. 2021.

[A Nesterov-type Acceleration with Adaptive Localized Cayley Parametrization for Optimization over the Stiefel Manifold](https://ieeexplore.ieee.org/abstract/document/9287609) *EUSIPCO* 2020.

[From Nesterov’s Estimate Sequence to Riemannian Acceleration](https://proceedings.mlr.press/v125/ahn20a/ahn20a.pdf) *COLT*. 2020.

[A continuous-time perspective for modeling acceleration in Riemannian optimization](https://proceedings.mlr.press/v108/alimisis20a/alimisis20a.pdf) *AISTATS*. 2020.

[Accelerated First-order Methods for Geodesically Convex Optimization on Riemannian Manifolds](https://proceedings.neurips.cc/paper_files/paper/2017/file/6ef80bb237adf4b6f77d0700e1255907-Paper.pdf) *NeurIPS*. 2017.

[Towards Riemannian accelerated gradient methods](https://arxiv.org/pdf/1806.02812) *Arxiv*. 2018.

## Conjugate Gradient Methods
> Riemannian conjugate gradient methods

[Practical gradient and conjugate gradient methods on flag manifolds](https://link.springer.com/article/10.1007/s10589-024-00568-6) *Comput. Optim. Appl.* 2024.

[Nonlinear conjugate gradient method for vector optimization on Riemannian manifolds with retraction and vector transport](https://www.sciencedirect.com/science/article/pii/S0096300324004624) *Appl. Math. Comput.*. 2024.

[Decentralized Riemannian Conjugate Gradient Method on the Stiefel Manifold](https://openreview.net/forum?id=PQbFUMKLFp) *ICLR*. 2024.

[Two efficient nonlinear conjugate gradient methods for Riemannian manifolds](https://link.springer.com/article/10.1007/s40314-024-02920-2) *Comput. Optim. Appl.* 2024.

[An improved Riemannian conjugate gradient method and its application to robust matrix completion](https://link.springer.com/article/10.1007/s11075-023-01688-6) *Numer. Algorithms.* 2024.


[Conjugate gradient methods for optimization problems on symplectic Stiefel manifold](https://ieeexplore.ieee.org/abstract/document/10159009) *IEEE Control Syst. Lett.* 2023.

[A hybrid Riemannian conjugate gradient method for nonconvex optimization problems](https://link.springer.com/article/10.1007/s12190-022-01772-5) *J. Appl. Math.* 2023.

[A class of spectral conjugate gradient methods for Riemannian optimization](https://link.springer.com/article/10.1007/s11075-022-01495-5) *Numer. Algorithms.* 2023.

[Global convergence of Hager–Zhang type Riemannian conjugate gradient method](https://www.sciencedirect.com/science/article/pii/S0096300322007536) *Appl. Math. Comput.* 2023.

[Riemannian Conjugate Gradient Methods: General Framework and Specific Algorithms with Convergence Analyses](https://epubs.siam.org/doi/abs/10.1137/21M1464178) *SIAM J. Optim.* 2022.

[Sufficient descent Riemannian conjugate gradient methods](https://link.springer.com/article/10.1007/s10957-021-01874-3) *J. Optim. Theory Appl.*  2021.

[Riemannian Modified Polak--Ribière--Polyak Conjugate Gradient Order Reduced Model by Tensor Techniques](https://epubs.siam.org/doi/abs/10.1137/19M1257147) *SIAM J. Matrix Anal. Appl.* 2020.

[Hybrid Riemannian conjugate gradient methods with global convergence properties](https://link.springer.com/article/10.1007/s10589-020-00224-9) *Comput. Optim. Appl.* 2020.

[Riemannian conjugate gradient methods with inverse retraction](https://link.springer.com/article/10.1007/s10589-020-00219-6) *Comput. Optim. Appl.* 2020.

[A Riemannian Fletcher--Reeves Conjugate Gradient Method for Doubly Stochastic Inverse Eigenvalue Problems](https://epubs.siam.org/doi/abs/10.1137/15M1023051) *SIAM J. Matrix Anal. Appl.* 2016.

[A Dai–Yuan-type Riemannian conjugate gradient method with the weak Wolfe conditions](https://link.springer.com/article/10.1007/s10589-015-9801-1) *Comput. Optim. Appl.* 2016.

[A new, globally convergent Riemannian conjugate gradient method](https://www.tandfonline.com/doi/full/10.1080/02331934.2013.836650) *Optim.* 2013.

[Conjugate gradient on Grassmann manifolds for robust subspace estimation](https://www.sciencedirect.com/science/article/pii/S0262885611000989) *Image Vis. Comput.* 2012.

[Conjugate gradient algorithm for optimization under unitary matrix constraint](https://www.sciencedirect.com/science/article/pii/S0165168409000814)  *Signal Process.* 2009.




## Quasi-Newton Methods
> Quasi-Newton methods on Riemannian manifolds.

[A restricted memory quasi-Newton bundle method for nonsmooth optimization on Riemannian manifolds](https://arxiv.org/pdf/2402.18308) *Arxiv*. 2024.

[Modified Memoryless Spectral-Scaling Broyden Family on Riemannian Manifolds](https://link.springer.com/article/10.1007/s10957-024-02449-8) *J. Optim. Theory Appl.* 2024.

[A Riemannian subspace BFGS trust region method](https://link.springer.com/article/10.1007/s11590-022-01964-9) *Optim. Lett.* 2023.

[Memoryless Quasi-Newton Methods Based on the Spectral-Scaling Broyden Family for Riemannian Optimization](https://link.springer.com/article/10.1007/s10957-023-02183-7) *J. Optim. Theory Appl.* 2023.

[Generalization of Quasi-Newton methods: application to robust symmetric multisecant updates](https://proceedings.mlr.press/v130/scieur21a.html) *AISTATS*. 2021.

[Vector Transport Free Riemannian LBFGS for Optimization on Symmetric Positive Definite Matrix Manifolds](https://proceedings.mlr.press/v157/godaz21a.html) *ACML*. 2021.

[Adaptive regularization with cubics on manifolds](https://link.springer.com/article/10.1007/s10107-020-01505-1) *Math. Prog.* 2020

[Structured Quasi-Newton Methods for Optimization with Orthogonality Constraints](https://epubs.siam.org/doi/abs/10.1137/18M121112X) *SIAM J. Sci. Comput.* 2019.

[Riemannian stochastic quasi-Newton algorithm with variance reduction and its convergence analysis](https://proceedings.mlr.press/v84/kasai18a/kasai18a.pdf) *AISTATS*. 2018.

[A Riemannian BFGS method without differentiated retraction for nonconvex optimization problems](https://epubs.siam.org/doi/abs/10.1137/17M1127582) *SIAM J. Optim.* 2018.

[A Riemannian Limited-Memory BFGS Algorithm for Computing the Matrix Geometric Mean](https://www.sciencedirect.com/science/article/pii/S1877050916310250) *ICCS*. 2016.

[A Broyden Class of Quasi-Newton Methods for Riemannian Optimization](https://epubs.siam.org/doi/10.1137/140955483) *SIAM J. Optim.* 2015.

[Riemannian BFGS Algorithm with Applications](https://link.springer.com/chapter/10.1007/978-3-642-12598-0_16) *Recent Advances in Optimization and its Applications in Engineering*. 2010.

[Trust-Region Methods on Riemannian Manifolds](https://link.springer.com/article/10.1007/s10208-005-0179-9) *FoCM* 2007

## Second-order Methods
> Second-order methods on Riemannian manifolds.

[Sub-sampled adaptive trust region method on Riemannian manifolds](https://onlinelibrary.wiley.com/doi/full/10.1002/nla.2557) *Numer. Linear Algebra Appl.* 2024.

[Inexact Adaptive Cubic Regularization Algorithms on Riemannian Manifolds and Application](https://arxiv.org/pdf/2405.02588) *Arxiv*. 2024.

[A Riemannian Dimension-Reduced Second-Order Method with Application in Sensor Network Localization](https://epubs.siam.org/doi/full/10.1137/23M1567229) *SIAM J. Sci. Comput.* 2024.

[Riemannian Trust Region Methods for SC1 Minimization](https://arxiv.org/pdf/2307.00490) *J. Sci. Comput.* 2024.

[Adaptive trust-region method on Riemannian manifold](https://dl.acm.org/doi/abs/10.1007/s10915-023-02288-1) *J. Sci. Comput.* 2023.

[Faster Riemannian Newton-type optimization by subsampling and cubic regularization](https://link.springer.com/article/10.1007/s10994-023-06321-0) *Mach. Learn.* 2023.

[A Limited-Memory Riemannian Symmetric Rank-One Trust-Region Method with a Restart Strategy](https://link.springer.com/article/10.1007/s10915-022-01962-0) *J. Sci. Comput.* 2022.

[Adaptive regularization with cubics on manifolds](https://link.springer.com/article/10.1007/s10107-020-01505-1) *Math. Program.* 2021.

[A Nonmonotone Trust Region Method for Unconstrained Optimization Problems on Riemannian Manifolds](https://link.springer.com/article/10.1007/s10957-020-01796-6) *J. Optim. Theory Appl.* 2021.

[Damped Newton’s method on Riemannian manifolds](https://link.springer.com/article/10.1007/s10898-020-00885-0) *J. Glob. Optim.* 2020.

[A Riemannian trust-region method for low-rank tensor completion](https://onlinelibrary.wiley.com/doi/abs/10.1002/nla.2175?casa_token=MKJnAMSdqSkAAAAA%3A3JFlcktsyK9aDrDX7xw6gpZ0VKETFlLS5RAgZj9i4chKkeqDajMFN5lNAFstLcTnQsOa0LHfQenBHXWB) *Numer. Linear Algebra Appl.* 2018.

[Adaptive Quadratically Regularized Newton Method for Riemannian Optimization](https://epubs.siam.org/doi/abs/10.1137/17M1142478) *SIAM J. Matrix Anal. Appl.* 2018.

[Inexact trust-region algorithms on Riemannian manifolds](https://proceedings.neurips.cc/paper_files/paper/2018/file/3e9e39fed3b8369ed940f52cf300cf88-Paper.pdf) *NeurIPS*. 2018.

[On the Superlinear Convergence of Newton’s Method on Riemannian Manifolds](https://link.springer.com/article/10.1007/s10957-017-1107-2) *J. Optim. Theory Appl.* 2017.

[A Riemannian symmetric rank-one trust-region method](https://link.springer.com/article/10.1007/s10107-014-0765-1) *Math. Program.* 2015.

[Low-rank matrix completion via preconditioned optimization on the Grassmann manifold](https://www.sciencedirect.com/science/article/pii/S0024379515001342) *Linear Algebra Its Appl.* 2015.

[Riemannian Trust Regions with Finite-Difference Hessian Approximations are Globally Convergent](https://link.springer.com/chapter/10.1007/978-3-319-25040-3_50) *GSI*. 2015.

[RTRMC: A Riemannian trust-region method for low-rank matrix completion](https://proceedings.neurips.cc/paper_files/paper/2011/file/37bc2f75bf1bcfe8450a1a41c200364c-Paper.pdf) *NeurIPS*. 2011.

[Trust-Region Methods on Riemannian Manifolds](https://link.springer.com/article/10.1007/s10208-005-0179-9) *Found. Comput. Math.* 2006.



## Zeroth-Order Optimization
> Derivative-free and zeroth-order optimization on manifolds

[Riemannian Accelerated Zeroth-order Algorithm: Improved Robustness and Lower Query Complexity](https://proceedings.mlr.press/v235/he24h.html) *ICML*. 2024.

[Zeroth-order Riemannian averaging stochastic approximation algorithms](https://epubs.siam.org/doi/full/10.1137/23M1605405?casa_token=GLUmnHCFPmcAAAAA%3AtqbK_tVkMUKRsj35eGERgQf4iTK04yGccBARgFVCjHFvBCFP6JKxCWOD-z9xRRnDGsV6SG9xbYCQ) *SIAM J. Optim.* 2024.

[Stochastic Zeroth-Order Riemannian Derivative Estimation and Optimization](https://pubsonline.informs.org/doi/abs/10.1287/moor.2022.1302?casa_token=-PpmKJFuuF8AAAAA:VDxcY2m0VIJtxaSoDuz5eN8FzXCnzTJ-19O5Cfjnr8YzFtoZKWRX_wXmeOos-WaGkXZM3trAIdyZLQ) *Math. Oper. Res.* 2022.



## Stochastic Optimization
> Methods for stochastic and finite-sum optimization on Riemannian manifolds

[Stochastic Modified Flows for Riemannian Stochastic Gradient Descent](https://arxiv.org/pdf/2402.03467) *Arxiv*. 2024.

[Stochastic approximation on riemannian manifolds](https://link.springer.com/article/10.1007/s00245-019-09581-2) *Appl. Math. Optim.* 2021.

[On Riemannian Stochastic Approximation Schemes with Fixed Step-Size](https://proceedings.mlr.press/v130/durmus21a/durmus21a.pdf) *AISTATS*. 2021.

[Averaging Stochastic Gradient Descent on Riemannian Manifolds](https://proceedings.mlr.press/v75/tripuraneni18a/tripuraneni18a.pdf) *COLT*. 2018.

[Stochastic gradient descent on Riemannian manifolds](https://ieeexplore.ieee.org/abstract/document/6487381) *IEEE Trans. Autom. Control.* 2013.

### Variance Reduction

[Streamlining in the Riemannian Realm: Efficient Riemannian Optimization with Loopless Variance Reduction](https://arxiv.org/pdf/2403.06677) *Arxiv*. 2024.

[Riemannian SVRG Using Barzilai–Borwein Method as Second-Order Approximation for Federated Learning](https://www.mdpi.com/2073-8994/16/9/1101) *Symmetry*. 2024.

[Improved Variance Reduction Methods for Riemannian Non-Convex Optimization](https://ieeexplore.ieee.org/document/9536452) *IEEE Trans. Pattern Anal. Mach. Intell.* 2022.

[Riemannian stochastic recursive momentum method for non-convex optimization](https://www.ijcai.org/proceedings/2021/0345.pdf) *IJCAI*. 2021.

[Faster First-Order Methods for Stochastic Non-Convex Optimization on Riemannian Manifolds](https://proceedings.mlr.press/v89/zhou19a/zhou19a.pdf) *AISTATS*. 2019. *IEEE Trans. Pattern Anal. Mach. Intell.* 2021.

[Escape saddle points faster on manifolds via perturbed riemannian stochastic recursive gradient](https://arxiv.org/pdf/2010.12191) *Arxiv*. 2020.

[Riemannian stochastic variance reduced gradient algorithm with retraction and vector transport](https://epubs.siam.org/doi/abs/10.1137/17M1116787) *SIAM J. Optim.* 2019.

[R-SPIDER: A fast Riemannian stochastic optimization algorithm with curvature independent rate](https://arxiv.org/pdf/1811.04194) *Arxiv*. 2018.

[Riemannian stochastic recursive gradient algorithm](https://proceedings.mlr.press/v80/kasai18a.html) *ICML*. 2018.

[MASAGA: A Linearly-Convergent Stochastic First-Order Method for Optimization on Manifolds](https://link.springer.com/chapter/10.1007/978-3-030-10928-8_21) *ECML*. 2018.

[Riemannian SVRG: Fast Stochastic Optimization on Riemannian Manifolds](https://proceedings.neurips.cc/paper_files/paper/2016/file/98e6f17209029f4ae6dc9d88ec8eac2c-Paper.pdf) *NeurIPS*. 2016.

### Adaptive Gradient

[A general framework of Riemannian adaptive optimization methods with a convergence analysis](https://arxiv.org/pdf/2409.00859) *Arxiv*. 2024.

[Riemannian Adaptive Optimization Algorithm and its Application to Natural Language Processing](https://ieeexplore.ieee.org/abstract/document/9339934) *IEEE Trans. Cybern.* 2022.

[Riemannian adaptive stochastic gradient algorithms on matrix manifolds](https://proceedings.mlr.press/v97/kasai19a/kasai19a.pdf) *ICML*. 2019.

[Riemannian Adaptive Optimization Methods](https://openreview.net/forum?id=r1eiqi09K7) *ICLR*. 2019.

## Geodesic Convex and Nonconvex Optimization
> Convergence theory, analysis and lower bound for geodesic convex and nonconvex optimization on Riemannian manifolds

[Geodesic Convexity of the Symmetric Eigenvalue Problem and Convergence of Steepest Descent](https://link.springer.com/article/10.1007/s10957-024-02538-8) *J. Optim. Theory Appl.* 2024.

[Curvature and complexity: Better lower bounds for geodesically convex optimization](https://proceedings.mlr.press/v195/criscitiello23a/criscitiello23a.pdf) *COLT*. 2023.

[Negative curvature obstructs acceleration for strongly geodesically convex optimization, even with exact first-order oracles](https://proceedings.mlr.press/v178/criscitiello22a/criscitiello22a.pdf) *COLT*. 2022.

[A No-go Theorem for Robust Acceleration in the Hyperbolic Plane](https://openreview.net/pdf?id=twz1QqzU0Hp) *NeurIPS*. 2021.

[Global rates of convergence for nonconvex optimization on manifolds](https://academic.oup.com/imajna/article/39/1/1/4836777) *IMA J. Numer. Anal.* 2019.

[Geodesic convex optimization: Differentiation on manifolds, geodesics, and convexity](https://arxiv.org/pdf/1806.06373) *Arxiv*. 2018.

[First-order Methods for Geodesically Convex Optimization](https://proceedings.mlr.press/v49/zhang16b.pdf) *COLT*. 2016.



## Nonsmooth Optimization
> Methods for solving nonsmooth optimization on manifolds

[On the Oracle Complexity of a Riemannian Inexact Augmented Lagrangian Method for Riemannian Nonsmooth Composite Problems](https://arxiv.org/pdf/2410.00482?) *Arxiv*. 2024.

[A Riemannian Proximal Newton-CG Method](https://arxiv.org/pdf/2405.08365) *Arxiv*. 2024.

[Nonsmooth nonconvex optimization on Riemannian manifolds via bundle trust region algorithm](https://link.springer.com/article/10.1007/s10589-024-00569-5) *Comput. Optim. Appl.* 2024.

[A Riemannian ADMM](https://arxiv.org/pdf/2211.02163) *Arxiv*. 2023.

[An inexact Riemannian proximal gradient method](https://link.springer.com/article/10.1007/s10589-023-00451-w) *Comput. Optim. Appl.* 2023.

[A manifold inexact augmented Lagrangian method for nonsmooth optimization on Riemannian submanifolds in Euclidean space](https://academic.oup.com/imajna/article/43/3/1653/6590238?login=true) *IMA J. Numer. Anal.* 2023.

[A proximal bundle algorithm for nonsmooth optimization on Riemannian manifolds](https://academic.oup.com/imajna/article/43/1/293/6454153?login=true) *IMA J. Numer. Anal.* 2023.

[Fenchel duality theory and a primal-dual algorithm on Riemannian manifolds](https://link.springer.com/article/10.1007/s10208-020-09486-5), *FoCM* 2021

[Riemannian proximal gradient methods](https://link.springer.com/article/10.1007/s10107-021-01632-3) *Math. Program.* 2022.

[Weakly Convex Optimization over Stiefel Manifold Using Riemannian Subgradient-Type Methods](https://epubs.siam.org/doi/abs/10.1137/20M1321000) *SIAM J. Optim.* 2021.

[A Collection of Nonsmooth Riemannian Optimization Problems](https://link.springer.com/chapter/10.1007/978-3-030-11370-4_1) *Nonsmooth Optim. Appl.* 2017

[A Riemannian Gradient Sampling Algorithm for Nonsmooth Optimization on Manifolds](https://epubs.siam.org/doi/abs/10.1137/16M1069298)  *SIAM J. Optim.* 2017.

[A parallel Douglas Rachford algorithm for minimizing ROF-like functionals on images with values in symmetric Hadamard manifolds](https://epubs.siam.org/doi/10.1137/15M1052858) *SIAM J. Imag. Sci* 2016

[Computing medians and means in Hadamard spaces](https://epubs.siam.org/doi/10.1137/140953393) *SIAM J. Optim.* 2014

[Proximal point algorithm on Riemannian manifolds](https://www.tandfonline.com/doi/abs/10.1080/02331930290019413) *Optimization' 2002

[Subgradient algorithm on Riemannian manifolds](https://link.springer.com/article/10.1023/A:1022675100677) *J. OPTIM. THEORY APPL.* 1998

## Constrained Optimization
> Methods for solving optimization problems on manifolds with constraints

[Structured Regularization for Constrained Optimization on the SPD Manifold](https://arxiv.org/pdf/2410.09660) *Arxiv*. 2024.

[Constraint Qualifications and Strong Global Convergence Properties of an Augmented Lagrangian Method on Riemannian Manifolds](https://epubs.siam.org/doi/full/10.1137/23M1582382?casa_token=x_-MW4p3aRQAAAAA%3Ae7JGmWcuZYdDpnSb-qr3odKUxCid5TySpZ_TPwMd03hPROjmLdy2yTNcrYApBHrwOXTnl2wOqjKK) *SIAM J. Optim.* 2024.

[Riemannian Interior Point Methods for Constrained Optimization on Manifolds](https://link.springer.com/article/10.1007/s10957-024-02403-8)  *J. Optim. Theory Appl.* 2024.

[Riemannian Projection-free Online Learning](https://proceedings.neurips.cc/paper_files/paper/2023/hash/8305a0049227f7dd2bb91e11090f8cfa-Abstract-Conference.html) *NeurIPS*. 2023.

[Riemannian Optimization via Frank-Wolfe Methods](https://link.springer.com/article/10.1007/s10107-022-01840-5) *Math. Program.* 2023.

[Interior-point methods on manifolds: theory and applications](https://ieeexplore.ieee.org/abstract/document/10353110?casa_token=_waujfZAdQgAAAAA:E5r0Eog9QD5aoZC5FwWLPM-PVrq5A7lgnSbTAJQKnG_lpsz1wcvN-R90A6vwy4GnZpHvtbx8csmE) *FOCS*. 2023.

[Projection-free nonconvex stochastic optimization on Riemannian manifolds](https://academic.oup.com/imajna/article/42/4/3241/6374894?login=true) *IMA J. Numer. Anal.* 2022.

[Intrinsic formulation of KKT conditions and constraint qualifications on smooth manifolds](https://epubs.siam.org/doi/10.1137/18M1181602) *SIAM J. Optim.* 2021

[Simple algorithms for optimization on Riemannian manifolds with constraints](https://link.springer.com/article/10.1007/s00245-019-09564-3) *Appl. Math. Optim.* 2020.



## Bilevel and Min-max Optimization
> Methods for solving bilevel and min-max optimization on manifolds

### Bilevel Optimization

[A framework for bilevel optimization on Riemannian manifolds](https://arxiv.org/pdf/2402.03883) *NeurIPS*. 2024.

[Riemannian Bilevel Optimization](https://arxiv.org/pdf/2405.15816) *Arxiv*. 2024.

[Riemannian Bilevel Optimization](https://arxiv.org/pdf/2402.02019) *Arxiv*. 2024.

[Semivectorial bilevel optimization on Riemannian manifolds](https://dl.acm.org/doi/abs/10.1007/s10957-015-0789-6) *J. Optim. Theory Appl.* 2015.

### Min-max Optimization

[A Riemannian Alternating Descent Ascent Algorithmic Framework for Nonconvex-Linear Minimax Problems on Riemannian Manifolds](https://arxiv.org/pdf/2409.19588) *Arxiv*. 2024.

[Local convergence of min-max algorithms to differentiable equilibrium on Riemannian manifold](https://arxiv.org/pdf/2405.13392) *Arxiv*. 2024.

[Extragradient Type Methods for Riemannian Variational Inequality Problems](https://proceedings.mlr.press/v238/hu24c/hu24c.pdf) *AISTATS*. 2024.

[Accelerated methods for riemannian min-max optimization ensuring bounded geometric penalties](https://arxiv.org/pdf/2305.16186) *Arxiv*. 2023.

[Nonconvex-nonconcave min-max optimization on Riemannian manifolds](https://openreview.net/forum?id=EDVIHPZhFo) *TMLR*. 2023.

[Riemannian optimistic algorithms](https://arxiv.org/pdf/2308.16004) *Arxiv*. 2023.

[Curvature-independent last-iterate convergence for games on riemannian manifolds](https://arxiv.org/pdf/2306.16617) *Arxiv*. 2023.

[Decentralized riemannian algorithm for nonconvex minimax problems](https://ojs.aaai.org/index.php/AAAI/article/view/26234) *AAAI*. 2023.

[Riemannian Hamiltonian methods for min-max optimization on manifolds](https://epubs.siam.org/doi/full/10.1137/22M1492684) *SIAM J. Optim.* 2023.

[Sion's minimax theorem in geodesic metric spaces and a Riemannian extragradient algorithm](https://epubs.siam.org/doi/full/10.1137/22M1505475) *SIAM J. Optim.* 2023.

[Gradient Descent Ascent for Minimax Problems on Riemannian Manifolds](https://ieeexplore.ieee.org/abstract/document/10005847)  *IEEE Trans. Pattern Anal. Mach. Intell.* 2023.

[First-Order Algorithms for Min-Max Optimization in Geodesic Metric Spaces](https://proceedings.neurips.cc/paper_files/paper/2022/file/2ad9a1a6ffac3dd72cc1df96019eca01-Paper-Conference.pdf) *NeurIPS*. 2022.


## Scalable Riemannian Optimization
> Tackling expensive retraction for scaling Riemannian optimization

### Stiefel (Orthogonal) Manifold

[Solving Optimization Problems over the Stiefel Manifold by Smooth Exact Penalty Functions](https://global-sci.org/intro/article_detail.html?journal=undefined&article_id=23277) *J. Comp. Math.* 2024.

[A Block Coordinate Descent Method for Nonsmooth Composite Optimization under Orthogonality Constraints](https://arxiv.org/pdf/2304.03641) *Arxiv*. 2023.

[Infeasible Deterministic, Stochastic, and Variance-Reduction Algorithms for Optimization under Orthogonality Constraints](https://arxiv.org/pdf/2303.16510) *Arxiv*. 2023.

[Fast and accurate optimization on the orthogonal manifold without retraction](https://proceedings.mlr.press/v151/ablin22a/ablin22a.pdf) *AISTATS*. 2022.

[A Class of Smooth Exact Penalty Function Methods for Optimization Problems with Orthogonality Constraints](https://www.tandfonline.com/doi/full/10.1080/10556788.2020.1852236) *Optim. Methods Softw.* 2020.

[Parallelizable algorithms for optimization problems with orthogonality constraints](https://epubs.siam.org/doi/10.1137/18M1221679) *SIAM J. Sci. Comput.* 2019.

[Coordinate-descent for learning orthogonal matrices through Givens rotations](https://proceedings.mlr.press/v32/shalit14.pdf) *ICML*. 2014.

### SPD Manifold

[Low-complexity subspace-descent over symmetric positive definite manifold](https://arxiv.org/pdf/2305.02041) *Arxiv*. 2023.

### General Manifold

[Riemannian Coordinate Descent Algorithms on Matrix Manifolds](https://proceedings.mlr.press/v235/han24c.html) *ICML*. 2024.

[Dissolving Constraints for Riemannian Optimization](https://dl.acm.org/doi/abs/10.1287/moor.2023.1360) *Math. Oper. Res.* 2023.

[Coordinate Descent Without Coordinates: Tangent Subspace Descent on Riemannian Manifolds](https://pubsonline.informs.org/doi/full/10.1287/moor.2022.1253?af=R) *Math. Oper. Res.* 2022.

[Trivializations for Gradient-Based Optimization on Manifolds](https://proceedings.neurips.cc/paper_files/paper/2019/file/1b33d16fc562464579b7199ca3114982-Paper.pdf) *NeurIPS*. 2019.

## Differentially Private Optimization
> Riemannian optimization that preserves privacy in data

[Differentially private Riemannian optimization](https://link.springer.com/article/10.1007/s10994-023-06508-5) *Mach. Learn.* 2024.

[Improved Differentially Private Riemannian Optimization: Fast Sampling and Variance Reduction](https://openreview.net/pdf?id=paguBNtqiO) *TMLR*. 2023.

# 3. Software

1. [ManOpt](https://github.com/NicolasBoumal/manopt): A Matlab toolbox for optimization on manifolds.
2. [Pymanopt](https://github.com/pymanopt/pymanopt): A Python toolbox for optimization on Riemannian manifolds with support for automatic differentiation.
3. [Manopt.jl](https://github.com/JuliaManifolds/Manopt.jl): A Julia toolbox for optimization on manifolds.
4. [ROPTLIB](https://github.com/whuang08/ROPTLIB): An object-oriented C++ library for optimization on Riemannian manifolds.
5. [McTorch](https://github.com/mctorch/mctorch): A manifold optimization library for deep learning with PyTorch.
6. [Geoopt](https://github.com/geoopt/geoopt): A manifold optimization and sampling toolbox with PyTorch.
7. [Rieoptax](https://github.com/SaitejaUtpala/rieoptax): A Riemannian optimization toolbox in jax.
