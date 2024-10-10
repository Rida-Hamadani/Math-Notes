#lemma
### Types
- `X` : [[Hausdorff Space]]
- `A` `B` : Subset of `X`
### Statement
If `A` and `B` are disjoined, and their [[subspace topology]] is [[Compact Space|compact]], then there exists disjoint [[open set]]s `U` and `V` such that $A \subset U$ and $B \subset V$.
### Proof
First, let's prove for when `B` is a singleton. Let $B = \left\{ q \right\}$, then by the [[Hausdorff Space|separation]] property, for every $p \in A$ we have disjoint [[open set]]s of `X`, $U_{p}$ and $V_{q}$ such that $p\in U_{p}$ and $q \in V_{q}.$ $\left\{ U_{p} \right\}_{p\in A}$ is a [[Covering of a Subset|covering]] of `A` in `X`, and as `A` is [[Compact Space|compact]], by [[Subspace Compactness Criterion]], there exists a finite sub[[Covering of a Subset|cover]] of `A` in `X`, denote it by $\left\{ U_{p_{1}}, U_{p_{2}}, \cdots, U_{p_{n}}\right\}$ where $p_{k}\in A$, then $A \subset U=\bigcup\limits_{k=1}^nU_{p_{k}}$ and $\left\{ q \right\}=B\subset\bigcap \limits_{k=1}^nV_{p_{k}}$. Both `U` and and `V` are [[open set|open]], and they are disjoint because each element $p$ in $U$ is not contained in some $V_{p}$, so it is not contained in the intersection $V$.

Now let's consider the case where $B$ is any [[compact space|compact]] subset of `X` that is disjoint from `A`. According to the previous case, for every $q \in B$, there exists disjoint [[Open Set|open]] $\mathcal{U}_{q}, \mathcal{V}_{q}$ subsets of `X` such that $A\subset \mathcal{U}_{q}$ and $q \in \mathcal{V}_{q}$. Then $\left\{\mathcal{V}_{q}\right\}_{q\in B}$ [[Covering of a Subset|covers]] $B$, which is [[Compact Space|compact]], so by [[Subspace Compactness Criterion]], there exists a finite sub[[Covering of a Subset|covering]] of $B$ in `X`, namely $\left\{  \mathcal{V}_{p_{1}}, \mathcal{V}_{p_{2}}, \cdots\mathcal{V}_{p_{n}}\right\}$. Note that each of the $\mathcal{V}_{p_{k}}$ with have an associated disjoint $\mathcal{U_{p_{k}}}$, so taking:
$$
U=\bigcup\limits_{k=1}^n\mathcal{U}_{p_{k}} \text{  and  } V=\bigcap\limits_{k=1}^n\mathcal{V}_{p_{k}}
$$
completes the proof.