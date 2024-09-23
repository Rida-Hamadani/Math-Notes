#definition
### Types
- `X` : Nonempty Set
### Definition
A *sigma algebra* $\mathcal{A}$ on a set `X` is a family of subsets of `X` satisfying the following conditions:
- `X` $\in \mathcal{A}$.
- $A \in \mathcal{A} \implies \overline{A} \in \mathcal{A}$.
- $(A_j)_{j\in\mathbb{N}} \subset \mathcal{A}\implies \bigcup\limits_{j\in\mathbb{N}}A_j\in\mathcal{A}$.
##### Notes
- Since $\mathcal{A}$ is closed under compliment, we have by the first condition $\varnothing \in \mathcal{A}$.
- Similarly, we have $(A_j)_{j\in\mathbb{N}} \subset \mathcal{A}\implies \bigcap\limits_{j\in\mathbb{N}}A_j\in\mathcal{A}$.
##### aka
- Sigma Field
- $\sigma$-Algebra
- $\sigma$-Field