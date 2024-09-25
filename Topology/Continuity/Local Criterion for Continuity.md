#theorem
### Types
- `X` `Y` : [[Topological Space]]
- $f : X \to Y$
### Statement
$f$ is [[Continuity|continuous]] if and only if each point in `X` has a [[neighborhood]] such that $f$'s restricted to is [[Continuity|continuity]].  
### Proof
If $f$ is continuous, then we know that $f$ restricted to all [[neighborhood]]s of any point in `X` is [[Continuity|continuous]] due to [[Restriction of Continuous to Open Set is Continuous]].
Conversely, assume that $f$'s restriction to a neighborhood of each point in `X` is [[continuity|continuous]], and let `U` be [[open set |open]] in `Y`. Let $x \in f^{-1}\left( U \right)$, then `x` has a [[neighborhood]] $V_{x}$ such that $f|_{V_{x}}$ is continuous over $V_{x}$, which means that $f|_{V_{x}}^{-1}(U)$ is an [[Open Set|open]] subset of $V_{x}$, and thus an [[Open Set|open]] subset of `X`. We have $U = \bigcup\limits_{x\in U}V_{x}$, which is the union of [[open set]]s in `X`, and thus is [[Open Set|open]] in `X` by the stability of arbitrary unions axiom of a [[topology]].