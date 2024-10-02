#lemma
### Types
- `X` `Y` `X` : [[Topological Space]]
- $f : X \to Y$
- $g : Y \to Z$
### Statement
If $f$ and $g$ are [[Topology/Continuity/Continuity|continuous]], then their composition $g \circ f : X \to Z$ is also [[Topology/Continuity/Continuity|continuous]]. 
### Proof
Let `U` be an [[Open Set|open]] subset of `Z`, we have:
$$
\begin{aligned}
\left(g \circ f\right) ^{-1}\left( U \right) &= f^{-1}\left( g^{-1} \left( U \right)   \right)   
\end{aligned}
$$
As $g$ is [[Topology/Continuity/Continuity|continuous]], and `U` is [[Open Set|open]], then $g^{-1}\left( U \right)$ is open, and $f$ is also [[Topology/Continuity/Continuity|continuous]], then $f^{-1}\left( g^{-1} \left( U \right)   \right)$ is also [[Open Set|open]]. Therefore $g \circ f$ is [[Topology/Continuity/Continuity|continuous]]. 