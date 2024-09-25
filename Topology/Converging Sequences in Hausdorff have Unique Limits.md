#lemma
### Types
- `X` : [[Hausdorff Space]]
### Statement
If a sequence [[convergence|converges]] in `X` to a limit, that limit is unique.
### Proof
Suppose that $\left\{ x_{i} \right\}_{i\in\mathbb{N}}$ converges to $l_{1}$ and $l_{2}$ with $l_{1}\ne l_{2}$ in `X`, then since `X` is a [[Hausdorff space]], there exists [[neighborhood]]s $U_{1}$ and $U_{2}$ of $l_1$ and $l_2$ respectively such that $U_{1} \cap U_{2} = \varnothing$. By definition of [[convergence]]:
$$
\begin{aligned}
\exists n_{1} \in \mathbb{N}: \forall i\ge n_{1}&:x_{i} \in U_{1} \\
\exists n_{2} \in \mathbb{N}: \forall i\ge n_{2}&:x_{i} \in U_{2}
\end{aligned}
$$
Take $n = \max\left( n_{1}, n_{2} \right)$, then $\forall i\ge n$, we have $x_{i} \in U_{1}$ and $x_{i} \in U_{2}$, thus $x_i \in U_1 \cap U_2 = \varnothing$, which is absurd.