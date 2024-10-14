#lemma
### Types
- `X` : [[Hausdorff Space]]
- `A` : Subset of `X`
- $\tau$ : [[Subspace Topology]] of `A` in `X`
- $\left( A,\tau \right)$ : [[Compact Space]]
### Statement
`A` is [[Closed Set|closed]] in `X`.
### Proof
We will prove that for every $a \in X-A$, there exists an [[open set]] $U$ such that $a \in U \subset X-A$.
Let $a \in X-A$, for every $x \in A$, there exists disjoint $U_{x}, V_{x}\subset X$ such that $a\in U_{x}$ and $x\in V_{x}$.
$\left\{ V_{x} \right\}_{x\in A}$ is a [[Covering of a Subset|covering]] of `A` in `X`, thus by using [[Subspace Compactness Criterion]], there exists a finite set of elements of $A$, name it $I$, such that $\left\{ V_{x} \right\}_{x\in I}$ is a finite [[Covering of a Subset|covering]] of `A` in `X`.
We have $U=\bigcap\limits_{x\in I}U_{x}$ is open in $X-A$ since it is the intersection of finite [[open set]]s. Moreover, $a\in U$ as it is in every $U_{x}$. Suppose $y \in U$, then $\exists i \in I, y \in U_{i}$, but $A \subset \bigcup\limits_{x\in I}V_{x}$, and as we have $y\notin V_{i}$, it cannot be in a union containing $V_{i}$, so $y\not\in A$. Hence $U\cap A=\varnothing$. Therefore $U\subset X- A$.