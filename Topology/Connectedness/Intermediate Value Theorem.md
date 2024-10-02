#theorem
### Types
- `X` : [[Connected Space]]
- $f : X \to \mathbb{R}$
- `p` `q` : `X`
### Statement
if $f$ is [[Topology/Continuity/Continuity|continuous]], it attains all the values between $f\left( p \right)$ and $f\left( q \right)$.
### Proof
We begin by proving that every connected subset of $\mathbb{R}$ is either a subset or an interval. Let $J \subset \mathbb{R}$ such that J is not an interval, then there exists $a < c < b$ such that $a, b \in J$ but $c \notin J$.  $\left] -\infty, c \right[\cap J$ and $\left] c,+\infty \right[\cap J$ [[Disconnected Space|disconnect]] $J$, thus we proved the contrapose.
Next, due [[Continuity Preserves Connectedness]], $f(X)$ is [[Connected Space|connected]], so it must be an interval, which completes the proof.