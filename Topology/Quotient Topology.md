#definition
### Types
- `X` : [[Topological Space]]
- `Y` : Set
- $q : X \to Y$
### Definition
If `q` is surjective, we define the *quotient topology* induced by `q` on `Y` as the [[topology]] with $U \subset Y$ [[Open Set|open]] if and only if $q^{-1}\left( U \right)$ is [[open set|open]] in `X`.
#### Proof that it is a [[Topology]]
- $q^{-1}\left( Y \right) = X$ since `q` is surjective, and `X` is [[open set|open]], so `Y` is [[open set|open]]. Trivially, $\varnothing$ is [[open set|open]] because $q^{-1}\left( \varnothing \right) = \varnothing$.
- Let `U` and `V` be [[open set|open]] in `Y`, then $q^{-1}\left( U\cap V \right) = q^{-1} \left( U \right) \cap q^{-1}\left( V \right)$ which is the intersection of [[open set|open]] sets and thus is [[open set|open]].
- Let `I` be a set and $\left\{ U_{i} \right\}_{i\in I}$ be a family of [[open set]]s in `Y`, then $q^{-1}\left( \bigcup\limits_{i\in I} U_{i}\right)=\bigcup\limits_{i\in I}q^{-1}\left( U_{i} \right)$ which is [[Open Set|open]].