#exercise 
### Question
Prove that the [[projective space]] over $\mathbb{R}^{n+1}$ is a [[smooth manifold]].
### Answer
Let $\pi : \mathbb{R}^{n+1} - \left\{ 0 \right\} \to \mathbb{P}\left( \mathbb{R}^{n+1} \right)$ defined as $\pi\left( x \right) = \left[ x \right]= span\left( x \right)$, note that $\pi \left( \lambda x \right) = \pi \left( x \right)$ for any $\lambda \in \mathbb{R} - \left\{ 0 \right\}$. The $\pi$ map is [[Topology/Continuity/Continuity|continuous]] ( #todo in topology). Let's define our [[chart]]s as $\left( V_{i}, \varphi_{i} \right)$, $i \in \left\{ 1, 2, \cdots, n+1 \right\}$ as: 
$$
\begin{aligned}
V_{i} &= \left\{ l \in \mathbb{P}\left( \mathbb{R}^{n +1} \right) \right\} \text{ such that } l \text{ is not in the } x_{i} \text{hyperplane}\\
&= \left\{ 
\pi \left(x_{1},x_{2},\cdots, x_{i-1}, 1, x_{i+1},\cdots, x_{n+1}\right), x_{j} \in \mathbb{R}
\right\}\\ 
\varphi_{i} &= \left(\frac{x_{1}}{x_{i}},\frac{x_{2}}{x_{i}},\cdots, \frac{x_{i-1}}{x_{i}}, \frac{x_{i+1}}{x_{i}},\cdots, \frac{x_{n+1}}{x_{i}}\right) \\
\varphi_{i}^{-1}(u) &=\left(u_{1}, u_{2}, \cdots,u_{{i-1}},1,u_{i+1},\cdots,u_{n+1}\right)
\end{aligned}
$$
Note that for $u \in \varphi_{i}^{-1} \left( V_{i}\cap V_{j} \right)$ or $\varphi_{j}^{-1} \left( V_{i}\cap V_{j} \right)$, $u_{i}$ and $u_{j}$ are nonzero respectively. We have the [[transition map]]s:
$$
\begin{aligned}
\left(\varphi_{i} \circ \varphi_{j}^{-1} \right)(u) &= \left(\frac{u_{1}}{u_{i}},\frac{u_{2}}{u_{i}},\cdots, \frac{u_{j-1}}{u_{i}}, \frac{1}{u_{i}},\frac{u_{j+1}}{u_{i}},\cdots, \frac{u_{n+1}}{u_{i}}\right) \\
\left(\varphi_{j} \circ \varphi_{i}^{-1} \right)(u) &= \left(\frac{u_{1}}{u_{j}},\frac{u_{2}}{u_{j}},\cdots, \frac{u_{i-1}}{u_{j}}, \frac{1}{u_{j}},\frac{u_{i+1}}{u_{j}},\cdots, \frac{u_{n+1}}{u_{j}}\right) 
\end{aligned}
$$
Which are smooth on the domains, thus $\mathbb{P}\left( \mathbb{R}^{n+1}  \right)$ is a [[smooth manifold].]
##### Source
Problem 1.81 - Analysis and Algebra on Differentiable Manifolds by Gadea et al
