#definition
### Types
- `X` : Nonempty [[Topological Space]]
### Definition
A *cell decomposition* of `X` is a [[partition]] $\mathcal{E}$ of `X` into subspaces that are [[Open n-Cell|open cells]] of different dimensions, satisfying the following condition:
For each cell $e \in \mathcal{E}$ of dimension $n \ge 1$, there exists a [[continuity|continuous]] map $\Phi$ from some [[Closed n-Cell]] `D` into `X` (called the *characteristic map* for $e$) that restricts to a [[homeomorphism]] from $\text{Int} D$ onto $e$ and maps $\partial D$ into the union of all [[Closed n-Cell|cells]] of $\mathcal{E}$ with dimension less than $n$.