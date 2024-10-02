#theorem
### Types
- `X` `Y` : [[Topological Space]]
- $f : X \to Y$
### Statement
If $f$ is [[Topology/Continuity/Continuity|continuous]], and $X$ is [[Connected Space|connected]], then $f\left( X \right)$ is [[Connected Space|connected]].
### Proof
We will prove the contrapositive. Supposed $f\left( X \right)$ is [[Disconnected Space|disconnected]], then $f(X) = U \cup  V$ where $U$ and $V$ are disjoint, non-empty, [[closed set|closed]] and [[open set|open]]. Then by the [[Topology/Continuity/Continuity]] of $f$, $f^{-1}\left( U \right)$ and $f^{-1}\left( U \right)$  are [[closed set|closed]] and [[open set|open]], and nonempty. Moreover, as the complement of the preimage is equal to the preimage of the complement, then their union is $X$, thus $X$ is [[Disconnected Space|disconnected]].