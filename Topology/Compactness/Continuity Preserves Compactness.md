#theorem
### Types
- `X` `Y` : [[Topological Space]]
- $f : X \to Y$
### Statement
If $f$ is [[Topology/Continuity/Continuity|continuous]], and $X$ is [[compact Space|compact]], then $f\left( X \right)$ is [[compact Space|compact]].
### Proof
Let $\left\{ U_{i} \right\}_{i\in I}$ be a [[covering]] of $f(X)$, then $X = f^{-1}\left(\bigcup\limits_{{i\in I}} U_{i} \right) = \bigcup\limits_{i \in I} f^{-1}\left( U_{i} \right)$, which means that $\left\{f^{-1}\left(U_{i}  \right)\right\}_{i\in I}$ is a [[covering]] of $X$, as $f$ is continuous making the elements of the [[covering]] [[open set|open]]. 
Since $X$ is a [[Compact Space|compact]], there exists a finite subcover of $\left\{ f\left( U_{i}\right) \right\}_{i\in I}$ that covers $X$,  so we have $\bigcup\limits_{{i\in\mathbb{N}}}f^{-1}\left(V_{i}\right) = X$, and thus $\left\{ V_{i} \right\}_{i\in\mathbb{N}}$ is a finite cover of $f(X)$.