#lemma
### Types
- `X` `Y` : [[Topological Space]]
- $f : X \to Y$
### Statement
If $f$ is [[Continuity|continuous]], then its restriction to any [[open set]] is also [[Continuity|continuous]]. 
### Proof
Let `O` be an [[Open Set|open]] subset of `X` and `U` an [[Open Set|open]] subset of `Y`, we have:
$$
\begin{aligned}
f|_O^{-1}\left( U \right) &= \left\{ x \in O | f\left( x \right) \in U  \right\}\\
&= O \cap f^{-1}\left( U \right) 
\end{aligned}
$$
$f^{-1}\left( U \right)$ is [[Open Set|open]] because $f$ is [[Continuity|continuous]]. So $f|_O^{-1}\left( U \right)$ is the intersection of two [[open set]]s, which is [[open set|open]] according to the axiom of stability of finite intersections in a [[topology]]. Therefore $f|_O$ is [[Continuity|continuous]].