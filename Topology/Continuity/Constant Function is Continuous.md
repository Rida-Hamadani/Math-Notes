#lemma
### Types
- `X` `Y` : [[Topological Space]]
- $f : X \to Y$
- `c` : `Y`
### Statement
If $f$ is constant, i.e. $\forall x \in X, f\left( x \right) = c$, then it is [[Continuity|continuous]].
### Proof
Let `U` be an open subset of `Y`, if $c \in U$, then $f^{-1}\left( U\right) = X$ which is [[Open Set|open]] in `X`, else if $c \notin U$, then $f^{-1}\left( U\right) = \varnothing$, which is also [[Open Set|open]] in `X`. Thus in all cases, $f^{-1}\left( U \right)$ is [[Open Set|open]] in `X` and $f$ is [[Continuity|continuous]].