# A Handbook on Riemannian Optimization
This repo contains papers, books, tutorials and resources on Riemannian optimization. 

⚡ This repo is currently under-developed. ⚡

<details open>
  <summary><h2><b> Contents </b></h2></summary>

  * [1. Books](#books)
  * [2. Papers](#papers)
    * [Acceleration](#acceleration)
    * [Quasi-Newton Methods](#quasi-newton-methods)
    * [Second-Order Methods](#second-order-methods)
    * [Geodesic Convex and Nonconvex Optimization](#geodesic-convex-and-nonconvex-optimization)
    * [Stochastic Optimization](#stochastic-optimization)
      * [Variance Reduction](#variance-reduction)
      * [Adaptive Gradient](#adaptive-gradient)
    * [Bilevel and Min-Max Optimization](#bilevel-and-min-max-optimization)
    * [Scalable Riemannian Optimization](#scalable-riemannian-optimization)
      * [Stiefel (Orthogonal) Manifold](#stiefel-orthogonal-manifold)
      * [SPD Manifold](#spd-manifold)
      * [General Manifold](#general-manifold)
   * [3. Software](#software) 
</details>

# 📘 Books

1. <a href="https://press.princeton.edu/absil?srsltid=AfmBOorlfmgaTCzFeGcEDw9mxNrVvWMaKhY578kDlMOKlYY9D-G9ar3n" target="_blank">Optimization Algorithms on Matrix Manifolds</a> *Cambridge University Press*. 2023

2. <a href="https://www.nicolasboumal.net/book/" target="_blank">An introduction to Optimization on smooth manifolds</a> *Princeton University Press*. 2008.

# 📜 Papers

## Acceleration
> Accelerated gradient methods and analysis on Riemannian manifolds. 

<a href="https://arxiv.org/pdf/2312.06366" target="_blank">Accelerated Gradient Dynamics on Riemannian Manifolds: Faster Rate and Trajectory Convergence</a> *Arxiv*. 2023.

<a href="https://proceedings.mlr.press/v206/han23a/han23a.pdf" target="_blank">Riemannian accelerated gradient methods via extrapolation</a>  *AISTATS*. 2023.

<a href="https://proceedings.mlr.press/v195/martinez-rubio23a/martinez-rubio23a.pdf" target="_blank">Accelerated Riemannian Optimization: Handling Constraints with a Prox to Bound Geometric Penalties</a>  *COLT*. 2023.

<a href="https://link.springer.com/article/10.1007/s10208-022-09573-9" target="_blank">An Accelerated First-Order Method for Non-convex Optimization on Manifolds</a> *Found. Comput. Math.* 2022.

<a href="https://proceedings.mlr.press/v178/jin22a/jin22a.pdf" target="_blank">Understanding Riemannian acceleration via a proximal extragradient framework</a>  *COLT*. 2022.

<a href="https://epubs.siam.org/doi/abs/10.1137/21M1395648" target="_blank">A variational formulation of accelerated optimization on Riemannian manifolds</a>  *SIAM J. Math. Data Sci.* 2022.

<a href="https://proceedings.mlr.press/v167/martinez-rubio22a/martinez-rubio22a.pdf" target="_blank">Global Riemannian acceleration in hyperbolic and spherical spaces</a>  *ALT*. 2022.

<a href="https://proceedings.mlr.press/v162/kim22k/kim22k.pdf" target="_blank">Accelerated Gradient Methods for Geodesically Convex Optimization: Tractable Algorithms and Convergence Analysis</a>  *ICML*. 2022.

<a href="https://www.global-sci.org/intro/article_detail.html?journal=undefined&article_id=18372" target="_blank">Accelerated optimization with orthogonality constraints</a>  *J. Comp. Math.* 2021.

<a href="https://proceedings.mlr.press/v130/alimisis21a/alimisis21a.pdf" target="_blank">Momentum Improves Optimization on Riemannian Manifolds</a>  *AISTATS*. 2021.

<a href="https://proceedings.mlr.press/v125/ahn20a/ahn20a.pdf" target="_blank">From Nesterov’s Estimate Sequence to Riemannian Acceleration</a>  *COLT*. 2020. 

<a href="https://proceedings.mlr.press/v108/alimisis20a/alimisis20a.pdf" target="_blank">A continuous-time perspective for modeling acceleration in Riemannian optimization</a> *AISTATS*. 2020.

<a href="https://proceedings.neurips.cc/paper_files/paper/2017/file/6ef80bb237adf4b6f77d0700e1255907-Paper.pdf" target="_blank">Accelerated First-order Methods for Geodesically Convex Optimization on Riemannian Manifolds</a>  *NeurIPS*. 2017.

<a href="https://arxiv.org/pdf/1806.02812" target="_blank">Towards Riemannian accelerated gradient methods</a> *Arxiv*. 2018. 

## Quasi-Newton Methods
> Quasi-Newton methods on Riemannian manifolds.

[Generalization of Quasi-Newton methods: application to robust symmetric multisecant updates](https://proceedings.mlr.press/v130/scieur21a.html) *AISTATS*. 2021.

<a href="https://epubs.siam.org/doi/10.1137/140955483" target="_blank">A Broyden Class of Quasi-Newton Methods for Riemannian Optimization</a> *SIAM J. Optim.* 2015.


## Second-order Methods
> Second-order methods on Riemannian manifolds.


<a href="https://proceedings.neurips.cc/paper_files/paper/2018/file/3e9e39fed3b8369ed940f52cf300cf88-Paper.pdf" target="_blank">Inexact trust-region algorithms on Riemannian manifolds</a> *NeurIPS*. 2018.

[Riemannian Trust Regions with Finite-Difference Hessian Approximations are Globally Convergent](https://link.springer.com/chapter/10.1007/978-3-319-25040-3_50) *GSI*. 2015.


<a href="https://proceedings.neurips.cc/paper_files/paper/2011/file/37bc2f75bf1bcfe8450a1a41c200364c-Paper.pdf" target="_blank">RTRMC: A Riemannian trust-region method for low-rank matrix completion</a> *NeurIPS*. 2011.

<a href="https://link.springer.com/article/10.1007/s10208-005-0179-9" target="_blank">Trust-Region Methods on Riemannian Manifolds</a> *Found. Comput. Math.* 2006.


## Stochastic Optimization
> Methods for stochastic and finite-sum optimization on Riemannian manifolds

<a href="https://proceedings.mlr.press/v75/tripuraneni18a/tripuraneni18a.pdf" target="_blank">Averaging Stochastic Gradient Descent on Riemannian Manifolds</a> *COLT*. 2018.

<a href="https://ieeexplore.ieee.org/abstract/document/6487381" target="_blank">Stochastic gradient descent on Riemannian manifolds</a> *IEEE Trans. Autom. Control.* 2013.


### Variance Reduction

<a href="https://proceedings.neurips.cc/paper_files/paper/2016/file/98e6f17209029f4ae6dc9d88ec8eac2c-Paper.pdf" target="_blank">Riemannian SVRG: Fast Stochastic Optimization on Riemannian Manifolds</a> *NeurIPS*. 2016.

### Adaptive Gradient


## Geodesic Convex and Nonconvex Optimization
> Convergence theory, analysis and lower bound for geodesic convex and nonconvex optimization on Riemannian manifolds

<a href="https://proceedings.mlr.press/v195/criscitiello23a/criscitiello23a.pdf" target="_blank">Curvature and complexity: Better lower bounds for geodesically convex optimization</a> *COLT*. 2023.

<a href="https://proceedings.mlr.press/v178/criscitiello22a/criscitiello22a.pdf" target="_blank">Negative curvature obstructs acceleration for strongly geodesically convex optimization, even with exact first-order oracles</a> *COLT*. 2022.

<a href="https://openreview.net/pdf?id=twz1QqzU0Hp" target="_blank">A No-go Theorem for Robust Acceleration in the Hyperbolic Plane</a> *NeurIPS*. 2021.

<a href="https://academic.oup.com/imajna/article/39/1/1/4836777" target="_blank">Global rates of convergence for nonconvex optimization on manifolds</a> *IMA J. Numer. Anal.* 2019.

<a href="https://arxiv.org/pdf/1806.06373" target="_blank">Geodesic convex optimization: Differentiation on manifolds, geodesics, and convexity</a> *Arxiv*. 2018.

<a href="https://proceedings.mlr.press/v49/zhang16b.pdf" target="_blank">First-order Methods for Geodesically Convex Optimization</a> *COLT*. 2016.


## Bilevel and Min-max Optimization
> Methods for solving bilevel and min-max optimization on manifolds


## Scalable Riemannian Optimization
> Tackling expensive retraction for scaling Riemannian optimization

### Stiefel (Orthogonal) Manifold

<a href="https://global-sci.org/intro/article_detail.html?journal=undefined&article_id=23277" target="_blank">Solving Optimization Problems over the Stiefel Manifold by Smooth Exact Penalty Functions</a> *J. Comp. Math.* 2024.

<a href="https://arxiv.org/pdf/2304.03641" target="_blank">A Block Coordinate Descent Method for Nonsmooth Composite Optimization under Orthogonality Constraints</a> *Arxiv*. 2023.

<a href="https://arxiv.org/pdf/2303.16510" target="_blank">Infeasible Deterministic, Stochastic, and Variance-Reduction Algorithms for Optimization under Orthogonality Constraints</a> *Arxiv*. 2023.

<a href="https://proceedings.mlr.press/v151/ablin22a/ablin22a.pdf" target="_blank">Fast and accurate optimization on the orthogonal manifold without retraction</a> *AISTATS*. 2022.

<a href="https://www.tandfonline.com/doi/full/10.1080/10556788.2020.1852236" target="_blank">A Class of Smooth Exact Penalty Function Methods for Optimization Problems with Orthogonality Constraints</a> *Optim. Methods Softw.* 2020.

<a href="https://epubs.siam.org/doi/10.1137/18M1221679" target="_blank">Parallelizable algorithms for optimization problems with orthogonality constraints</a> *SIAM J. Sci. Comput.* 2019.

<a href="https://proceedings.mlr.press/v32/shalit14.pdf" target="_blank">Coordinate-descent for learning orthogonal matrices through Givens rotations</a> *ICML*. 2014.

### SPD Manifold

<a href="https://arxiv.org/pdf/2305.02041" target="_blank">Low-complexity subspace-descent over symmetric positive definite manifold</a> *Arxiv*. 2023.

### General Manifold

<a href="https://proceedings.mlr.press/v235/han24c.html" target="_blank">Riemannian Coordinate Descent Algorithms on Matrix Manifolds</a> *ICML*. 2024.

<a href="https://dl.acm.org/doi/abs/10.1287/moor.2023.1360" target="_blank">Dissolving Constraints for Riemannian Optimization</a> *Math. Oper. Res.* 2023.

<a href="https://pubsonline.informs.org/doi/full/10.1287/moor.2022.1253?af=R" target="_blank">Coordinate Descent Without Coordinates: Tangent Subspace Descent on Riemannian Manifolds</a> *Math. Oper. Res.* 2022.

<a href="https://proceedings.neurips.cc/paper_files/paper/2019/file/1b33d16fc562464579b7199ca3114982-Paper.pdf" target="_blank">Trivializations for Gradient-Based Optimization on Manifolds</a> *NeurIPS*. 2019.


# 🖥️ Software

1. <a href="https://github.com/NicolasBoumal/manopt" target="_blank">ManOpt</a>: A Matlab toolbox for optimization on manifolds.
2. <a href="https://github.com/pymanopt/pymanopt" target="_blank">Pymanopt</a>: A Python toolbox for optimization on Riemannian manifolds with support for automatic differentiation
3. <a href="https://github.com/JuliaManifolds/Manopt.jl" target="_blank">Manopt.jl</a>: A Julia toolbox for optimization on manifolds.
4. <a href="https://github.com/whuang08/ROPTLIB" target="_blank">ROPTLIB</a>: An object-oriented C++ library for optimization on Riemannian manifolds.
5. <a href="https://github.com/mctorch/mctorch" target="_blank">McTorch</a>: A manifold optimization library for deep learning with PyTorch.
6. <a href="https://github.com/geoopt/geoopt" target="_blank">Geoopt</a>: A manifold optimization and sampling toolbox with Pytorch.
