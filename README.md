# A Handbook on Riemannian Optimization
This repo contains papers, books, tutorials and resources on Riemannian optimization. 

⚡ This repo is currently under-developed. Any suggestions are welcome!⚡

   
<details open>
  <summary><h2><b> Contents </b></h2></summary>

  * [1. Books](#1-books)
  * [2. Papers](#2-papers)
    * [Acceleration](#acceleration)
    * [Quasi-Newton Methods](#quasi-newton-methods)
    * [Second-Order Methods](#second-order-methods)
    * [Geodesic Convex and Nonconvex Optimization](#geodesic-convex-and-nonconvex-optimization)
    * [Stochastic Optimization](#stochastic-optimization)
      * [Variance Reduction](#variance-reduction)
      * [Adaptive Gradient](#adaptive-gradient)
    * [Bilevel and Min-Max Optimization](#bilevel-and-min-max-optimization)
      * [Bilevel Optimization](#bilevel-optimization)
      * [Min-max Optimization](#min-max-optimization)
    * [Scalable Riemannian Optimization](#scalable-riemannian-optimization)
      * [Stiefel (Orthogonal) Manifold](#stiefel-orthogonal-manifold)
      * [SPD Manifold](#spd-manifold)
      * [General Manifold](#general-manifold)
   * [3. Software](#3-software) 
</details>

# 1. Books

1. [Optimization Algorithms on Matrix Manifolds](https://press.princeton.edu/absil?srsltid=AfmBOorlfmgaTCzFeGcEDw9mxNrVvWMaKhY578kDlMOKlYY9D-G9ar3n) *Cambridge University Press*. 2023

2. [An introduction to Optimization on smooth manifolds](https://www.nicolasboumal.net/book/) *Princeton University Press*. 2008.

# 2. Papers

## Acceleration
> Accelerated gradient methods and analysis on Riemannian manifolds. 

[Accelerated Gradient Dynamics on Riemannian Manifolds: Faster Rate and Trajectory Convergence](https://arxiv.org/pdf/2312.06366) *Arxiv*. 2023.

[Riemannian accelerated gradient methods via extrapolation](https://proceedings.mlr.press/v206/han23a/han23a.pdf) *AISTATS*. 2023.

[Accelerated Riemannian Optimization: Handling Constraints with a Prox to Bound Geometric Penalties](https://proceedings.mlr.press/v195/martinez-rubio23a/martinez-rubio23a.pdf) *COLT*. 2023.

[An Accelerated First-Order Method for Non-convex Optimization on Manifolds](https://link.springer.com/article/10.1007/s10208-022-09573-9) *Found. Comput. Math.* 2022.

[Understanding Riemannian acceleration via a proximal extragradient framework](https://proceedings.mlr.press/v178/jin22a/jin22a.pdf) *COLT*. 2022.

[A variational formulation of accelerated optimization on Riemannian manifolds](https://epubs.siam.org/doi/abs/10.1137/21M1395648) *SIAM J. Math. Data Sci.* 2022.

[Global Riemannian acceleration in hyperbolic and spherical spaces](https://proceedings.mlr.press/v167/martinez-rubio22a/martinez-rubio22a.pdf) *ALT*. 2022.

[Accelerated Gradient Methods for Geodesically Convex Optimization: Tractable Algorithms and Convergence Analysis](https://proceedings.mlr.press/v162/kim22k/kim22k.pdf) *ICML*. 2022.

[Accelerated optimization with orthogonality constraints](https://www.global-sci.org/intro/article_detail.html?journal=undefined&article_id=18372) *J. Comp. Math.* 2021.

[Momentum Improves Optimization on Riemannian Manifolds](https://proceedings.mlr.press/v130/alimisis21a/alimisis21a.pdf) *AISTATS*. 2021.

[From Nesterov’s Estimate Sequence to Riemannian Acceleration](https://proceedings.mlr.press/v125/ahn20a/ahn20a.pdf) *COLT*. 2020. 

[A continuous-time perspective for modeling acceleration in Riemannian optimization](https://proceedings.mlr.press/v108/alimisis20a/alimisis20a.pdf) *AISTATS*. 2020.

[Accelerated First-order Methods for Geodesically Convex Optimization on Riemannian Manifolds](https://proceedings.neurips.cc/paper_files/paper/2017/file/6ef80bb237adf4b6f77d0700e1255907-Paper.pdf) *NeurIPS*. 2017.

[Towards Riemannian accelerated gradient methods](https://arxiv.org/pdf/1806.02812) *Arxiv*. 2018.


## Quasi-Newton Methods
> Quasi-Newton methods on Riemannian manifolds.

[Generalization of Quasi-Newton methods: application to robust symmetric multisecant updates](https://proceedings.mlr.press/v130/scieur21a.html) *AISTATS*. 2021.

[Riemannian stochastic quasi-Newton algorithm with variance reduction and its convergence analysis](https://proceedings.mlr.press/v84/kasai18a/kasai18a.pdf) *AISTATS*. 2018.


[A Broyden Class of Quasi-Newton Methods for Riemannian Optimization](https://epubs.siam.org/doi/10.1137/140955483) *SIAM J. Optim.* 2015.

## Second-order Methods
> Second-order methods on Riemannian manifolds.

[Faster Riemannian Newton-type optimization by subsampling and cubic regularization](https://link.springer.com/article/10.1007/s10994-023-06321-0). *Mach. Learn.* 2023.

[Adaptive regularization with cubics on manifolds](https://link.springer.com/article/10.1007/s10107-020-01505-1) *Math. Program.* 2021.

[Inexact trust-region algorithms on Riemannian manifolds](https://proceedings.neurips.cc/paper_files/paper/2018/file/3e9e39fed3b8369ed940f52cf300cf88-Paper.pdf) *NeurIPS*. 2018.

[Low-rank matrix completion via preconditioned optimization on the Grassmann manifold](https://www.sciencedirect.com/science/article/pii/S0024379515001342) *Linear Algebra Its Appl.* 2015.

[Riemannian Trust Regions with Finite-Difference Hessian Approximations are Globally Convergent](https://link.springer.com/chapter/10.1007/978-3-319-25040-3_50) *GSI*. 2015.

[RTRMC: A Riemannian trust-region method for low-rank matrix completion](https://proceedings.neurips.cc/paper_files/paper/2011/file/37bc2f75bf1bcfe8450a1a41c200364c-Paper.pdf) *NeurIPS*. 2011.

[Trust-Region Methods on Riemannian Manifolds](https://link.springer.com/article/10.1007/s10208-005-0179-9) *Found. Comput. Math.* 2006.

## Stochastic Optimization
> Methods for stochastic and finite-sum optimization on Riemannian manifolds

[Stochastic Modified Flows for Riemannian Stochastic Gradient Descent](https://arxiv.org/pdf/2402.03467) *Arxiv*. 2024.

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

## Bilevel and Min-max Optimization
> Methods for solving bilevel and min-max optimization on manifolds

### Bilevel Optimization


### Min-max Optimization

[Sion's minimax theorem in geodesic metric spaces and a Riemannian extragradient algorithm](https://epubs.siam.org/doi/full/10.1137/22M1505475) *SIAM J. Optim.* 2023.

[Extragradient Type Methods for Riemannian Variational Inequality Problems](https://proceedings.mlr.press/v238/hu24c/hu24c.pdf) *AISTATS*. 2024.

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

# 3. Software

1. [ManOpt](https://github.com/NicolasBoumal/manopt): A Matlab toolbox for optimization on manifolds.
2. [Pymanopt](https://github.com/pymanopt/pymanopt): A Python toolbox for optimization on Riemannian manifolds with support for automatic differentiation.
3. [Manopt.jl](https://github.com/JuliaManifolds/Manopt.jl): A Julia toolbox for optimization on manifolds.
4. [ROPTLIB](https://github.com/whuang08/ROPTLIB): An object-oriented C++ library for optimization on Riemannian manifolds.
5. [McTorch](https://github.com/mctorch/mctorch): A manifold optimization library for deep learning with PyTorch.
6. [Geoopt](https://github.com/geoopt/geoopt): A manifold optimization and sampling toolbox with PyTorch.
