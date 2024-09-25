#exercise
### Question
Prove that $S^n=\left\lbrace x\in \mathbb{R}^{n+1}, \left|\left| x\right|\right|_2=1\right\rbrace$ is a [[smooth manifold]] on $\mathbb{R}^n$.
### Answer
Let:
$$
 \begin{aligned}
U_S &= \left\lbrace x \in S^n, x_{n+1} \neq 1\right\rbrace \\
U_N &= \left\lbrace x \in S^n, x_{n+1} \neq -1\right\rbrace \\
\varphi_S &: U_S \to \mathbb{R}^n \\
\varphi_S\left(x\right) &= \frac{1}{1-x_{n+1}}\cdot x \\
\varphi_N &: U_N \to \mathbb{R}^n \\
\varphi_N\left(x\right) &= \frac{1}{1+x_{n+1}}\cdot x \\
\end{aligned}
$$
Without lost of generalization, we will look at the [[transition map]] $\varphi_S \circ\varphi^{-1}_N$. We have $\varphi_N^{-1} : \varphi_N\left(U_N\right) \subset \mathbb{R}^n\to S^n \subset \mathbb{R}^{n+1}$:
$$
\varphi_N^{-1}(y) = \frac{1}{1+\left|\left| y\right|\right|_2}\left(2y_1,2y_2,\cdots,2y_n, \left|\left| y\right|\right|_2 - 1\right)
$$
We get $\varphi_S \circ\varphi^{-1}_N : \varphi_N\left(U_N\cap U_S\right) = \mathbb{R}^n - \lbrace 0 \rbrace \to \varphi_S\left(U_N\cap U_S\right)$: 
$$
\varphi_S \circ\varphi^{-1}_N\left(y\right) = \frac{y}{\left|\left| y\right|\right|_2}
$$
Which is $C^\infty$ over $\mathbb{R}^n - \lbrace0\rbrace$.

![[Stereographic  Projection.png]]
##### Source
Problem 1.28 - Analysis and Algebra on Differentiable Manifolds by Gadea et al
